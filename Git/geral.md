# Git status resumido:

`git status -s`

# Git log:

1. Pretty format:<br /><br />
   `git log --pretty=format: {comandos}`<br /><br />
   É possível formatar o log de várias maneiras, como mostrar os commits por nome, data ou um mix de cada.

Exemplo:<br /><br />
`git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'`

# Criar Tags:

1. Annotated:<br /><br />
`git tag -a "1.0.0" -m "1.0.0"`<br /><br />
Cria tag do tipo annotate com a mensagem 1.0.0.

# Git commit:

1. Adicionar alteração ao commit anterior, sem mensagem<br /><br />
`git commit --amend --no-edit`
