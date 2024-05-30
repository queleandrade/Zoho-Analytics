# Query - Modelando Dados

## Introdução às Queries

Neste estudo, vamos explorar como utilizar queries SQL no Zoho Analytics para realizar consultas e modelar dados de maneira eficiente.

### Exemplos de Queries

Aqui estão alguns exemplos básicos de queries que você pode usar para consultar seus dados:

1. **Selecionar todas as vendas:**
   ```sql
   SELECT * FROM tabela_de_vendas;

2. **Selecionar todas as vendas de uma região específica:**
   ```sql
   SELECT * FROM tabela_de_vendas
   WHERE Region = 'Central';

3. **Selecionar todas as vendas de um produto específico:**
   ```sql
   SELECT * FROM tabela_de_vendas
   WHERE Product = 'Fruits and Vegetables';

4. **Selecionar todas as vendas com lucro acima de $500:**
   ```sql
   SELECT * FROM tabela_de_vendas
   WHERE Profit > 500;


## Passo a Passo para Criar uma Query

Para utilizar consultas de dados no Zoho Analytics, siga os passos abaixo:

1. **Iniciar a Criação de uma Query**
      - Clique em "+ Criar" no painel principal.
      - Selecione "Tabelas de Consultas", conforme mostrado na imagem abaixo:

      <img width="522" alt="query1" src="https://github.com/queleandrade/Zoho-Analytics/assets/75625651/b9082bec-41a9-416c-b5be-bce4b44b644d">

2. **Escrever a Query**

Após o passo acima, uma nova janela será aberta onde você pode escrever suas queries utilizando comandos SQL como SELECT, WHERE, FROM, entre outros.

<img width="955" alt="query2" src="https://github.com/queleandrade/Zoho-Analytics/assets/75625651/2d22c6ed-71c8-4623-9e72-75186584edd8">




