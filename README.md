# Configurando uma instáncia de Banco de Dados na Azure

## 💻 Configurando uma instância de Banco de Dados na Azure

  1. Navegue até a página Selecionar uma opção de Implantação do SQL.

  2. Em Bancos de dados SQL, deixe Tipo de recurso definido como Banco de dados individual e selecione Criar.

  3. Na guia Noções básicas do formulário Criar Banco de Dados SQL, em Detalhes do projeto, selecione a Assinatura do Azure desejada.

  4. Para Grupo de recursos, selecione Criar, insira o nome do grupo e selecione OK. Caso não existir pode pular.

  5. Para Nome do banco de dados, insira um nome.

  6. Para Servidor, selecione Criar e preencha o formulário Novo servidor com os seguintes valores:

      - Insira um nome ao servidor:

      - Localização: Selecione uma localização na lista suspensa.

      - Método de autenticação: selecione Usar autenticação do Microsoft Entra.

  7. Selecione OK.

  8. Deixe Deseja usar o pool elástico do SQL definido como Não.

  9. Para o Ambiente de carga de trabalho, especifique o Desenvolvimento para este exercício.

  10. Em Computação + armazenamento, selecione Configurar banco de dados.

  11. Este guia de início rápido usa um banco de dados sem servidor. Portanto, mantenha Camada de serviço definida como Uso Geral (computação sem servidor mais econômica) e defina Camada de computação como Sem servidor. Escolha Aplicar.

  12. Em Redundância de armazenamento de backup, escolha uma opção de redundância para a conta de armazenamento em que os seus backups serão salvos. Para saber mais, confira Redundância de armazenamento de backup.

  13. Selecione Examinar + criar.

  14. Na página Examinar + criar, após examinar, selecione Criar.
