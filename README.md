# carlos' dotfiles

[![Build Status][tb]][tp] [![Powered by Antibody][ab]][ap]

> Config files for ZSH, Java, Ruby, Go, Editors, Terminals and more.

![screenshot][scrn]

[ap]: https://github.com/getantibody/antibody
[ab]: https://img.shields.io/badge/powered%20by-antibody-blue.svg?style=flat-square
[tb]: https://img.shields.io/travis/caarlos0/dotfiles/master.svg?style=flat-square
[tp]: https://travis-ci.org/caarlos0/dotfiles
[scrn]: https://raw.githubusercontent.com/caarlos0/dotfiles/master/screenshot.png

## Installation

First, make sure you have all those things installed:

- `git`: to clone the repo
- `curl`: to download some stuff
- `tar`: to extract downloaded stuff
- `zsh`: to actually run the dotfiles
- `sudo`: some configs may need that

Then, run these steps:

```console
$ git clone https://github.com/caarlos0/dotfiles.git ~/.dotfiles
$ cd ~/.dotfiles
$ script/bootstrap
$ chsh -s $(which zsh)
```

## Further help:

- [Personalize your configs](/PERSONALIZATION.md)
- [Understand how it works](/PHILOSOPHY.md)
- [License](/LICENSE.md)

## Contributing

Feel free to contribute. Pull requests will be automatically
checked/linted with [Shellcheck](https://github.com/koalaman/shellcheck).
