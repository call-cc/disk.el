# disk.el
Simplified find-file, revert-file, save-buffer interface.

This unifies disk operations on a file.  Use it by binding it to a key.  Example setup in your ~/.emacs file:

```el
(global-set-key (kbd "<f9>") 'disk)
(autoload 'disk "disk" "Save, revert, or find file." t)
```
