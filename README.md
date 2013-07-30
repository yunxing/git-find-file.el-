git-find-file.el-
=================

Find files in a git project quickly. Sort them by last modified time

Forked from https://github.com/hjz/emacs/blob/master/jz/git-find-file.el

Usage: 
``` bash
cd ~/.emacs.d/
wget https://raw.github.com/Imbalism/git-find-file.el-/master/git-find-file.el
```

Add the following into your emacs rc:
``` lisp
(require 'git-find-file)
(global-set-key (kbd "C-x C-M-f") 'git-find-file)
```

Open your emacs, browse into your git repo directory (via eshell, dired-mode, or open any file in your repo), press C-x C-M-f
