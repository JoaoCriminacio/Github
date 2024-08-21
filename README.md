<h1 align='center'>Comandos do Git</h1>

### `git config --global user.name"SeuNome"` - configurar seu nome no Git;
---
### `git config --global user.email"SeuEmail"` - configurar seu email no Git;
---
### `git init` - criar dentro da pasta atual uma nova pasta com a extensão .git;
---
### `git status` - verificar o status do commit;
---
### `git log` - acessar o histórico dos commits (verificar quantos commits você tem, mostra a lista de todos os commits feitos);
---
### `git cat NomeDoArquivo` - pegar um arquivo e mostrar o que tem dentro dele, sem precisar abrir ele;
---
### `git clone LinkDoRepositório` - clonar um repositório diretamente do GitHub;
---
### `git add .` - adicionar os arquivos para a stage area;
---
### `git commit -m "NomeDoCommit"` - salvar os arquivos no repositório local;
---
### `git restore .` - remover o commit da stage area (voltar o commit);
---
### `git diff CodigoDoCommitX CodigoDoCommitY` - diferenciar dois commits (verificar o que há de diferente);
---
### `git push` - enviar os arquivos para o GitHub (salvar os arquivos no repositório remoto);
---
### `git pull` - realizar o download das alterações no repositório local (significa basicamente dois comandos, git fetch e git merge);
---
### `git pull --rebase` -- deixar o histórico limpo;
---
### `git fetch` - enviar os arquivos do repositório remoto, para o repositório local;
---
### `git merge` - enviar os arquivos do repositório local, para o local;
---
### `git merge NomeDaBranch` - juntar duas branchs;
---
### `git stash` - enviar os arquivos do local, para o stash;
---
### `git stash apply stash{0}` - enviar os arquivos da stash, para o local;
---
### `git stash list` - listar os arquivos que estão na stash;
---
### `git tag -a v1.0 -m "Mensagem"` - adicionar uma tag para marcar o próximo commit;
---
### `git checkout -b NomeDaBranch` - criar uma nova branch;
---
### `git checkout NomeDaBranch` - alterar de branch;
---
### `git branch -d NomeDaBranch` - deletar uma branch;
---
### `git cherry-pick HashCommit` - pegar o commit identificado pelo hash e aplicá-lo na branch atual onde você está;
---
## Passos para fazer um pull request
### 1 - Abrir o repositório;
### 2 - Ir na aba Pull Request;
### 3 - Clicar em New Pull Request;
### 4 - Selecionar a Branch;
### 5 - Clicar em Create Pull Request;
### 6 - Fazer um Merge;
---
> [!NOTE]
> Não é possível fazer os arquivos voltarem do repositório local para a stage area, pois eles já foram salvos.</br></br>
> Stash normalmente é usado quando ocorre conflitos entre os arquivos.</br></br>
> Head é o último commit.