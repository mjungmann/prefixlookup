# prefixlookup.el

## Look up and insert semantic web prefix URIs

This file provides completion for semantic web prefixes.
On completion the prefix URI will be inserted at point.
Based on the information published at: https://prefix.cc/context

## Installation & usage

1. Clone repository to destination of choice, e.g.:

```
git clone https://github.com/mjungmann/prefixlookup.git ~/emacs/prefixlookup
```

2. Edit your .emacs to load the file; change keybinding if needed:

```
(load "~/emacs/prefixlookup/prefixlookup.el")
(global-set-key
 (kbd "C-c C-p")
 'prefixlookup-insert-uri)
```