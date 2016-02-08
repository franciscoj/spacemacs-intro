### Ruby layer

```lisp
     (ruby :variables
           ;; normal ruby mode is better IMHO
           ruby-enable-enh-ruby-mode nil
           ;; to make sure it takes rbenv into account
           ruby-version-manager 'rbenv
           ;; to run the specs with rspec instead of rake
           ruby-test-runner 'rspec)
```
