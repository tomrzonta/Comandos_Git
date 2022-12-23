# Comando p/ Att e Compartilhas Repositorio

git fetch

# Comando p/ Mesclar Branches

git merge + (ex: origin/adicionar_css_home) (nome da branch p/ mesclar)

# Comando p/ Criar Submodulos

git submodule add https://github.com/tomrzonta/submodulo.git (submodulo)

# Comando p/ Enviar Arquivos p/ Submodulo

git push --recurse-submodules=on-demand

# Comando p/ Limpar Arquivos NÃO Trackeados

git clean ( Usar o --F para forçar o comando)

# Comando para Identificar Arquivos NÃO Mais Necessários e EXCLUIR

git gc

# Comando p/ Verificar a Integridade dos Arquivos

git fsck

# Comando p/ Mapear Todos os Passos no Repositório

git reflog

# Comando p/ Deletar Atividade pela Hash

git resete --hard + (numero da hash desejada)

# Comando p/ Passar o Arquivo do Programa em ZIP

git archive --format zip --output master_files.zip master

# Comando p/ Salvar os Commits com Bons Nomes

1. Criar branch com nome private_ + (nome da branch) (ex: private_codigos_fonte)
2. Salvar todos os commits necessarios nesse arquivo
3. Voltar para o branch original (de nome não-private)
4. git rebase + (ex: codigos_fonte private_codigos_fonte) --i
5. Aperta I (editar) e muda de PICK para SQUASH os commits que quer deletar
6. REWORD para renomear
7. ESC + :X!
8. Usar # p/ apagar os commits que você não quer, então ESC :X!