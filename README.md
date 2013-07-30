git-find-file.el-
=================

Find files in a git project quickly. Sort them by last modified time

Usage: 

cd ~/.emacs.d/
wget 

Add the following into your emacs rc:

(require 'git-find-file)
(global-set-key (kbd "C-x C-M-f") 'git-find-file)
