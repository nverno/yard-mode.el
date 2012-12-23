# yard-mode

Rudimentary support for fontifying YARD tags and directives in ruby
comments.

## Installation

MELPA should support this soon enough.

Add it to your ruby hook:

```scheme
(add-hook 'ruby-mode-hook 'yard-mode)
```

If you would also like `eldoc` support, so that the expected syntax for
the tag beneath your cursor is displayed in the minibuffer, add that
hook too:

```scheme
(add-hook 'ruby-mode-hook 'eldoc-mode)
```

## TODO
1. Some reasonable means of providing completions.
2. Tidy up the defcustoms; most could be parsed from `yard-tag-docstrings`.