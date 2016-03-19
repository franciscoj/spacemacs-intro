### Better have word motion (better as in Vim)

```lisp
;; To have word motion in underscored words
(add-hook 'js2-mode-hook #'(lambda () (modify-syntax-entry ?_ "w")))
(add-hook 'ruby-mode-hook #'(lambda () (modify-syntax-entry ?_ "w")))
```
