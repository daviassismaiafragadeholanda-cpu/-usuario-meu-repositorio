
1) Git

### `git init`
Função: inicializa um repositório Git local.

### `git clone URL`
Função: copia um repositório remoto para a máquina local.

### `git status`
Função: mostra o estado dos arquivos do projeto.

### `git add arquivo`
Função: adiciona um arquivo específico à área de preparação (staging).

### `git add .`
Função: adiciona todas as alterações pendentes.

### `git commit -m "mensagem"`
Função: registra as alterações no histórico local do Git.

### `git log`
Função: mostra o histórico de commits.

### `git diff`
Função: mostra as diferenças entre versões antes de confirmar.

### `git branch`
Função: lista as branches existentes.

### `git branch nome_da_branch`
Função: cria uma nova branch.

### `git checkout nome_da_branch`
Função: troca para outra branch.

### `git switch nome_da_branch`
Função: troca de branch de forma mais moderna.

### `git merge nome_da_branch`
Função: integra alterações de uma branch em outra.

### `git pull`
Função: baixa e mescla alterações do repositório remoto.

### `git push`
Função: envia os commits locais para o GitHub.

### `git remote -v`
Função: mostra os repositórios remotos configurados.

### `git remote add origin URL`
Função: conecta o projeto local a um repositório remoto.

### `git fetch`
Função: baixa atualizações do remoto sem alterar o código local.

### `git reset`
Função: desfaz alterações ou remove commits, dependendo da opção usada.

### `git revert codigo_do_commit`
Função: cria um novo commit para desfazer uma alteração sem apagar o histórico.

### `git stash`
Função: guarda mudanças temporárias sem fazer commit.

### `git tag nome`
Função: cria uma marca de versão.

### `git config --global user.name "Seu Nome"`
Função: define o nome do usuário do Git.

### `git config --global user.email "seuemail@email.com"`
Função: define o e-mail do usuário do Git.

2) GitHub

### Repositório
Função: local onde o projeto fica armazenado no GitHub.

### Branch
Função: ramificação do projeto para desenvolvimento paralelo.

### Commit
Função: registro de uma alteração no projeto.

### Pull Request
Função: solicitação para integrar alterações de uma branch em outra.

### Issue
Função: tarefa, problema ou sugestão de melhoria.

### Fork
Função: cópia de um repositório para outra conta.

### Clone
Função: cópia do repositório remoto para o computador.

### Push
Função: envio de alterações locais para o GitHub.

### Pull
Função: atualização do projeto local com as mudanças do remoto.

### README.md
Função: arquivo que explica o projeto, instruções e informações gerais.

### GitHub Pages
Função: permite publicar sites estáticos diretamente do repositório.

### Actions
Função: automatiza testes, builds e deploys.

### Releases
Função: publica versões do software com tags e arquivos de distribuição.

3) Fluxo básico de uso

```bash
git init
git add .
git commit -m "Primeiro commit"
git remote add origin URL_DO_REPOSITORIO
git push -u origin main