```clojure
^{:nextjournal.clerk/visibility #{:hide :hide-ns}}
(ns index
  (:require [nextjournal.clerk :as clerk]))
```

# 🎪 Minimal Clerk Demo

```clojure
(clerk/html
  [:p "The answer to life, the universe, and everything: " (+ 23 19)])
```

