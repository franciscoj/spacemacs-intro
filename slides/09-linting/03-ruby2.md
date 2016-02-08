### Ruby (2)

You can also use reek :) `gem install reek`

```
  ;; Add this to your config inside dotspacemacs/user-config
  (flycheck-define-checker ruby-reek
    "A Ruby smeel checker using reek

See URL `https://github.com/troessner/reek'."
    :command ("reek" "--format=xml"
              source-original)
    :standard-input t
    :error-parser flycheck-parse-checkstyle
    :modes (enh-ruby-mode ruby-mode)
    :next-checkers ((info . ruby-rubocop)))
  (add-to-list 'flycheck-checkers 'ruby-reek)
```
