# Git status resumido:

`git status -s`

# Git log:

1. Pretty format:<br /><br />
   `git log --pretty=format: {comandos}`<br /><br />
   É possível formatar o log de várias maneiras, como mostrar os commits por nome, data ou um mix de cada.

Exemplo:<br /><br />
`git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'`
