# Criar Repositório

echo "# okok" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/tomrzonta/okok.git 
git push -u origin main 

# Comando para ir para Pasta Desejada

cd + (nome da pasta)

# Comando para Verificar Status

git status

# Comando para Adicionar arquivo 

git add + (nome do arquivo) ou
git add . (para todos os arquivos)

# Comando p/ Valirdar Arquivo

git commit

# Comando p/ Commitar Todos Arquivos

git commit -a (all) -m (msg) " texto " (indicando o que foi feito no arquivo)

# Comando p/ Sincro. com Repositório

git push

# Comando p/ Baixar Arquivos do Repositório

git pull

# Comando p/ Clonar Repositório

git clone + (link do repositório) + . (para clonar na pasta selecionada)

# Comando p/ Deletar Arquivo

git rm ou git -D + (nome do arquivo)

# Comando p/ Ver Alterações Feitas

git log

# Comando p/ Mover/Renomear

git mv (ex:git mv rodape.css + css/rodape.css )

# Comando p/ Retornar ao Estado Original do Arquivo

git checkout