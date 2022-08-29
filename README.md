


### 4 estágios

- 1 Untracked files - Unstage - arquivos não estão versionados
- git add .
- 2 Staging -> pronto para ser comitado
- git commit -m ""
- 3 Arquivo versionado - pós commit
- git log
- 4 Arquivo modificado - arquivo commitado que foi alterado, volta para unstage modified
- git commit -a -m "Commitando arquivo.txt e index.html juntos"

### git log

- opções:
- git log -p => mostra as alterações feitas em cada commit
- git log -p -2 => dos dois últimos commits
- git log --stat => estatísticas de cada commit
- git log --pretty=oneline => info em uma linha
- git log -2 --pretty=oneline 
- git log -2 --pretty=short/medium/full
- git log -2 --pretty=format:"%h - %an, %ar : %s"
- git log --since=2.minutes
- git log --since=20.minutes
- git log --since=2.days

### gitignore

### 
- git restore --staged teste2.txt => para voltar para untracked (to unstage)