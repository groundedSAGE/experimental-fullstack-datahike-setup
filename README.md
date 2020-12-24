# Minimal setup for Datahike testers

This is an example setup repository for those looking to experiment with fullstack Datahike. Currently running **Clojure CLI + shadow-cljs** repls in the same process is not possible. As the `shadow-cljs` build overrides the Datahike dependency with the experimental ClojureScript branch.

### Backend (Clojure CLI)
You can run the `backend.db` namespace in the clojure repl. Without selecting the `:cljs` build alias.

### Frontend (shadow-cljs)
You can run the `frontend.db` namespace in the `browser-repl` with the build `:app`


