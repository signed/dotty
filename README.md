Dotfiles, my dotfiles.

# Getting started

````
./activate
````
# [zsh function loading](https://dev.to/lukeojones/1up-your-zsh-abilities-by-autoloading-your-own-functions-2ngp)
add those lines to your `~/.zshrc`

```
fpath=("$HOME/dev/github/signed/dotty/dotfiles/zsh/functions
autoload -Uz $fpath[1]/*(.:t)
```
 

# Opportunities

## Found [dotbot](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/) today. 
