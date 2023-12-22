# comandos-git
## ➡️ Principais comandos que são utilizados no Git

| **id** | **Descrição** | **Comandos** | **Opções** |
| :-----:| :------------ | :----------- | :--------- |
| 1. | *Inicialize* um novo repositório Git | `git init` | - |
| 2. | Liste todos os arquivos *novos ou modificados* | `git status` | - |
| 3. | Add ou preparar o código/arquivos para serem commitados | `git add` | .file  |
| 4. | Descartar alterações do código na área de trabalho | `git restore` | .file  |
| 5. | Commita o código/arquivos no histórico das versões | `git commit -m` | "mensagem-da-alteração" |
| 6. | Mostra os últimos commit, log de alterações | `git log` | - |
| 7. | Permite voltar versões do histórico da branch | `git checkout` | [sua-hash] |
| 8. | Voltar para última versão ou volta para branch principal | `checkout master` | [nome-da-branch] |
| 9. | Cria uma nova branch a partir do histórico da branch atual que estamos | `checkout -b` | [nome-da-branch] |

| `git diff` | Mostrar diferenças de arquivos que **não foram** preparados |



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

- [x] #739
- [ ] #Atualizar este projeto amanhã

<p>
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
<hr>
<details>
<summary>NOTAS:</summary>
➡️ Algumas observações importantes:  

1. O comando `git add` podemos usar <font color="magenta">nome-do-arquivo</font> ou simplesmente usar um ponto <font color="magenta">"."</font> para adicionar todos os arquivos não trackeados;  

1. O comando `git restore` podemos usar <font color="magenta">nome-do-arquivo</font> ou simplesmente usar um <font color="magenta">"."</font> para restaurar todos os arquivos que foram adicionados indevidamente;  

>**Detalhe:** Se você tiver qualquer modificação pendente que ainda não foi "comitada". Faça um `git add` e um `git commit -m "sua msg"` antes de realizar um `git checkout` para retornar uma versão.

</details>
<hr>

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor