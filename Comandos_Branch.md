# Comando p/ Visualizar os Branches

git branch

# Comando p/ Criar um novo Branch

git branch + (nome do branch)

# Comando p/ Mudar/Criando de Branch

git checkout + (nome do branch)
git checkout -b (nome do branch) (para criar e mudar ao mesmo tempo)

# Comando p/ Unir Branches

git merge + (nome do branch) OBS: Nunca dar merge na master a partir do seu branch

# Comando p/ Salvar Modificações e Mudar Abordagem

Git Stash
Git stash list

# Comando p/ Recuperar o Stash

git stash apply + (numero da stash) (lembrando que sempre tem que dar git stash pra trocar entre elas)

git stash show -p + (numero da stash) (Mostra exatamente o que foi modificado na stash)

git stash clear

git stash drop + (n da stash)

# Comando p/ uma TAG

git tag -a (nome da tag) -m (msg)  (ex: git tag -a v1.0 -m "primeira versao)

git tag (ver lista de tags)

git checkout + (nome da tag p/ alterar entre elas)

# Comando p/ Enviar TAG para Repositório

git push origin + (nome da tag)

git push origin -tags (envia todas das tags salvas)

# Comando p/ Exibir Diferenças entre Branches

git diff

git diff head:a.txt a.txt (Comparando arquivo da Main c/ arquivo da branch específico)

# Comando p/ LOG Resumido do Projeto

git shortlog (mostra os commits feitos)
