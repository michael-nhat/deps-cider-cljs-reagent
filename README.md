To start Figwheel, open `src/cljs/myapp/core.cljs` in Emacs and type <b>`C-c C-x j s`</b>

Or start from a terminal by typing <b>`clj -M:figwheel`</b>

For production run <b>`clj -M:prod`</b> then open the `resources/public/index.html` file in a browser to run.

clj -Sverbose -M:cider:cider/nrepl

connect to cider repl then (figwheel-main) will init and open in browser 9500
