# GIT E GITHUB

Guia Pratico de GIT E GITHUB

## Instalação

https://git-scm.com/

## Objective

- [ ] Voce deseja criar pontos na historia da produção do seu projeto.

    touch index.html\
    git add index.html\
    git commit -m "Criação do arquivo index.html"

- [ ] Voce deseja verificar mudanças feitas no seu projeto.

    git log

- [ ] Voce começa uma nova funcionalidade no seu projeto, sem estragar o que ja foi feito.

    git branch feature/login\
    git checkout feature/login\
    touch login.html\
    git add login.html\
    git commit -m "Criação do arquivo de login"\
    git log


- [ ] Voce adiciona as novas funcionalidade ao seu projeto em produção.

    git checkout master\
    git merge feature/login\
    git log

- [ ] Voce que deletar a branch da nova funcionalidade, depois de aplicasr em seu projeto.

    git branch -D feature/login

- [ ] Voce quer colocar seu projeto na nuvem.

    git remote add origin 'https://github.com/'...... \
    git push -u origin master

- [ ] Voce vai pegar um projeto ja iniciado, para trabalhar com o time.

    git clone 'https://github.com'....

- [ ] Antes de enviar a reslução, precisamos atualizar o projeto local.

    git pull

- [ ] Voce precisa voltar um arquivo para um determinado momento da linha do tempo

    git checkout 'id do commit' -- 'nome do arquivo'

- [ ] Voce presisa recuperar algo deletado

    git checkout 'id do commit' -- 'nome do arquivo'

# Commands

- `git init` // Inicia a linha do tempo
- `git add` // Adiciona ou atualiza mudanças para irem a linha do tempo
- `git commit` // Adiciona um ponto na linha do tempo
- `git log` // Visualiza os pontos na linha do tempo / commits
- `git status` // Informa o estado das alterções do nosso projeto
- `git show` // Apresenta determinado ponto na historia
- `git checkout 'branch ou commit'` // Acessa as linha do tempo
- `git branch 'nome'` // Cria linha do tempo
- `git merge` // Unir linhas do tempo
- `git push` // Enviar alterações locais para o repositorio remoto
- `git pull` // Puxa do repositorio remoto
