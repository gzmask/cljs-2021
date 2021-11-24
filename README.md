# socket REPL
clj -J-Dclojure.server.browser="{:port 4444 :accept cljs.server.browser/repl}" -- --main cljs.main --watch "src" --compile cljs-2021.core

clj -J-Dclojure.server.browser="{:port 4444 :accept cljs.server.browser/repl}" -M --main cljs.main --compile cljs-2021.core --repl
