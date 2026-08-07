# Módulo 09 — Séries Temporais

> Status: ✅ Completo

## Objetivo
Estudar dados observados ao longo do tempo (preços, índices, taxas) e construir modelos para descrevê-los e prever seus próximos valores.

## Tópicos abordados
- Estacionariedade e diferenciação
- Autocorrelação (ACF) e autocorrelação parcial (PACF)
- Modelos ARIMA e SARIMA
- Vetor Autorregressivo (VAR) e causalidade de Granger
- Avaliação de previsão (RMSE, MAE, MAPE)

## Pré-requisitos
[Módulo 08 — Econometria II](../08_Econometria_II)

## Ferramentas
`statsmodels`, `pmdarima`, `pandas`, `matplotlib`, `python-bcb`

## Projetos deste módulo
- [`projeto_ipca_selic/`](projeto_ipca_selic) — previsão do IPCA e da SELIC com modelos ARIMA
- [`var_macro.ipynb`](var_macro.ipynb) — Vetor Autorregressivo entre IPCA, variação da Selic e retorno cambial (dados reais e ao vivo via API do Banco Central), seleção de defasagens, causalidade de Granger, função de resposta a impulso e previsão multivariada
