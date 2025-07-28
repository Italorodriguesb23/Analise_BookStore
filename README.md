# 📚 Análise de Dados de uma Loja de Livros

Este projeto consiste em uma análise completa dos dados de uma loja virtual de livros. Os dados foram obtidos por meio de **web scraping** e processados utilizando ferramentas de análise de dados e visualização.

## 🔧 Tecnologias Utilizadas

- **Python** (Pandas, BeautifulSoup, Requests, Seaborn, Matplotlib)
- **SQL** (MySQL)
- **Power BI** (Dashboard interativo)
- **Jupyter Notebook**

## 🧩 Etapas do Projeto

1. **Coleta de Dados**  
   Utilizei web scraping no site [Books to Scrape](https://books.toscrape.com) para coletar informações de livros, como:
   - Título
   - Preço
   - Avaliação (1 a 5)
   - Disponibilidade
   - Categoria
   - Descrição
   - Preço com e sem imposto
   - Quantidade disponível
   - UPC
   - Link do produto

2. **Limpeza e Tratamento**  
   - Remoção de valores nulos e correção de categorias inconsistentes.
   - Conversão de preços e separação dos dados em colunas apropriadas.
   - Remoção de acentos e padronização de nomes de colunas.

3. **Análise Exploratória**  
   Foram gerados gráficos em Python com **Seaborn** e **Matplotlib**, como:
   - Quantidade de livros por categoria
   - Distribuição de preços
   - Boxplot por categoria
   - Avaliações e disponibilidade

4. **Consultas SQL**  
   Foram criadas diversas consultas para analisar os dados, como:
   - Valor total do estoque
   - Livro mais caro por categoria
   - Preço médio por categoria
   - Livros abaixo da média de preço geral
   - Quantidade de livros por avaliação

5. **Dashboard no Power BI**  
   Criação de visualizações interativas para análise de:
   - Média de preços por categoria
   - Quantidade de livros disponíves
   - Média de preços por avaliação
   - Tabela com titulo, categoria, estoque e preço



