# .zsh_custom
Organizing my .zshrc

## Installation

```bash
# clone the repo
git clone git://github.com/jonowar/.zsh_custom.git ~/.zsh_custom

# update the ZSH_CUSTOM variable to point at this repo
sed "s/\(ZSH_CUSTOM=\)\(.*\)/\1\$HOME\/.zsh_custom/g" ~/.zshrc > ~/.zshrc.tmp && mv ~/.zshrc.tmp ~/.zshrc
```

## Adding stuff
Create a new file with a filename in the format of `<order in which this will be run>.<brief description>.zsh` in this directory.

That's it!
