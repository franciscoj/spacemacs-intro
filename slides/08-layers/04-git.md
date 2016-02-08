### Git layer (1)

```lisp
     (version-control :variables
                      ;; Shows a some colors on the marging telling
                      ;; which code has been added, removed or changed
                      version-control-global-margin t
                      ;; Chosses the tool to generate that margin's
                      ;; diff
                      version-control-diff-tool 'diff-hl)
     ;; To use magit to manage git.
     git
     ;; To integrate with gist (couldn't make other parts of the
     ;; integration work :( )
     ;; github
```
