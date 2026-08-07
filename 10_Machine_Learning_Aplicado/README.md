# Módulo 10 — Machine Learning Aplicado

> Status: ✅ Completo

## Objetivo
Módulo de aplicações práticas de machine learning sobre dados, como extensão natural depois de estatística e econometria — mais experimental e exploratório que os módulos anteriores.

## Pré-requisitos
[Módulo 09 — Séries Temporais](../09_Séries_Temporais)

## Ferramentas
`scikit-learn`, `keras`, `pandas`, `arch`, `yfinance`

## Projetos deste módulo
- [`clusterizacao_volatilidade.ipynb`](clusterizacao_volatilidade.ipynb) — K-Means (não-supervisionado) identifica regimes de volatilidade em 4 mercados (Ibovespa, S&P 500, Nasdaq, Euro Stoxx 50) com dados reais e ao vivo, sem nenhum rótulo de data — e isola sozinho a crise da COVID-19 como regime distinto; compara com a volatilidade condicional de um GARCH(1,1) (correlação de 0,97)
- [`ml_loterias/`](ml_loterias) — rede neural recorrente para explorar padrões em sorteios da Lotofácil (exercício educacional, sem pretensão de prever resultados de loteria)
