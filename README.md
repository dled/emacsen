Emacs configuration
===================

This set up is tailored to 25.1 && 24.(5) and has been largely informed by the following sources: _HT_

I keep any `'init-_this_.el` files in a `.emacs.d/elisp` directory and externals in `.emacs.d/vendor`.   

For starters, some handy reference:

[GNU Emacs Lisp Ref Manual](https://www.gnu.org/software/emacs/manual/)  

- [Startup Summary](http://www.gnu.org/software/emacs/manual/html_node/elisp/Startup-Summary.html#Startup-Summary)  
- [Library Search](http://www.gnu.org/software/emacs/manual/html_node/elisp/Library-Search.html#Library-Search)  
- [Initial Options](http://www.gnu.org/software/emacs/manual/html_node/emacs/Initial-Options.html#Initial-Options)  
- [Init File](http://www.gnu.org/software/emacs/manual/html_node/emacs/Init-File.html#Init-File)  
- [Default Config](https://www.gnu.org/software/emacs/manual/html_node/eintr/Default-Configuration.html#Default-Configuration)  

Also helpful:

[Emacs from Git](https://www.emacswiki.org/emacs/EmacsFromGit)  

## HT

### howardabrams | [ha/dots]([https://github.com/howardabrams/dot-files)  

Unless otherwise noted, most of my config is inspired by / stolen from [Howard Abrams](http://howardism.org/).  

I've also riffed off of [ha/dc-survival-kit](https://github.com/howardabrams/dc-survival-kit).  

- [Magit Intro & Demo 10 29 15](https://www.youtube.com/watch?v=vQO7F2Q9DwA)  
- [Literate DevOps 08 30 15 (28:35m)](https://www.youtube.com/watch?v=dljNabciEGg)  
- [Literate DevOps 09 25 15 (39:55m)](https://www.youtube.com/watch?v=vVJSn8gCh_I&list=PLomc4HLgvuCUoPVpUJSkpsje4333Guxeo&index=12)  
- [Learn you some lisp](https://www.youtube.com/watch?v=3T00X_sNg4Q)  

### aaronbieber  | [ab/init.el](https://github.com/aaronbieber/dotfiles/blob/master/configs/emacs.d/init.el)  

Probably the first 30+ minute talk on Emacs I ever watched, [Aaron Bieber](http://blog.aaronbieber.com/) has a great intro to Emacs `vi`a [Evil Mode](https://www.youtube.com/watch?v=JWD1Fpdd4Pc)  

_Thanks!_

### rpdillon     | [rd/emacs-config](https://github.com/rpdillon/emacs-config)  

Rick Dillon's got a great weblog: [KillRing](https://killring.org/hack-emacs/).  

Also appreciated a solid [Hack Emacs tutorial series](https://www.youtube.com/user/rpdillon) & [notes](https://github.com/rpdillon/hack-emacs-notes).  

## Extending Emacs

Also appreciated Erik Hetzner's [EmacsConf 2015](http://emacsconference.com/) presentation on Emacs as a [scholastic tool](http://www.e6h.org/talks/emacsconf-2015/index.html).  

A few packages to check out, soon:  

- org-ref
- helm-bibtex
- zotero & zoxtxt
- gopar


## Vendor  

Web development

- [skewer-mode](https://github.com/skeeto/skewer-mode)  
- [emmet-mode](https://github.com/smihica/emmet-mode)  
- [wrap-region.el](https://github.com/rejeep/wrap-region.el)  
- [expand-region.el](https://github.com/magnars/expand-region.el)  

Clojure development

- [clojure-mode](https://github.com/clojure-emacs/clojure-mode)  
- [cider](https://github.com/clojure-emacs/cider)  
- [smartparens](https://github.com/Fuco1/smartparens)  
- [clj-refactor.el](https://github.com/clojure-emacs/clj-refactor.el)  
- [clojure-snippets](http://github.com/swannodette/clojure-snippets)  

Pair-programming

- [screencast.el](https://github.com/rpdillon/screencast)  
