# dotfiles
## Vim
Install Plugins:

```
$ vim +PluginInstall +qall
```

## Syncronice with home
```
$ rsync --exclude={README.md,.git/,LICENSE} . ~
```
