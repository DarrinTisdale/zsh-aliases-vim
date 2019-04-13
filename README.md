# zsh-aliases-vim

## Purpose

This zsh plugin aliases the existing `vim` that exists (on my Mac, at `/usr/bin/vim`) with the one provided by [Homebrew](https://brew.sh). 

## Use

To use it, you should first install [`vim`](https://www.vim.org). 

For macOS users, you can use [Homebrew](https://brew.sh):
```
brew install vim
```
For Windows users, you can use [Chocolatey](https://chocolatey.org):
```
choco install vim
```

Next, clone this repo into your custom plugins directory. For my installation using [Oh My Zsh](https://ohmyz.sh/), I cloned the repo to `~/.oh-my-zsh/custom/plugins`.

Lastly, add `zsh-aliases-vim` to the plugins array of your zshrc file:
```
plugins=(... zsh-aliases-vim)
```

Restart your zsh session, and the aliases will be available.

## Aliases

```bash
alias vim='/usr/local/bin/vim'                       # list, size, show type
```

## Next Steps

* Add in zshrc options to configure options
  1. which other vim to use (vim, neovim, macvim, others)
  2. other options I have not considered yet
* Create function to configure different profiles of aliases, so that different alias configurations can be enabled

## Thanks

Big thanks to Oh My Zsh, Homebrew, and the Vim community for these terrific tools. They have made the command line fun again.

## Contributors

- [Darrin Tisdale](https://github.com/darrintisdale)
