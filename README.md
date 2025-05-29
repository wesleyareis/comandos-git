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


```json
[
  {
    "title": "Verificação de Estrutura antes de Criar Arquivos/Pastas",
    "description": "Antes de criar novas pastas ou arquivos, sempre verificar a estrutura atual do projeto para evitar duplicações e manter a organização modular. Conferir se já existe um componente, serviço ou módulo com a mesma função. Utilizar nomes claros e coerentes com a arquitetura por domínios/módulos. Criar pastas apenas quando necessário e manter o padrão de nomeação existente (ex: PascalCase para componentes, camelCase para utilitários).",
    "type": "Always"
  },
  {
    "title": "Arquitetura Modular",
    "description": "Organizar o projeto por domínios e responsabilidades. Separar lógica de negócio da interface. Evitar arquivos grandes ou com múltiplas responsabilidades.",
    "type": "Always"
  },
  {
    "title": "Validação de Dados",
    "description": "Utilizar bibliotecas de validação tipadas (como Zod ou Joi) para validar dados de entrada e saída. Mensagens de erro devem ser claras, exibidas próximas ao campo ou contexto onde ocorreram.",
    "type": "Always"
  },
  {
    "title": "Tratamento de Erros e Feedback ao Usuário",
    "description": "Exibir mensagens visuais de erro ou sucesso sempre que necessário. Nunca deixar o usuário sem retorno após ações críticas.",
    "type": "Always"
  },
  {
    "title": "Reutilização e Padronização de Componentes",
    "description": "Reutilizar componentes padronizados. Nomear arquivos com clareza e consistência, evitando duplicação de estilos ou lógicas.",
    "type": "Always"
  },
  {
    "title": "Lazy Loading de Módulos ou Páginas",
    "description": "Carregar módulos ou páginas sob demanda sempre que possível, para reduzir o tempo de carregamento inicial.",
    "type": "Always"
  },
  {
    "title": "Indicadores de Carregamento",
    "description": "Exibir spinners ou skeletons para indicar carregamentos. Nunca deixar a interface congelada ou sem resposta.",
    "type": "Always"
  },
  {
    "title": "Acessibilidade (a11y) Básica",
    "description": "Garantir o uso de elementos semânticos, labels, contraste adequado e navegação por teclado.",
    "type": "Always"
  },
  {
    "title": "Responsividade Mínima",
    "description": "Garantir que telas importantes funcionem bem em telas pequenas, mesmo que o foco seja desktop.",
    "type": "Always"
  },
  {
    "title": "Documentação no Código",
    "description": "Comentar funções reutilizáveis com JSDoc ou equivalente, explicando entradas, saídas e responsabilidade.",
    "type": "Always"
  },
  {
    "title": "Centralização de Configurações",
    "description": "Utilizar arquivos de configuração centralizados (ex: config/db.ts, config/theme.ts) para valores e opções reutilizáveis.",
    "type": "Always"
  },
  {
    "title": "Mensagens e Interface em Português do Brasil",
    "description": "Toda interface e mensagens devem estar em português do Brasil, inclusive respostas do assistente.",
    "type": "Always"
  },
  {
    "title": "Planejamento Prévio de Banco de Dados",
    "description": "Antes de iniciar o frontend, modelar e revisar o banco de dados, suas relações e regras. Isso evita retrabalho e garante consistência.",
    "type": "Always"
  },
  {
    "title": "Versionamento do Banco de Dados",
    "description": "Utilizar migrações para versionar alterações no banco, evitando alterações manuais sem histórico.",
    "type": "Always"
  }
]
