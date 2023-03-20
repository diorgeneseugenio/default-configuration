## Configurações GIT

- git config --global user.name "Diórgenes Eugênio"
- git config --global user.email diorgeneseugenio
- git config --global core.editor code

### Arquivo final

```
[user]
	name = Diórgenes Eugênio
	email = diorgeneseugenio@gmail.com
[core]
	editor = code
[alias]
	s = status -s
	c = !git add -A && git commit -m
	l = log --all --graph --decorate --oneline --abbrev-commit
	remotes = remote -v
	p = pull
	ps = push
	st = stash
	stp = stash pop
[push]
	autoSetupRemote = true
```

### Comandos extras

- Abrir arquivo de configuração on editor
  - git config --global -e
