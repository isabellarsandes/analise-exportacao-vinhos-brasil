# Brazil Wine Export Analytics

Projeto de análise de dados sobre as exportações brasileiras de vinho, com foco em identificar tendências de mercado, países de destino mais relevantes e insights estratégicos para expansão internacional.

---

## Visão Geral

Este projeto analisa dados históricos de exportação de vinhos brasileiros com o objetivo de entender o comportamento da demanda internacional e apoiar decisões de negócio orientadas por dados.

A proposta simula o trabalho de uma pessoa analista de dados atuando no suporte à estratégia comercial de uma empresa brasileira do setor vitivinícola com atuação no mercado externo.

---

## Problema de Negócio

Empresas exportadoras precisam entender quais mercados apresentam maior relevância, como o desempenho evolui ao longo do tempo e onde existem oportunidades de crescimento.

Neste contexto, a análise busca responder perguntas como:

- Quais países mais importam vinho brasileiro?
- Como o volume exportado evoluiu ao longo do tempo?
- Existe concentração em poucos mercados?
- Quais padrões podem apoiar decisões estratégicas de expansão?

---

## Objetivo

Os principais objetivos deste projeto são:

- identificar os principais países de destino das exportações
- analisar a evolução do volume exportado ao longo do tempo
- avaliar o valor exportado em dólares
- explorar padrões e concentração de mercado
- gerar insights que apoiem decisões estratégicas de negócio

---

## Base de Dados

A base utilizada neste projeto foi extraída da **Embrapa Vitibrasil**, referência em dados da cadeia vitivinícola brasileira.

**Fonte:**  
http://vitibrasil.cnpuv.embrapa.br/index.php?opcao=opt_01

A base disponibiliza informações sobre:

- produção
- processamento
- comercialização
- importação
- exportação

Neste projeto, o foco está especificamente nos dados de **exportação de vinhos brasileiros**.

---

## Ferramentas e Tecnologias

Este projeto foi desenvolvido com:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Etapas da Análise

As principais etapas realizadas foram:

1. coleta e entendimento da base de dados
2. limpeza e padronização das informações
3. análise exploratória dos dados
4. criação de visualizações para identificar padrões
5. interpretação dos resultados com foco em negócio

---

## Principais Análises Realizadas

- evolução do volume exportado ao longo do tempo
- identificação dos principais países importadores
- análise da concentração das exportações
- avaliação de padrões de crescimento e oscilação do mercado

---

## Principais Insights

Alguns dos principais insights identificados foram:

- as exportações brasileiras de vinho apresentam concentração em um número reduzido de mercados
- determinados países demonstram maior recorrência e relevância ao longo do período analisado
- o desempenho das exportações varia ao longo do tempo, indicando oportunidades e riscos para a estratégia comercial internacional

---

## Estrutura do Projeto

brazil-wine-export-analytics/
├── data/
│   └── processed/   # bases tratadas e modeladas para análise
├── docs/
│   ├── brazil_wine_exports_analysis_2009_2023.pdf
│   └── project_description.pdf
├── notebooks/
│   └── 01_eda.ipynb
├── .gitignore
└── README.md
