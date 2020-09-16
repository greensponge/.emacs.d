<p align="center"><img src="assets/images/emacs-logo.png" width=150 height=150/></p>
<p align="center">This repository contains my Emacs configuration.</p>

---

Work in progress, I'll expand the description after I've configured my Emacs a little further along.

But for now, the most important files are:

* [`config.org`](https://github.com/greensponge/.emacs.d/blob/master/config.org/):
 This is the main configuration file. When changes are saved here it will update the generated `config.el` file automatically.

* [`init.el`](https://github.com/greensponge/.emacs.d/blob/master/init.el/):
  This loads the generated configuration file when Emacs starts.

# Getting started
If you decide to clone, you will probably be prompted if you want to allow an unsafe local variable, and possibly for missing GTD files depending on your environment. The prompts should in this case only happen the first time you load Emacs. 

If you don't want to clone, then the best way is to just look at the [`config.org`](https://github.com/greensponge/.emacs.d/blob/master/config.org/) file and try out interesting snippets one at a time.
