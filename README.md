
# Tabela de produtos 

## Descrição
"Este projeto tem como propósito a realização de testes com consultas básicas e frequentemente utilizadas no dia a dia. 
Para esse fim, foi escolhido um banco de dados simples, com um volume de dados reduzido em comparação aos bancos de dados empresariais."

## Estrutura do Banco de Dados
"O banco de dados em questão apresenta apenas três colunas e um total de 35 registros. As colunas são nomeadas da seguinte forma: 
  - id_produto (chave primária)
  - nome_produto
  - preco_unidade

## Exemplos de Consultas

### Listar todos os produtos com seus preços
```sql
SELECT * FROM tabelaprodutosdesafioaula1;
```
### Encontrar o produto mais caro
```sql
SELECT * FROM tabela_de_produto
ORDER BY preço DESC
LIMIT 1;
```
### Calcular a média dos preços dos produtos
```sql
SELECT AVG(preço) AS media_precos
FROM  tabelaprodutosdesafioaula1;
```
### Análise de vendas 
```sql
-- Calcular total de vendas (3465)
SELECT SUM (preco_unitario) as total_vendas
FROM tabelaprodutosdesafioaula1;

-- Quantidade de produtos vendidos
SELECT COUNT (nome_do_produto) as qtde_vendida
FROM tabelaprodutosdesafioaula1;
```

## Contribuições
Se você deseja contribuir com o banco de dados adicionando novas funcionalidades, correções ou dados, forneça instruções sobre como fazer isso e diretrizes para contribuição.

## Licença
Declare a licença sob a qual o banco de dados está disponível, para que os usuários saibam como podem usar os dados.

## Autora
Brunna Aureliano Gonçalves
