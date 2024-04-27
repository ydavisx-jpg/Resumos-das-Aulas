## Comandos mais utilizados

### Git Aliases: Adicionando apelidos para os comandos do Git

Adiciona um repositório remoto ao seu projeto Git:
```bash
$ git remote add origin [link do github]
```  
Envia alterações do branch main local para o branch main remoto e configura o branch main local para rastrear o branch main remoto:
```bash
$ git push -u origin main
```  
Envia alterações do branch main local para o branch main remoto:
```bash
$ git push origin main
```  
Comando que puxa as configuraçoes remoto para o local :
```bash
$ git pull origin main
```
Comando para ver a situaçao que se econtra em andamento:
```bash
$ git status
```
Comando que adiciona tudo de uma vez e que adiciona uma:
```bash
$ git add .
$ git add "Nome do Arquivo"
```
Comando para ver as commit:
```bash
$ git log
```
Comando para restaurar:
```bash
$ git restore "arquivo"
```
Comando para renomear a ultima commit:
```bash
$ git commit --amend -m "Nova mensagem de commit"
$ git commit -ammend [vai levar p arquivo e vai ter que mudar manualmente]
```
comando para trazer somente uma branch e comando que mostra quantas branch tem:
```bash
$ git clone [URL DO GITHUB] --branch t "nome da branch" --single-branch
$ git branch
```
Comandos para desfazer uma mudança na area de preparaçao:
```bash
$ git reset --soft [isso removerá o arquivo da área de preparação, mas manterá o arquivo no diretório de trabalho.]
$ git reset --mixed [Isso removerá as alterações do arquivo da área de preparação e do diretório de trabalho.]
$ git reset --hard [Isso restaurará o diretório de trabalho e a área de preparação para o estado do commit anterior.]
```
## Comandos de branch
Criar nova branch:
```bash
$ git checkout -B "nova branch secundaria"
```
Apagar a branch:
```bash
$ git branch -d [nome da branch]
```
Mostra as ultimas commit feita em cada branch:
```bash
$ git branch -v
```
Volta para branch principal:
```bash
$ git checkout main
```
Mescla as branch:
```bash
$ git merge [nome da nova branch]
```
## Comandos de visualizar diferenças entre remoto e local
Puxa os arquivos diferentes:
```bash
$ git fetch origin main 
```
Mostra as diferenças entre o local e remoto:
```bash
$ git diff maion origin/main 
```
Mescla e traz os arquivos para o local:
```bash
$ git diff maion origin/main 
```
Volta o arquivo que eu apaguei:
```bash
$ git stash
```
Lista as mudanças:
```bash
$ git stash list
```
