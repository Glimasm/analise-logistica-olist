# 📊 Business Case: O que realmente influencia a satisfação dos clientes?

## 🎯 Business Question

Uma plataforma de marketplace precisa decidir onde investir seus recursos para aumentar a satisfação dos clientes.

**Vale mais a pena reduzir o tempo de entrega ou diminuir o custo do frete?**

Este projeto busca responder essa pergunta utilizando dados reais da Olist por meio de Análise Exploratória de Dados (EDA), estatística e visualização.

---

# 📌 Executive Summary

## Problema

A experiência do cliente pode ser impactada tanto pelo valor pago no frete quanto pelo tempo necessário para receber o pedido. Como recursos são limitados, a empresa precisa identificar qual fator gera maior impacto na satisfação.

## Principais achados

- O tempo de entrega apresentou associação mais forte com a nota atribuída pelos clientes do que o preço do frete.
    
- Embora fretes mais caros também apresentem avaliações inferiores, essas faixas concentram maior proporção de entregas demoradas.
    
- Os resultados sugerem que a experiência logística exerce maior influência sobre a satisfação do cliente do que reduções isoladas no custo do frete.
    

## Recomendação

Priorizar investimentos na eficiência logística, reduzindo o tempo médio de entrega e monitorando continuamente indicadores de prazo. Reduções isoladas no preço do frete tendem a produzir impacto mais limitado na satisfação dos clientes.

---

# 🛠️ Stack Utilizada

- **Python**
    
- **Pandas**
    
- **Matplotlib**
    
- **Seaborn**
    
- **Jupyter Notebook**
    
- **Power BI**
    

Dataset:

- **Brazilian E-Commerce Public Dataset by Olist (Kaggle)**
    

---

# 📁 Estrutura do Repositório

```text
olist-business-analysis/

├── data/
│   └── olist_customers_dataset.csv
│   └── olist_order_items_dataset.csv
│   └── olist_order_reviews_dataset.csv
│   └── olist_orders_dataset.csv
│
├── notebooks/
│   └── tempo_vs_frete.ipynb
│
├── images/
│   ├── A nota média diminui à medida que o custo do frete aumenta.png
│   ├── Fretes mais caros não estão entregando mais rapidamente.png
│   └── Quanto maior o tempo de entrega.png
│
├── powerbi/
│   └── dashboard.pbix
│
└── README.md
```

---

# 🔎 Principais Evidências

## 1. O tempo de entrega apresenta forte associação com a satisfação dos clientes.

Correlação de Pearson:

- **r = -0,334**
    
- **p < 0,001**
    

Quanto maior o tempo de entrega, menor tende a ser a nota atribuída pelos clientes.

---

## 2. Fretes mais caros também recebem avaliações inferiores.

Observou-se redução gradual da nota média conforme aumenta o custo do frete.

Entretanto, a magnitude desse efeito foi significativamente menor do que aquela observada para o tempo de entrega.

---

## 3. Fretes mais caros concentram entregas mais demoradas.

Ao analisar conjuntamente custo do frete e prazo de entrega, verificou-se que as faixas de maior valor apresentam maior proporção de entregas longas.

Esse comportamento oferece uma possível explicação para as avaliações inferiores observadas nesses grupos.

---

# 💡 Conclusão

Os resultados indicam que **investimentos voltados à eficiência logística tendem a produzir maior impacto na satisfação dos clientes do que reduções isoladas no custo do frete.**

---

# 📚 Artigo Completo

Este projeto faz parte da série:

**Investigando a Olist: decisões estratégicas orientadas por dados**

**Parte 1**

> O que realmente influencia a satisfação dos clientes: tempo de entrega ou preço do frete?

---

# 🚀 Próximas análises

Esta é a primeira parte da série.

Os próximos estudos responderão às seguintes perguntas de negócio:

- Quais vendedores devem ser desenvolvidos ou descredenciados?
    
- Em quais estados vale investir para expandir a operação?
    
- O que realmente explica os cancelamentos dos pedidos?
