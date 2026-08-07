# Módulo 08 — Econometria II

> Status: ✅ Completo

## Conteúdo
- [`dados_em_painel.ipynb`](dados_em_painel.ipynb) — Pooled OLS, Efeitos Fixos, Efeitos Aleatórios e teste de Hausman (implementado manualmente), retomando o dataset de companhias aéreas do Módulo 07 e acrescentando um segundo estudo de caso clássico (aluguel em cidades universitárias) onde ignorar o painel muda a conclusão
- [`rental_housing.csv`](rental_housing.csv) — dataset usado no segundo estudo de caso (Wooldridge, clássico da literatura de econometria)

## Objetivo
Estender a regressão múltipla para estruturas de dados em painel (mesmas unidades observadas ao longo do tempo), muito comuns em economia e finanças.

## Tópicos abordados
- Estrutura de dados em painel (cross-section + série temporal)
- Modelo Pooled OLS
- Modelo de Efeitos Fixos
- Modelo de Efeitos Aleatórios
- Teste de Hausman (escolha entre efeitos fixos e aleatórios)
- Ponte para séries temporais (ligação com o [Módulo 09](../09_Séries_Temporais))

## Pré-requisitos
[Módulo 07 — Econometria I](../07_Econometria_I)

## Ferramentas
`linearmodels`, `statsmodels`, `pandas`

## Origem do conteúdo
Sílabo baseado na disciplina de Econometria II cursada na graduação, incluindo as notas de aula de dados em painel originalmente trabalhadas no Gretl.
