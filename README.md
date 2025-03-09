Créer un lien symnolique pour dire a tmux de chercher dans le bon dossier.

```shell
ln -sf ~/tmux-config/.tmux.conf ~/.tmux.conf
```

Puis le sourcer dans tmux

```shell
tmux source-file ~/.tmux.conf
```
