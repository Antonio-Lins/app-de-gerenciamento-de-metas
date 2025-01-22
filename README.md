# app de gerenciamento de metas

este é um aplicativo interativo em node.js para gerenciamento de metas pessoais. o projeto permite aos usuários cadastrar, listar, visualizar, editar e excluir metas de forma prática e organizada.

## funcionalidades
- **cadastrar metas**: adicione novas metas ao seu planejamento. 
- **listar metas**: visualize todas as metas cadastradas e marque as concluídas.
- **visualizar metas realizadas**: veja quais metas já foram alcançadas.
- **visualizar metas abertas**: acompanhe as metas que ainda precisam ser concluídas.
- **deletar metas**: remova metas indesejadas.

## estrutura do projeto
- o arquivo `index.js` contém a lógica principal do programa.
- os dados das metas são armazenados no arquivo `metas.json` em formato json.
- utiliza o pacote [inquirer](https://www.npmjs.com/package/inquirer) para interatividade no terminal.

## como executar
1. instale o node.js e o npm no seu sistema.
2. no terminal, navegue até o diretório do projeto.
3. instale as dependências com:
   ```bash
   npm install
