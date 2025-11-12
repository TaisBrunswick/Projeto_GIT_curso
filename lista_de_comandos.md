`git init`

## Lista de comandos

## Rotina básica para adicionar versão na linha do tempo
Checando o status dos arquivos, adicionando na_sataging area_, faz o _commit_ para salvar na linha do tempo e faz o _push_ para mandar pro GitHub.

`git status`

`git add <nome do arquivo>`

`git commit -m <mensagem>`

`git push`

## Comandos básicos
`git init`
cria a sua pasta no Git

`git add <nome do arquivo>`
permite transferir os arquivos para o commitde 

`git commit -m <mensagem>`
permite registrar as alterações realizadas nos arquivos que estão na sataging area

`git log --help`
permite encontrar ajuda sobre o comando

`git log --abbrev-commit`
permite abreviar os nomes dos identificadores dos commits

`git show <commit> <commit>`
permite mostrar o que tem em cada commit

`git diff <commit old> <commit new>`
permite comparar commits. A ordem faz diferença sendo o primeiro a referência.

`git status`
permite ver onde estão as pastas dentro do Git

`git push`
sincroniza o computador e o remoto

`git remote add origin <ssh>`
cria uma ponte entre o GitHub e o computador

`git pull`
busca as informações que foram feitas no GitHub para sincronizar no seu computador. 

`git revert`
recupera a versão anterior e é uma solução menos arriscada para recuperar seu arquivo anterior. Se der errado, vc pode reverter a reversão inicial.

`git reset`
utilizado para tentar recuperar um arquivo em versão anterior em caso de você ter cometido um erro e fez um commit errado. Você volta no tempo e pode perder seu histórico. CUIDADO!!

`git clone <SSH>`
usado para recuperar o repositório local ou para baixar os dados em um novo computador. O comando refaz a pasta, cria a ponte e copia todos os arquivos. A pasta .gitignore deve ter sumido se ela não estivesse no GitHub.
