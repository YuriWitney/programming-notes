# Git status resumido:

`git status -s`

# Git log:

1. Pretty format:
   `git log --pretty=format: {comandos}`
   É possível formatar o log de várias maneiras, como mostrar os commits por nome, data ou um mix de cada.

Exemplo:
`git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'`
