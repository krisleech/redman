Install Chicken

Install [readline](http://wiki.call-cc.org/eggref/4/readline) support for REPL.

```
sudo chicken-install readline
```

~/.csirc

```lisp
(use readline)
(current-input-port (make-readline-port))
(install-history-file #f "/.csi.history")
```
