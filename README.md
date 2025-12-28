# Segmentação de Clientes com K-Means 🛒👥

Este projeto foca na análise de comportamento de clientes de um e-commerce multinacional. Utilizei técnicas de **Aprendizado Não Supervisionado** para agrupar mais de 4.000 clientes em perfis distintos, permitindo estratégias de marketing mais direcionadas.

### 🚀 Como visualizar a análise
O estudo completo, incluindo a limpeza dos dados e a criação dos clusters, está disponível abaixo:

🔗 **[Abrir análise no Google Colab](https://colab.research.google.com/github/gesiele-vaz/clusterizacao-clientes-ecommerce/blob/main/segmentacao_clientes_ecommerce.ipynb)**

---

## 🛠️ Etapas do Projeto:

### 1. Tratamento de Big Data
* Processamento de um dataset com mais de **540 mil transações**.
* Limpeza de dados: remoção de valores nulos e duplicados.
* Engenharia de variáveis para focar em métricas de identificação e preço unitário.

### 2. Modelagem com Machine Learning (K-Means)
* Aplicação do algoritmo **K-Means** para identificar agrupamentos naturais nos dados.
* Uso da métrica **Silhouette Score** para encontrar o número ideal de clusters.
* Identificação de 3 a 4 perfis principais de consumidores.

### 3. Análise de Perfis (Insights)
* **Clientes Fiéis:** Alta frequência e alto gasto.
* **Clientes Inativos:** Baixa frequência e baixo gasto (foco em reengajamento).
* **Clientes de Alto Valor:** Gastam muito em compras sazonais.

## 🧰 Tecnologias Utilizadas
* **Python**
* **Pandas & Numpy** (Tratamento de dados)
* **Scikit-Learn** (Algoritmo K-Means e Silhouette Score)
* **Matplotlib & Seaborn** (Visualização dos clusters)

---
*Projeto realizado para fins de estudo e portfólio.*
