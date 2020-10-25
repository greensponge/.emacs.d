<p align="center">This repository contains my Emacs configuration.</p>
<p align="center"><img src="assets/images/gruvbox-example.png"/></p>

<blockquote>
    Modeline: <a href="https://github.com/seagle0128/doom-modeline">DOOM Modeline</a> <br>
    Theme: <a href="https://github.com/hlissner/emacs-doom-themes">DOOM Gruvbox</a> <br>
    Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a>
</blockquote>

The most important files:

* [`config.org`](https://github.com/greensponge/.emacs.d/blob/master/config.org/):
 This is the main configuration file where all snippets are organized under categories. When changes are saved here, the generated `config.el` file will update automatically.

* [`init.el`](https://github.com/greensponge/.emacs.d/blob/master/init.el/):
  This file loads the `config.el` configuration file when Emacs starts.

# Getting started
If you're starting fresh, clone this repository into your home directory:

```
git clone https://github.com/greensponge/.emacs.d.git
```

If you're on Windows it can vary if you're using `WSL`, `Chocolatey` or have installed Emacs manually. In general you just have to find where your Emacs home directory lives and replace the .emacs.d folder with this one.

# Snippets
Look at the [`config.org`](https://github.com/greensponge/.emacs.d/blob/master/config.org/) file and take what you like.

If you find something you want to try out, paste it into your own configuration and press:

`C-x C-e`

With the marker/point at the end of the functions closing paranthesis.

If you're unfamiliar, this is what's called a key chord in Emacs, and it's simply a succint way of saying: 

`CTRL+X CTRL+E`

