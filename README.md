# git-github

## Git and GitHub for beginners.

### Controle de versão é um sistema com a finalidade de gerenciar diferentes versões de um documento.

#### 1. Configurações básicas:
- $ git config --global user.name " nome "  setar o nome
- $ git config --global user.email " e-mail"  setar e-mail
- $ git config --global core.editor " editor " setar editor de texto
- $ git config --list  exibir as configurações que estão setadas

#### 2. Iniciar repositório:
- $ git init  para iniciar o arquivo .git no repositório

#### 3. Visualização logs de dados modificados:
- $ git log  exibir logs.
- $ git log --decorate logs por branch.
- $ git log --author= " nome "  buscar os logs pelo nome de quem modificou.
- $ git shortlog  logs em ordem alfabetica, autores, quantos commits esses autores fizeram e quais foram.
- $ git shortlog -sn  logs com apenas nomes e quantidade de commits.
- $ git log --graph  mostra em forma gráfica o que está acontecendo com as branchs e as versões.
- $ git show " hash "  visualizar commit por hash.

#### 4. Visualizar as mudanças que estão no stage:
- $ git status  exibir aquivos que foram modificados.

#### 5. Visualizar os detalhes das modificações que não estão no stage:
- $ git diff  exibir modificações feitas no arquivo.
- $ git diff --name-only  exibir apenas nome do arquivo modificado.

#### 6. Para commitar um arquivo:
- $ git commit -am " mensagem "  adiciona todos os arquivos modificados para área de stage e, em seguida, faz o commit dos mesmos.
- $ git commit -m " mensagem" faz commit apenas dos arquivos modificados e que encontram-se adicionados na área de stage

#### 7. Desfazendo coisas com o reset:
- $ git checkout retorna o arquivo da unstage para antes da edição
- $ git reset HEAD retorna o arquivo da stage para unstage
- $ git reset --soft " hash " retorna o arquivo que estava pronto para commitar para stage
- $ git reset --mixed " hash " retorna o arquivo que estava pronto para commitar para unstage
- $ git reset --hard " hash " ignora todo o commit e modificações feita no arquivo
