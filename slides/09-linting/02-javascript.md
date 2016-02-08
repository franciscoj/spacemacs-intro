### Javascript

```
;; -*- mode: emacs-lisp; -*-
;; Put this on your frontend folder on a file called
;; .dir-locals.el
((nil . ((eval . (progn
                   (setq flycheck-javascript-eslint-executable
                         "/frontend/node_modules/.bin/eslint")
                   )))))
```

When emacs asks you just accept forever :)
