#Git Commands....

### Editar configurações global

### core.editor

// config to open edit file on vscode

` $ git config --global core.editor code `


// open file config

` $ git config --global --edit `

### my custom config

```
[user]
	email = email@email.com
[core]
	editor = code
[push] 
	followTags = true
[alias]
    a = !git add .
	s = !git status -s
    l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
	count = !git shortlog -s --grep 
	amend = !git commit --amend --no-edit 
```


### Commands

// add annotated tag
```
 git tag -a "1.0.1" -m "1.0.1"
```
