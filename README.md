# Análise de Faturamento de Lojas

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) a partir de informações de vendas de quatro lojas diferentes. Os dados foram obtidos a partir de arquivos CSV hospedados no GitHub.

---

## Dados Utilizados

Os arquivos CSV contêm informações sobre:

- Produto
- Categoria do Produto
- Preço
- Frete
- Data da Compra
- Vendedor
- Local da compra
- Avaliação da compra
- Tipo de pagamento
- Quantidade de parcelas
- Latitude e longitude

Fontes dos dados:

- [`loja_1.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
- [`loja_2.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
- [`loja_3.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
- [`loja_4.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

---

## Análises Realizadas

As principais análises feitas no projeto foram:

### Vendas por Categoria
Contagem de produtos vendidos por categoria, permitindo visualizar quais tipos de produtos são mais populares.

### Média de Avaliação das Lojas
Cálculo da média da avaliação dada pelos clientes para cada loja.

### Produtos Mais e Menos Vendidos
Identificação dos produtos com maior e menor número de vendas.

### Frete Médio por Loja
Cálculo do valor médio de frete cobrado por cada loja.

---

## Tecnologias Utilizadas

- Python 3
- Pandas
- Jupyter Notebook ou Google Colab

---

## Como Executar

1. Instale as dependências:
   ```bash
   pip install pandas
