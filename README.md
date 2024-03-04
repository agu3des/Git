<h1>
  Git
  <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40"/>
</h1> 
<h3>Learning how to use git</h3> 
<p>Os comandos a seguir são feitos no Git Bash.</p>

----------------------------------------------------------------
<h3>Starting a new projct by the command line example:</h3>
<p>echo "# APIGemini" >> README.md</p>
<p>git init</p>
<p>git add README.md</p>
<p>git commit -m "first commit"</p>
<p>git branch -M main</p>
<p>git remote add origin https://github.com/agu3des/APIGemini.git</p>
<p>git push -u origin main</p>

----------------------------------------------------------------

<h3>All the commands</h3>
`git init` */iniciar um projeto git/*

`git clone` */clonar um projeto git/*

`git add .` */para adicionar todos os arqs/*

`git add "meuCodigo.py"` */adicionar apenas um arq escolhido/*

`git status` */ver o que ocorre/*

`git commit` */adicionar/*

`git commit -m "commit 1"` */adicionar com uma mensagem/*

`git config --global user.name "Seu Nome"` */adicionar seu nome de usuário/*

`git config --global user.email "seuemail@email.com"` */adicionar seu email de usuário/*

`git push` */enviar/*

`git remote add origin link` */enviar para um link remoto/*

`git branch --unset-upstream` */criar a branch em um reposiório existente/*

`git push --set-upstream origin master` */enviar para uma branch master/*

`git reflog` */ver as versões, a mais atual está no topo/*

`git reset --hard codigo` */voltar a uma versão específica/*

`git branch`*/branchs - a verde é a que se está localizado/*

`git branch nome` */cria uma nova branch/*

`git chekout nome` */muda de branch/*

`git pull` */pegar as versões mais atuais/*

`git merge nome` */puxa de uma branch para a atual/*

`touch .gitignore` */para que algum arquivo não seja enviado para nuvem - dentro desse arquivo são adicionadas as pastas ou arquivos que não devem ser enviados/*
