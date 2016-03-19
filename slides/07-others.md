### Better have word motion (better as in Vim)

```lisp
;; To have word motion in underscored words
(add-hook 'js2-mode-hook #'(lambda () (modify-syntax-entry ?_ "w")))
(add-hook 'ruby-mode-hook #'(lambda () (modify-syntax-entry ?_ "w")))
```

### See more on

[My emacs setup](http://dev.otrobloggeek.com/2016/03/08/my-emacs-setup.html)

Linux only, sorry :( but easy to do on mac as well.
