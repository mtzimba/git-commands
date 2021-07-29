# Comandos do curso de *Git e Github: Controle e compartilhe seu código e Git* (Alura)

## O que é o Git  
git init - criar um repositório git   
git status - analisar o estado do repositório  

## Iniciando os trabalhos  
git config --local user.name "Seu nome aqui" - configurar o usuário do git para o repositório  
git config --local user.email "seu@email.aqui" - configurar o e-mail do git para o repositório  

git add - adicionar os arquivos para serem commitados  
git commit - commitar arquivos  
git log - verificar o histórico  de mudanças
git log --oneline
git log -p
git log --pretty="parametros de formatação"

## Compartilhando o trabalho  
git remote add - adicionar links para os repositórios remotos  
git clone - baixar um repositório clonando-o  
git push - enviar as alterações para um repositório remoto  
git pull - atualizar o repositório local com os dados do repositório remoto  

## Trabalhando em equipe
git branch - criação de branch  
git checkout master - para voltar à linha de desenvolvimento  
git checkout -b - criar um novo branch e passar a trabalhar nela  
git merge <branch> - para trazer o trabalho feito numa branch para outra  
git merge gera um novo commit  
git rebase <branch> - para trazer o trabalho feito numa branch para outra  
git rebase não gera um commit de merge  
git push local master para enviar as alterações locais para o repositório remoto  
git pull local master para baixar as alterações do repositorio remoto para o local  

## Manipulando versões
git reset HEAD index.html - para trazer o arquivo index.html de volta para a HEAD do projeto (remover do stage, que é o que será enviado para o commit)  
git checkout serve para deixar a cópia do código da nossa aplicação no estado que desejarmos  
git checkout <branch> deixa o código no estado de uma branch com o nome <branch>  
git checkout <hash> deixa o código no estado do commit com o hash <hash>  
git revert gera um novo commit informando que alterações foram desfeitas  
  
## Gerando entregas
git diff - visualizar quais alterações foram realizadas em cada arquivo  
git tag -a é utilizado para gerar uma nova tag  
