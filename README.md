# 📱 Análise de Planos de Telecomunicações — Megaline

Projeto desenvolvido durante o Sprint 04 do bootcamp **TripleTen** de Análise de Dados.

## 📋 Objetivo

Analisar o comportamento de 500 clientes da operadora Megaline em 2018 para identificar qual dos planos pré-pagos (Surf ou Ultimate) gera maior receita, apoiando decisões do departamento comercial sobre orçamento de publicidade.

## 🔍 O que foi feito

- Carregamento e exploração de 5 datasets (usuários, chamadas, mensagens, internet e planos)
- Conversão de colunas de data para o formato datetime
- Arredondamento de duração de chamadas para cima com `numpy.ceil`
- Remoção de duplicatas e verificação de valores ausentes
- Enriquecimento dos dados com colunas de mês e conversão de MB para GB
- Cálculo de receita mensal por cliente com base nas regras de cada plano
- Análise estatística comparativa entre os planos Surf e Ultimate
- Teste de hipóteses para validar diferenças de receita entre os planos

## 🛠️ Ferramentas utilizadas

- Python 3
- Pandas
- NumPy
- SciPy (stats)
- Matplotlib
- Jupyter Notebook

## 📂 Estrutura do projeto

```
sprint04-analise-megaline/
├── README.md
└── notebook.ipynb
```

## ▶️ Como visualizar

👉 [Abrir no Google Colab](https://colab.research.google.com/github/LucasSvieira97/Repository-name-sprint04-analise-megaline/blob/main/notebook.ipynb) 

## 📌 Resultado

Projeto aprovado com análise estatística completa e teste de hipóteses para comparação de receita entre planos de telecomunicações.
