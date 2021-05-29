> ## GIT E GITHUB

### Guia pratico para iniciantes.
> ### Criando pontos na Historia
#### Comando para iniciar um git no projeto
* git init

#### adiciona ou atualiza mudanças do arquivo para commit
* git add "nome do arquivo"

#### Utilizado para Fazer comentarios no commit e adiciona ponto na linha do tempo
 * git commit -m

 #### Visualiza os pontos(branch) na linha do tempo/ commit que foi criado no repositorio
 * git log

 > ## Verificar mudanças feitas no projeto

#### Informa  o estado das alterações do projeto
* git status

### verifica as mudanças feitas no projeto
* git show "hash do commit"

### Apresenta determinado ponto na historia
* git show

> ## Começa uma nova funcionalidade na projeto

#### Criar uma nova branch
* git branch "nome"

#### Mudar de branch
* git checkout "nome da branch"

#### mostrar todas branch criadas na linha do tempo
- git branch
> ## Adicionar novas funcionalidades no projeto

#### Vai fazer a união da branch atual com outra branch 
- git merge 'nome branch'

> ## Deletar branch da nova funcionalidade
- git branch -D "nome Branch"

> ## Colocar Projeto na nuvem
#### visualiza os repositorios remotos
- git remote -v
#### para empurar o repositorio local para repositorio remoto
- git push
#### so usa quando for subir pela primeira vez
- git push -u origin master

