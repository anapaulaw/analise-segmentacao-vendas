# analise-segmentacao-vendas
Este projeto realiza uma análise exploratória de vendas, lucratividade, estoque e segmentação de produtos de uma oficina mecânica. O objetivo é gerar insights estratégicos para otimização de estoque, marketing e precificação, utilizando técnicas de ciência de dados.

##  Estrutura do Projeto

- `vendas_filtradas.xlsx` - Base de dados com informações de vendas, produtos, vendedores e estoque.
- Notebooks e scripts em Python com etapas de:
  - Engenharia de dados
  - Análise exploratória
  - Visualização de dados com Plotly e Matplotlib
  - Segmentação de produtos via PCA e K-Means

---

##  Tecnologias Utilizadas

- Python
- Pandas e NumPy
- Matplotlib e Seaborn (visualização)
- Plotly (gráficos interativos)
- Scikit-learn (StandardScaler, PCA, K-Means)
- Excel (para armazenamento da base de dados)

---

##  Etapas da Análise

1. **Engenharia de Dados**
   - Tratamento de dados faltantes e colunas desnecessárias.
   - Conversão de datas e criação de variáveis temporais.
   - Cálculo de lucro por venda.

2. **Análise Exploratória**
   - Estatísticas descritivas e análise de valores nulos.
   - Distribuição de variáveis numéricas.
   - Vendas diárias e mensais, lucro por vendedor e por produto.
   - Top 20 produtos mais vendidos.
   - Estoque total e valor total do estoque.

3. **Ciência de Dados**
   - Normalização das variáveis de interesse.
   - PCA (Análise de Componentes Principais) para redução de dimensionalidade.
   - K-Means para segmentação de produtos em clusters.

