Comandos Git Para Brasileiros
============
<h1 align="center">
    <img alt="GithubBR" title="#githubBR" src="githubBR.png" width="300px" />
</h1>

## Versões traduzidas
___

_Uma lista dos comandos Git mais usados_

--
### Setup & Configurando Conta

| Comando | Descrição |
| ------- | --------- |
| `git config --global user.name “[firstname]”` | Colocando seu nome |
| `git config --global user.email “[valid-email]”` | Colocando seu e-mail usado no Github |
| `git config --global color.ui auto”` | Deixando colorido para idenfificar alterações |

### Obtendo & Criação de Projetos

| Comando | Descrição |
| ------- | --------- |
| `git init` | Inicializa um repositório Git local |
| `git clone ssh://git@github.com/[usuario]/[nome-repositorio].git` | Cria uma cópia local de um repositório remoto |

### Básicos

| Comando | Descrição |
| ------- | --------- |
| `git status` | Verifique ou Checa o status do seu repositorio|
| `git add [nome-arquivo.txt]` | Adiciona um arquivo ou para todos que estão trabalhando no diretório |
| `git add -i [nome-arquivo.txt]` | Adiciona arquivo através de um menu interativo |
| `git add -A`/`git add .` | Adiciona todos os arquivos novos ou modificados para a área de stage |
| `git commit -m "[Mensagem de Commit]"` | Comita as alterações |
| `git commit -am "[Mensagem de Commit]"` | Comita e já adiciona ao mesmo tempo |
| `git rm -r [nome-arquivo.txt]` | Remove um arquivo (ou pasta) |

### Ramificação & Mesclando

| Comando | Descrição |
| ------- | --------- |
| `git branch` | Lista as branches (o asterisco denota a branch atual) |
| `git branch -a` | Lista todas as branches (local e remoto) |
| `git branch [nome da branch]` | Cria uma nova branch |
| `git branch -d [nome da branch]` | Deleta uma branch |
| `git push origin --delete [nome da branch]` | Deleta uma branch remota |
| `git checkout 'nome do diretório'` | Remove mudanças de um determinado arquivo |
| `git checkout -b [nome da branch]` | Cria uma nova branch e muda para ela |
| `git checkout -b [nome da branch] origin/[nome da branch]` | Clona uma branch remota e muda para ela |
| `git checkout [nome da branch]` | Seleciona uma branch |
| `git checkout -` | Muda para a última branch |
| `git checkout -- [nome-arquivo.txt]` | Descarta modificações de um arquivo |
| `git merge [nome da branch]` | Faz um merge de uma branch na branch atual |
| `git merge [source branch] [branch alvo]` | Faz um merge de uma branch em outra branch |
| `git stash` | Tirar o estado sujo do seu diretório de trabalho |
| `git stash clear` | Remove todas as entradas 'stash' |

### Compartilhar & Subir Projects

| Comando | Descrição |
| ------- | --------- |
| `git push origin [nome da branch]` | Enviar uma branch para seu repositório remoto |
| `git push -u origin [nome da branch]` | Envia as alterações da branch informada para um repositório remoto (and selecionar a branch) |
| `git push` | Envia as alterações para o repositório remoto (branch atual) |
| `git push origin --delete [nome da branch]` | Deletar uma branch remota |
| `git pull` | Atualiza o repositório local para o último commit |
| `git pull origin [nome da branch]` | Recebe alterações do repositório remoto |
| `git remote add origin ssh://git@github.com/[usuario]/[nome-repositorio].git` | Adicionar um repositório remoto |
| `git remote set-url origin ssh://git@github.com/[usuario]/[nome-repositorio].git` | Seta um repositório da origin branch para o SSH |

### Inspeção & Comparação

| Comando | Descrição |
| ------- | --------- |
| `git log` | Ver modificações |
| `git log --summary` | Ver modificações (detalhadas) |
| `git diff [branch original] [branch alvo]` | Visualizar alterações antes de mesclar |


Feito com :heart: by  [Felipe Schiavon] <span>&#x1f1e7;&#x1f1f7;</span> :wave: [Linkedin!](https://www.linkedin.com/in/felipeschiavon/)
Inspirado em joshnh / education.github / jedmao / pedronauck
