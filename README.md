# Alex's Dotfiles

This repo is my newest rebuild of my dotfiles.
It was re-built from the ground up for use with macOS 10.13+

The focus is on easy terminal navigation and slick vim and tmux configs.

Once cloned, symlink all of the files to your home dir.

```
$ ln -s ~/projects/dotfiles/.* ~/
```

Then remove the git dir

```
$ rm -rf ~/.git
```

Install the Vim plugins:

```
:VundleInstall
```
