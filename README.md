# git-github

Git and GitHub for beginners.

Controle de versão é um sistema com a finalidade de gerenciar diferentes versões de um documento.

Configurações básicas:
$ git config --global user.name " nome " ------- setar o nome
$ git config --global user.email " e-mail" ----- setar e-mail
$ git config --global core.editor " editor " --- setar editor de texto
$ git config --list ---------------------------- exibir as configurações que estão setadas

Iniciar repositório:
$ git init ------------------------------------- para iniciar o arquivo .git no repositório

Visualização logs de dados modificados:
$ git log -------------------------------------- logs
$ git log --decorate --------------------------- logs por branch
$ git log --author= " nome " ------------------- buscar os logs pelo nome de quem modificou
$ git shortlog --------------------------------- logs com menos informação
$ git shortlog -sn ----------------------------- logs com apenas nomes e modificações
$ git log --graph ------------------------------ gráfico de logs
$ git show " hash " ---------------------------- visualizar arquivo e conteúdo modificado

Visualizar as mudanças antes de enviar:
$ git status ----------------------------------- exibir aquivos que foram modificados

Visualizar as modificações feitas:
$ git diff ------------------------------------- exibir modificações
$ git diff --name-only ------------------------- exibir apenas nome do arquivo modificado

Para commitar um arquivo que já existiu:
$ git commit -am " mensagem " ------------------ salvar arquivos para transferir ao repositório
