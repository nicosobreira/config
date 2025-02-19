# Meus Dotfiles

## Instalação

```bash
git clone --bare https://github.com/nicosobreira/config $HOME/.config
```

## Mantendo

Declare o alias a seguir para manter a repo
```bash
alias config='/usr/bin/env git --git-dir=$HOME/.config/ --work-tree=$HOME'
```
