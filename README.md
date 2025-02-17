<h1>
  Git
  <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40"/>
</h1> 
<h3>Learning how to use git</h3> 
<p>Os comandos a seguir são feitos no Git Bash.</p>


```
Starting a new projct by the command line example:
echo "# Nome" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/user/repository.git
git push -u origin main
```
<h3>All the commands</h3>

`git config --global user.name "Seu Nome"`
#adicionar seu nome de usuário

`git config --global user.email "seuemail@email.com"`
#adicionar seu email de usuário

`git clone link`
#clonar um projeto git

`git init` 
#iniciar um projeto git

`git add .` 
#para adicionar todos os arqs

`git add "meuCodigo.py"` 
#adicionar apenas um arq escolhido

`git status` 
#ver o que ocorre ou repositório

`git commit` 
#adicionar

`git commit -m "commit 1"` 
#adicionar com uma mensagem

`git diff` 
#linhas modificadas, vermelho(remove/altera) e verde(adiciona)

`git log` 
#histórico de commits

`git restore nomearq` 
#ele volta para a versão anterior

`git restore --staged nomearq` 
#ele volta para a versão anterior na área citada

`git push` 
#enviar

`git remote add origin link` 
#enviar para um link remoto

`git branch --unset-upstream` 
#criar a branch em um reposiório existente

`git push --set-upstream origin master` 
#enviar para uma branch master

`git reflog` 
#ver as versões, a mais atual está no topo

`git reset --hard codigo` 
#voltar a uma versão específica

`git branch`
#branchs - a verde é a que se está localizado

`git branch nome` 
#cria uma nova branch

`git chekout nome` 
#muda de branch

`git clone --branch NOME_DA_BRANCH --single-branch URL_DO_REPOSITORIO`
#clona de uma branch específica

`git pull` 
#pegar as versões mais atuais

`git merge nome` 
#puxa de uma branch para a atual

`touch .gitignore` 
#para que algum arquivo não seja enviado para nuvem - dentro desse arquivo são adicionadas as pastas ou arquivos que não devem ser enviados

`git restore <arquivo>` 
#deseja desfazer as alterações antes de adicionar ao git

`git restore .` 
#deseja desfazer todas as alterações antes de adicionar ao git

`git rm --cached <arquivo>` 
#remover um ou mais arquivos do Git, mas mantê-los no seu sistema de arquivos

`git rm -r --cached .` 
#remover todos os arquivos do Git, mas mantê-los no seu sistema de arquivos

`git rm --cached .` 
#remover todos os arquivos não rastreados do Git, mas mantê-los no seu sistema de arquivos

`git clean -n` 
#verificar quais arquivos serão removidos

`git clean -f` 
#remova os arquivos não rastreados

`git clean -fd`
#remover diretórios não rastreados

`git clean -fx` 
#para arquivos ignorados
