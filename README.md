# comandos-git
## ➡️ Principais comandos que são utilizados no Git (TESTE)

| **id** | **Descrição** | **Comandos** | **Opções** |
| :-----:| :------------ | :----------- | :--------- |
| 1. | *Inicialize* um novo repositório Git | `git init` | - |
| 2. | Liste todos os arquivos *novos ou modificados* | `git status` | - |
| 3. | Add ou preparar o código/arquivos para serem commitados | `git add` | .file  |
| 4. | Descartar alterações do código na área de trabalho | `git restore` | .file  |
| 5. | Commita o código/arquivos no histórico das versões | `git commit -m` | "mensagem-da-alteração" |
| 6. | Mostra os últimos commit, log de alterações | `git log` | - |
| 7. | Permite voltar versões do histórico da branch | `git checkout` | [sua-hash] |
| 8. | Voltar para última versão ou volta para branch principal | `git checkout master` | [nome-da-branch] |
| 9. | Cria uma nova branch a partir do histórico da branch atual que estamos | `git checkout -b` | [new_branch] |
| 10. | Cria uma nova branch a partir do histórico da branch atual que estamos | `git branch` | [new_branch] |
| 11. | Mostra todas as branches que estão sendo trabalhadas localmente | `git branch` | - |
| 12. | Renomeia o nome da branch | `git branch -M` | [new_branch] |
| 13. | Remove uma branch | `git branch -d` | [nome-da-branch] |
| 14. | Mescla as linhas de desenvolvimento. De modo geral, esse comando é usado para combinar alterações feitas em dois branches distinto | `git merge` | [nome-da-branch] |
| 15. | Mostra as diferenças do código alterado | `git` | - |
| 16. | Mostra as diferenças do código alterado | `git diff` | - |

## ➡️ Principais comandos utilizados repositório remoto **Github**

| **id** | **Descrição** | **Comandos** | **Opções** |
| :-----:| :------------ | :----------- | :--------- |
| 1. | Preparar o repositório para envio remoto **Github** | `git remote add origin` | [url-repositorio-remoto] |
| 2. | Subir/manda alterações do código local para repositório remoto (Github) ou atualiza o repositório remoto com todos os commits feitos localmente em um branch | `git push origin` | [nome-da-branch] |
| 3. | Atualiza o novo histórico local de acordo com o histórico salvo lá no repositório remoto | `git fetch` | - |
| 4. | Pega as alterações do repositório remoto, e joga para nossa máquina local ou atualiza a linha de desenvolvimento local com atualizações do equivalente remoto | `git pull origin` | [nome-da-branch] |

- git clone</br>

<hr>
<details>
<summary>NOTAS:</summary>
➡️ Algumas observações importantes:  

1. O comando `git add` podemos usar <font color="magenta">nome-do-arquivo</font> ou simplesmente usar um ponto <font color="magenta">"."</font> para adicionar todos os arquivos não trackeados;  

1. O comando `git restore` podemos usar <font color="magenta">nome-do-arquivo</font> ou simplesmente usar um <font color="magenta">"."</font> para restaurar todos os arquivos que foram adicionados indevidamente;  

>**Detalhe:** Se você tiver qualquer modificação pendente que ainda não foi "comitada". Faça um `git add` e um `git commit -m "sua msg"` antes de realizar um `git checkout` para retornar uma versão.

>**Lembrando:** Se estiver qualquer modificação pendente e querer voltar versão o `Git` não deixará ...

>`git merge [branch]` temos que estar na __branch-principal__ para poder mesclar a **branch-develop**

</details>
<hr>

- [x] #739
- [ ] #Atualizar este projeto amanhã

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
