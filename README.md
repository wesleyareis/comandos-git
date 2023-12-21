# comandos-git
**Principais comandos que são utilizados no Git.**

The background color is `#0969DA` for light mode and `#000000` for dark mode.

<details>
<summary>1. git init</summary>
➡️ Inicializar novo projeto no Git:

```bash
git init
```
</details>

<details>
<summary>2. git status</summary>
➡️ Verifica o estado da ramificação:

```bash
git status
```
</details>

#### ➡️ Add ou preparar o código/arquivos para serem commitados:
```bash
git add <file>
```
### Descartar alterações do código na área de trabalho:
```bash
git restore <file>
```

### Commita o código/arquivos no histórico das versões:
```bash
git commit -m "<sua mensagem de alteração feita>"
```

### Mostra os últimos commit, log de alterações:
```bash
git log
```

### Mostra as diferenças do código alterado:
```bash
git diff
```

### Mostra qual a branch que está atualmente:
```bash
git branch
```
### Cria uma nova branch a partir do histórico da branch atual que estamos:
```bash
git checkout -b <nome-da-branch>
```

### Voltar para branch principal:
```bash
git checkout master
```

### Voltar para branch criada:
```bash
git checkout <nome-da-branch>
```

#### Merge de ramificações, mescla as ramificações:
```bash
git merge <nome-da-nova-branch>
```

### Preparar o repositório remoto do código para Github
```bash
git remote add origin <url-repositorio-remoto>
```

### Subir/manda alterações do código local para repositório remoto (Github):
```bash
git push origin <nome-da-branch>
```

### Pega as alterações do repositório remoto, e joga para nossa máquina local:
```bash
git pull origin <nome-da-branch>
```

### Atualiza o novo histórico local de acordo com o histórico salvo lá no repositório remoto:
```bash
git fetch
```

<p>
git init</br>
git status</br>
git add</br>
git commit</br>
git log</br>
git diff</br>
git branch</br>
git branch -b</br>
git checkout</br>
git marge</br>
git log</br>
git push</br>
git pull</br>
git fetch</br>
</p>