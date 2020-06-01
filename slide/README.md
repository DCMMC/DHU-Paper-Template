## slide

To use minted, we must pass shell-escape into xelatex.
e.g. In TexStudio, we need add an user command in build:

```
xelatex_shell_esc: xelatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
```

And then, change default complier into `txs:///xelatex_shell_esc`.
