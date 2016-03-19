### Eslint global

It just works

### Eslint on your node_modules

Put this on your frontend folder on a file called `.dir-locals.el`

```
;; -*- mode: emacs-lisp; -*-
((nil . ((eval . (progn
                   (setq flycheck-javascript-eslint-executable
                         "/projet/node_modules/.bin/eslint")
                   )))))
```

When emacs asks you just accept forever :)
