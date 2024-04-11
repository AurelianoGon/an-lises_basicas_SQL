SELECT * FROM tabelaprodutosdesafioaula1;

-- Encontrar produtos mais caros (150)
SELECT * from tabelaprodutosdesafioaula1
ORDER BY preco_unitario DESC
LIMIT 1;

-- Produto mais barato (70,75)
SELECT * FROM tabelaprodutosdesafioaula1
ORDER BY preco_unitario 
LIMIT 1;

-- Media dos produtos (99)
SELECT AVG (preco_unitario) as media_preco
from tabelaprodutosdesafioaula1;

-- Média de um produto específico(150)
SELECT AVG (preco_unitario) as media_categoria_A
from tabelaprodutosdesafioaula1
WHERE nome_do_produto = 'Produto A';

-- Mínimo do Banco de dados (70.75)
SELECT MIN (preco_unitario) as minimo_preco
from tabelaprodutosdesafioaula1;

-- Mínimo da categoria A (150)
SELECT MIN (preco_unitario) as minimo_categoria_A
from tabelaprodutosdesafioaula1
where nome_do_produto = 'Produto A';

-- Listar produtos com preços acima de um determinado valor
SELECT * from tabelaprodutosdesafioaula1
where preco_unitario > 90;

-- Contar o numero total de produtos (35)
SELECT COUNT (*) as total_produto
from tabelaprodutosdesafioaula1;

-- Encontrar produtos com nomes semelhantes usando correspondência parcial
SELECT * from tabelaprodutosdesafioaula1
WHERE nome_do_produto LIKE '% Produto I%';

-- Calcular total de vendas (3465)
SELECT SUM (preco_unitario) as total_vendas
from tabelaprodutosdesafioaula1;

-- Quantidade de produtos vendidos
SELECT COUNT (nome_do_produto) as qtde_vendida
FROM tabelaprodutosdesafioaula1;

