# Estado dos arquivos no Git

![](file_lifecycle.png)

| Estado | Descrição |
|-------------|------------------------------------------------------------------------|
| Untracked | É o arquivo criado, mas não rastreado pelo git (não passou pelo git add).|
| Unmodified | É o arquivo que passou pelo git add e commit, mas que apois isso não foi modificado.|
| Modified | É o arquivo que já havia passado pelo commit e sofreu uma alteração.|
| Staged | É o arquivo que passou pelo git add e está pronto para o commit.|

# Comandos Git para windows no prompt:

### Baixa o Git na máquina ou atualizar:
```winget install --id Git.Git -e --source winget```


## - Configurando o Git:

### Cria o nome:
```git config –global user.name <nome>```
### Coloca o e-mail:
```git config –global user.email <email>```
### Verifica lista de configurações do Git:
```git config --list```
### Retorna a versão do Git se estiver instalado
```git --version```

## - Principais comandos do Git:

### Cria um repositório local
```git init```
### Clona um repositório remoto para o local:
```git clone```
### Prepara o arquivo (staging area) para o commit:
```git add .```
### Envia o arquivo (staged) para o repositório local:
```git commit -m <mensagem>```
### Exibe o estado atual do repositório:
```git status```
### Mostra o histórico de commits:
```git log```
### Lista todas as branchs locais e destaca a atual:
```git branch```
### Cria uma branch:
```git branch <nome_branch>```
### Altera para uma branche específica:
```git checkout <nome_branch>```
### Combina as alterações de uma branch com a atual:
```git merge <nome_branch>```
### Atualiza repositório local com o remoto:
```git pull```
### Envia os commits para o repositório remoto:
```git push <nome_repositório_remoto> <nome_branch>```
### Lista os repositórios remotos configurados:
```git remote -v```
### Recupera as últimas alterações do repositório remoto, sem merge automático:
```git fetch```
### Desfaz alterações de arquivo específico, removendo do índice:
```git reset <nome_arquivo>```
### Remove arquivo de um repositório e inclui no próximo commit:
```git rm <nome_arquivo>```
### Mostra as diferenças entre as alterações ainda não adicionadas nos índices:
```git diff```
### Adiciona repositório remoto com um nome específico no repositório local:
```git remote add <nome_repositório_remoto> <URL>```
### Envia alterações locais para o repositório remoto:
```git push add origin main```






