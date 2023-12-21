# comandos-git
**Principais comandos que são utilizados no Git.**

| Comandos | Descrição |
| :--- | :--- |
| `git status` | Liste todos os arquivos *novos ou modificados* |
| `git diff` | Mostrar diferenças de arquivos que **não foram** preparados |

- [x] #739

The background color is `#0969DA` for light mode and `#000000` for dark mode.

<details>
<summary>1. git init</summary>
➡️ Inicialize um novo repositório Git:

```bash
git init
```
</details>

<details>
<summary>2. git status</summary>

➡️ Use `git status` para listar todos os arquivos novos ou modificados que ainda não foram comitados.

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

### Mostra as branches que estão sendo trabalhadas localmente:
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

#### Mescla as linhas de desenvolvimento. De modo geral, esse comando é usado para combinar alterações feitas em dois branches distinto:
```bash
git merge <nome-da-nova-branch>
```

### Preparar o repositório remoto do código para Github
```bash
git remote add origin <url-repositorio-remoto>
```

### Subir/manda alterações do código local para repositório remoto (Github) ou atualiza o repositório remoto com todos os commits feitos localmente em um branch:
```bash
git push origin <nome-da-branch>
```

### Pega as alterações do repositório remoto, e joga para nossa máquina local ou atualiza a linha de desenvolvimento local com atualizações do equivalente remoto:
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
git clone</br>
</p>