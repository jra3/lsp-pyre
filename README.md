# lsp-pyre
An Emacs LSP client for python using pyre and lsp-mode.

[![MELPA](https://melpa.org/packages/lsp-pyre-badge.svg)](https://melpa.org/#/lsp-pyre)

## Installation

Install [`lsp-mode`](https://github.com/emacs-lsp/lsp-mode) first, and either clone
this repository, or install from MELPA. Add the following to your `.emacs`:

```emacs-lisp
(require 'lsp-mode)
(require 'lsp-pyre)
(add-hook 'python-mode-hook 'lsp)
```

## Configuration

I recommend turning on company-mode and flycheck-mode in your particular major mode as LSP will be feed those modes and give you all the *magic*.
