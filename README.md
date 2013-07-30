git-find-file.el-
=================

Find files in a git project quickly. Sort them by last modified time

Usage: 
``` bash
cd ~/.emacs.d/
wget 
```

Add the following into your emacs rc:
``` lisp
(require 'git-find-file)
(global-set-key (kbd "C-x C-M-f") 'git-find-file)
```
