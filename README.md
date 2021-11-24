# start app with socket PREPL
	clj -J-Dclojure.server.browser="{:port 4444 :accept cljs.server.browser/prepl :launch-browser false}" -- --main cljs.main --watch "src" --compile cljs-2021.core

## or socket REPL
	clj -J-Dclojure.server.browser="{:port 4444 :accept cljs.server.browser/repl :launch-browser false}" -- --main cljs.main --watch "src" --compile cljs-2021.core

## connect socket REPL with inf-clojure etc.
## open browser with localhost:9000

# start app with command line REPL
clj -M --main cljs.main --compile cljs-2021.core --repl
