# 🛒 EDA — Brazilian E-Commerce Public Dataset (Olist)

Análise Exploratória de Dados (EDA) do dataset público da Olist, disponível no Kaggle.
O objetivo não é apenas gerar gráficos — mas desenvolver raciocínio analítico, senso de
negócio e capacidade de extrair insights interpretáveis a partir de dados reais de
e-commerce brasileiro.

![Python](https://img.shields.io/badge/Python-3.11+-blue)
![Pandas](https://img.shields.io/badge/Pandas-3.0.1-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-2.4.2-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.8-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-4c72b0)
![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle)

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

## 💡 Principais Insights

- Pedidos entregues no prazo têm nota média **62% maior** que pedidos atrasados (4.14 vs 2.55)
- Estados do Norte têm tempo de entrega **3x maior** que São Paulo (27.8 vs 8.3 dias)
- **90.5%** dos pedidos chegam antes do prazo estimado — estratégia de prazos conservadores
- Novembro/2017 registrou o maior volume de pedidos (7.451) impulsionado pela Black Friday
- Nenhuma variável financeira influencia a nota do cliente — o que importa é o prazo de entrega
- Janeiro concentra o maior número de atrasos — reflexo direto da Black Friday e Natal

---

## 🗂️ Estrutura do Repositório
```
├── data/
│   ├── raw/              ← arquivos originais do Kaggle (não versionados)
│   └── processed/        ← dados após limpeza (não versionados)
├── notebooks/
│   ├── 01_initial_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_descriptive_statistics.ipynb
│   ├── 04_sales_analysis.ipynb
│   ├── 05_satisfaction_analysis.ipynb
│   ├── 06_logistics_analysis.ipynb
│   └── 07_insights.ipynb
├── outputs/              ← gráficos e relatórios exportados
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 🧠 Perguntas de Negócio

### Vendas
- Quais categorias de produto concentram mais receita?
- Há sazonalidade clara nas vendas? Quais eventos explicam os picos?
- Qual o ticket médio por categoria?
- Quais os métodos de pagamento mais usados?
- Quais os dias da semana com mais pedidos?

### Satisfação
- Existe correlação entre tempo de entrega e nota de avaliação?
- Pedidos atrasados têm nota menor?
- Quais categorias concentram mais reclamações?
- Quais estados têm as piores avaliações?
- A nota média melhorou ao longo do tempo?

### Logística
- Quais estados têm maior tempo médio de entrega?
- O prazo estimado está alinhado com o prazo real?
- Quais meses concentram mais atrasos?
- Produtos mais pesados atrasam mais?
- Entregas dentro do mesmo estado são mais rápidas?

---

## 🚀 Como Reproduzir
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/Brazilian-E-Commerce-Public-Dataset.git

# Crie e ative o ambiente virtual
python -m venv .venv
.venv\scripts\activate  # Windows
source .venv/bin/activate  # Linux/Mac

# Instale as dependências
pip install -r requirements.txt
```

---

## 📊 Status

✅ Concluído

---

## 👤 Autor

**Adam Genezine Columbari**
Desenvolvido como projeto de portfólio em Análise e Ciência de Dados.
