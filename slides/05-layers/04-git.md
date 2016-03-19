### Git layer (1)

```lisp
(version-control :variables
                 ;; Shows some colors on the marging telling
                 ;; which code has been added, removed or changed
                 version-control-global-margin t
                 ;; Chosses the tool to generate that margin's
                 ;; diff
                 version-control-diff-tool 'diff-hl)
git ;; To use magit to manage git.
github ;; To integrate with gist
```
Github integration can do more stuff... but I coulnd't make it work
