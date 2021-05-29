> ### GIT E GITHUB![](https://pipz.com/static/images/blog/eddie.png)

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

 > ### Verificar mudanças feitas no projeto

#### Informa  o estado das alterações do projeto
* git status

### verifica as mudanças feitas no projeto
* git show "hash do commit"(Sem as aspas)

### Apresenta determinado ponto na historia
* git show

> ### Começa uma nova funcionalidade na projeto

#### Criar uma nova branch
* git branch "nome"

#### Mudar para uma determinada branch
 git checkout "nome da branch"(Sem as aspas)
#### Para volta a um arquivo para o um determinado momento da linha do tempo e recuperar um determinado arquivo
* git checkout "hash" -- "arquivo.extensao"(Sem as aspas)
#### Recurar arquivo  so vai funcionar se o arquivo se nao foi feito commit no arquivo
- git checkout -- "arquivo.extensao"(Sem as aspas)

#### mostrar todas branch criadas na linha do tempo
- git branch
> ### Adicionar novas funcionalidades no projeto

#### Vai unir a linha do tempo
- git merge 'nome branch'

> ### Deletar branch da nova funcionalidade
- git branch -D "nome Branch"(Sem as aspas)

> ### Colocar Projeto na nuvem
#### visualiza os repositorios remotos
- git remote -v
#### Para subir o repositorio local para repositorio remoto varias vezes.Envia alterações locaispara repositorio remoto
- git push
 #### So usa quando for subir pela primeira vez
- git push -u origin master 

> ### __Para baixar as alterações que ja foram feitas no projeto__
- git pull
> ### clonar **projeto/repositorio**
- git clone


