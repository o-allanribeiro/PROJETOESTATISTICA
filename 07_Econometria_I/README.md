# Módulo 07 — Econometria I

> Status: ✅ Completo

## Conteúdo
- [`regressao_multipla.ipynb`](regressao_multipla.ipynb) — função de custo Cobb-Douglas (MQO múltiplo) sobre dados reais de companhias aéreas, pressupostos de Gauss-Markov, testes t e F, R² x R² ajustado, variáveis dummy, VIF (multicolinearidade) e teste de Breusch-Pagan (heterocedasticidade)
- [`violacoes_das_hipoteses.ipynb`](violacoes_das_hipoteses.ipynb) — aprofunda cada hipótese de Gauss-Markov: viés de variável omitida (simulação), especificação funcional (teste RESET), multicolinearidade extrema, e um estudo de caso real com dados de mercado ao vivo (Ibovespa x S&P 500) expondo heterocedasticidade condicional (ARCH-LM) — a mesma violação que motiva os modelos GARCH do Módulo 09 — além de autocorrelação (Breusch-Godfrey) e normalidade (Jarque-Bera)
- [`airline_costs.csv`](airline_costs.csv) — dataset usado no primeiro notebook (Christensen & Greene, clássico da literatura de econometria)

## Objetivo
Generalizar a regressão linear simples para múltiplas variáveis explicativas e aprender a validar se um modelo de regressão é confiável. Este módulo reproduz em Python o que originalmente foi feito no Gretl.

## Tópicos abordados
- Modelo de regressão linear múltipla (MQO)
- Pressupostos de Gauss-Markov
- Testes de significância individual (teste t) e conjunta (teste F)
- R² e R² ajustado
- Variáveis dummy
- Diagnóstico básico: multicolinearidade e heterocedasticidade
- Dados de corte transversal (cross-section)

## Pré-requisitos
[Módulo 05 — Correlação e Regressão Linear](../05_Correlação_e_Regressão_Linear), [Módulo 06 — Estatística Econômica e Números-Índices](../06_Estatística_Econômica_e_Números_Índices)

## Ferramentas
`statsmodels`, `pandas`

## Origem do conteúdo
Sílabo baseado na disciplina de Econometria I cursada na graduação, cujos exercícios e listas foram originalmente resolvidos no software Gretl com dados de corte transversal.
