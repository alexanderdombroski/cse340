# Web Backend - CSE340 in both Deno and Express

As a learning activity, I am completing all the assignments for this class using Deno, typscript and native Deno libraries like Oak (to make up for the lack of express's middleware), and following along with the class using Express and Node.js.

<!-- INSERT SUBMODULE TABLE HERE -->

## Main Differences

### First App



#### "deno run dev" vs "npm run dev"
```zsh
# deno run dev
deno run --allow-env --env-file=.env --allow-net --watch server.ts

# npm run dev
nodemon --env-file=.env server.js
```
* Deno has nodemon functionality built in with --watch
* Deno has increased security and requires permission flags.


#### Sending Requests
* Deno.serve() is a combination of express's app.get() and app.listen()


### Second App
