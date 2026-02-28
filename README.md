# 🛒 EDA — Brazilian E-Commerce Public Dataset (Olist)

Repositório dedicado à Análise Exploratória de Dados (EDA) do dataset público da Olist,
disponível no Kaggle. O objetivo não é apenas gerar gráficos — é desenvolver raciocínio
analítico, senso de negócio e capacidade de extrair insights interpretáveis a partir de
dados reais de e-commerce brasileiro.

---

## 📦 Sobre o Dataset

- **Fonte:** [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Período:** 2016 a 2018
- **Volume:** ~100k pedidos | 9 tabelas relacionais
- **Cobertura:** pedidos, produtos, vendedores, clientes, pagamentos, avaliações e geolocalização

---

## 🎯 Objetivos da Análise

- Entender o comportamento de compra dos clientes brasileiros
- Identificar padrões de sazonalidade e picos de demanda
- Analisar drivers de satisfação e insatisfação (reviews)
- Investigar performance por categoria de produto, região e vendedor
- Gerar hipóteses acionáveis como um analista de negócio faria

---

## 🧠 Perguntas que guiam a EDA

- Quais categorias de produto concentram mais receita e mais reclamações?
- Existe correlação entre tempo de entrega e nota de avaliação?
- Quais estados têm os clientes mais valiosos (LTV implícito)?
- Há sazonalidade clara nas vendas? Quais eventos explicam os picos?
- O prazo estimado de entrega está alinhado com o prazo real?

---

## 🗂️ Estrutura do Repositório
```
├── data/               # Dados brutos (não versionados)
├── notebooks/          # Notebooks Jupyter com a EDA
│   ├── 01_exploracao_inicial.ipynb
│   ├── 02_qualidade_e_limpeza.ipynb
│   ├── 03_analise_pedidos_e_receita.ipynb
│   ├── 04_satisfacao_e_reviews.ipynb
│   └── 05_insights_e_storytelling.ipynb
├── src/                # Funções auxiliares e scripts
├── outputs/            # Gráficos e relatórios exportados
└── README.md
```

---

## 🛠️ Tecnologias Utilizadas

- Python 3.12.4
- Pandas / NumPy
- Matplotlib / Seaborn / Plotly
- Jupyter Notebook

---

## 📊 Status

🚧 Em desenvolvimento — EDA progressiva do zero ao avançado.

---

## 👤 Autor

Adam Genezine Columbari
