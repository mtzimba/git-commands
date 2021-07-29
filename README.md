# Comandos do curso de *Git e Github: Controle e compartilhe seu código e Git* (Alura)

## O que é o Git   
git init - criar um repositório Git  
git status - analisar o estado do nosso repositório  

## Iniciando os trabalhos
git config --local user.name "Seu nome aqui"  
git config --local user.email "seu@email.aqui"  

Como adicionar arquivos para serem commitados com git add;
Como commitar arquivos, utilizando o comando git commit;
Como verificar o histórico de commits, através do git log e algumas de suas opções:
git log --oneline
git log -p
git log --pretty="parametros de formatação"

## Compartilhando o trabalho  
Como adicionar links para os repositórios remotos, com o comando git remote add;
Como baixar um repositório pela primeira vez, clonando-o com o comando git clone;
Como enviar as nossas alterações para um repositório remoto, com git push;
Como atualizar o nosso repositório com os dados no repositório remoto, utilizando git pull;

## Trabalhando em equipe
git branch titulo e logo após execute o comando git branch
git checkout master para voltar à linha de desenvolvimento 
Execute git checkout -b lista para criar uma nova branch, chamada lista e passar a trabalhar nela
omando git merge titulo para trazer o trabalho feito na branch titulo para a branch master
Que o git merge gera um novo commit, informando que houve uma mescla entre duas branches;
Como trazer os commits de uma branch para outra, com o git rebase
Que o git rebase não gera um commit de merge, simplificando o nosso log;
xecute o comando git push local master para enviar suas alterações para o repositório remoto
git pull local master para baixar as alterações que

## Manipulando versões
comando git reset HEAD index.html para trazer o arquivo index.html de volta para a HEAD do projeto (remover do stage, que é o que será enviado para o commit);

git checkout serve para deixar a cópia do código da nossa aplicação no estado que desejarmos:
git checkout <branch> deixa o código no estado de uma branch com o nome <branch>;
git checkout <hash> deixa o código no estado do commit com o hash <hash>.
git revert gera um novo commit informando que alterações foram desfeitas;
  
## Gerando entregas
visualizar quais alterações foram realizadas em cada arquivo, com o comando git diff
comando git tag -a é utilizado para gerar uma nova tag
