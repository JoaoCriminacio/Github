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
### `git reset` - remover o commit da stage area (voltar o commit);
---
### `git diff CodigoDoCommitX CodigoDoCommitY` - diferenciar dois commits (verificar o que há de diferente);
---
### `git push` - enviar os arquivos para o GitHub (salvar os arquivos no repositório remoto);
---
### `git pull` - realizar o download das alterações no repositório local (significa basicamente dois comandos, git fetch e git merge);
---
### `git fetch` - enviar os arquivos do repositório remoto, para o repositório local;
---
### `git merge` - enviar os arquivos do repositório local, para o local;
---
> [!NOTE]
> Não é possível fazer os arquivos voltarem do repositório local para a stage area, pois eles já foram salvos.
