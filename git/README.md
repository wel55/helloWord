###instalação

https://git-scm.com/download

git config --global user.email "welingtonmotta@hotmail.com"
git config --global user.name "wel55"

#git  //inicia git
#git add <name>//Add arquivos
#git commit -m "[MENSAGEM]updated lp.html" //envia arquivos paraw repositorio
#git status //mostra atatus
#git log //mostro mudanças
#git show 0c9229621d4b1db799e8c844feaf6ca21e9f94c7 // mostra a mundança do arquivo
#git branch //mostra todos branch
#git branch feature/cart   //cria outr linha do tempo
#git checkout feature/cart //entra na linha do tempo 
#git merge feature/cart // para unir as linhas do tempo
#git branch -D feature/cart   //delete linha do tempo

--------------------------------------------------------------------------

GIT E GITHUB
Guia prático para iniciantes.

Instalação
https://git-scm.com/download

SCENES
 Você deseja criar pontos na história da produção do seu projeto

 Você deseja verificar mudanças feitas no seu projeto

 Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.

 Você adiciona as novas funcionalidades ao seu projeto em produção

 Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

 Você quer colocar seu projeto na nuvem.

 Você vai pegar um projeto já iniciado, para trabalhar com o time

 Você precisa resolver um conflito.

 Antes de enviar a resolução, precisamos atualizar o projeto local.

 Você precisa voltar um arquivo para um determinado momento da linha do tempo.

 Você precisa recuperar algo deletado.

git init // inicia a linha do tempo
git add // adiciona ou atualiza mudanças para irem para a linha do tempoo
git commit // adiciona um ponto na linha do tempo
git log // visualiza os pontos na linha do tempo / commit
git status // informa o estado das alterações do nosso projeto
git show // apresenta determinado ponto na história
git branch // gerenciar novas linhas do tempo
git checkout // manipula as linhas do tempo
git merge // unir linhas do tempo
git push // envia alterações locais para o repositório remoto
git clone // clonar um projeto / repositório
git pull // puxa do repositório remoto


… Ou crie um novo repositório na linha de comando
echo "# helloWord" >> README.md 
git init 
git add README.md 
git commit -m "primeiro commit" 
git remote add origin https://github.com/wel55/helloWord.git
 git push -u origin master
… Ou envie um repositório existente a partir da linha de comando
git remote add origin https://github.com/wel55/helloWord.git
 git push -u origin master