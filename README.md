Configura o email do git
```
git config --global user.email ""
```
Configura o nome do git
```
git config --global user.name ""
```

Cria um atalho para alguns comandos
```
git config --global alias.cm commit
```

Mostra o manual do comando
```
git (comando) --help
```

Inicializa o repositorio com as configurações do git. Gera arquivo oculto .git com essas configurações
```
git init
```

Verifica a situação dos arquivos do branch local
```
git status
```

Adiciona arquivo para ser monitorado
```
git add "nome_arquivo"
```

Adiciona todos os arquivos do repositório para o monitoramento
```
git add *
```

Adiciona todos os arquivos do diretório atual para o monitoramento
```
git add .
```

retira o arquivo do monitoramento
```
git rm --cached "nome_arquivo"
```
```
git rm --cached *
```

Realiza a submissao dos arquivos que estão em monitoramento. -m ==> Mensagem
```
git commit -m "mensagem do commit"
```

Mostra o ħistorico de commit's
```
git log
```

Vê o historico e as alterações realizadas
```
git log -p 
```

Vê o historico e as alterações realizadas do commit na posição -1
```
git log -p -1
```

Vê as alterações realizadas no commit respectivo ao hash
```
git show "codigo_hash"
```

Apaga todas as alterações feitas e volta pra ultima versão
```
git checkout -- "nome_arquivo"
```

Vincula um diretorio remoto ao seu diretorio local, pode-se add mais de um remoto
```
git remote add origin "nome_enderço_remoto"
```

Mostra os diretorios remotos vinculados aos projeto
```
git remote
```

Remove o diretorio remoto 
```
git remote remove "nome_repositorio"
```

Pasta colocado pra ignorar algum arquivo
```
.gitignore
```

Puxa toda informação do diretório e mescla com o local
```
git pull origin master
```

Baixa toda as alterações mas nao mescla com o local
```
git fetch origin master:master
```

Mostra todas as brach's
```
git brach
```

Cria um novo brach
```
git brach "nome_brach"
```

Movimenta entra os brach	
```
git checkout "nome_brach"
```

Junta brach
```
git merge "brach_que_ira_juntar" "brach_atual"
```

Desfaz somento o commit que esta indicando
```
git revert "hash"
```

Volta para o commit desejado
```
git reset "hash"
```
