## Vendas Table SQL Script

Este repositório contém um script SQL para criação e manipulação da tabela `vendas` no Oracle SQL Developer. O objetivo é gerenciar informações sobre vendas realizadas, incluindo dados do cliente, tipo de venda e valor.

### Estrutura da Tabela

A tabela `vendas` é definida com as seguintes colunas:

- **numero_venda** (INTEGER): Número da venda realizada (chave primária).
- **codigo_cliente** (INTEGER): Código do cliente.
- **nome_cliente** (VARCHAR(10)): Nome do cliente.
- **tipo_cliente** (VARCHAR(10)): Tipo do cliente.
- **tipo_venda** (VARCHAR(10)): Tipo da venda.
- **valor_venda** (NUMERIC(7,2)): Valor da venda (deve ser maior que zero).
- **situacao_venda** (VARCHAR(15)): Situação da venda.

### Comentários

A tabela e suas colunas possuem comentários que descrevem cada campo, facilitando o entendimento da estrutura de dados.

### Consultas SQL

O script inclui várias consultas para manipulação e extração de dados da tabela `vendas`, incluindo:

- **Seleção de dados**: Exemplos de consultas `SELECT` para recuperar informações específicas.
- **Filtragem**: Uso de cláusulas `WHERE` para filtrar resultados com base em condições específicas.
- **Funções de string**: Demonstrações de funções para manipulação de texto.
- **Inserção e atualização**: Exemplos de comandos `INSERT` e `UPDATE` para adicionar e modificar dados na tabela.
- **Agregação**: Uso de funções de agregação como `COUNT`, `AVG` e `SUM`.

### Exemplo de Uso

Para criar a tabela e realizar as operações, você pode executar o script SQL completo em seu ambiente Oracle SQL Developer. As consultas podem ser adaptadas conforme a necessidade do seu projeto.

### Requisitos

- Oracle SQL Developer instalado.
- Acesso a um banco de dados Oracle onde você possa criar a tabela e executar consultas.
