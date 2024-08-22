# Desafio_cadastra
O objetivo desse desafio é desenvolver um modelo para previsão de vendas (sell-out) para integrar o processo de planejamento de demanda do grupo. Este processo tem como objetivo orientar o plano de produção da indústria. Em outras palavras, a partir dessa previsão de vendas a Indústria irá estabelecer quais produtos e quando fabricá-los.

Entregáveis:
1.	Análise exploratória e descritiva dos dados;
2.	Modelo de previsão;

Importante:

●	Justificar a abordagem escolhida para a modelagem;

R: Escolhi a técnica de arvores sequenciais através do algorítmimo XGBoost, pois possui um ótimo desempenho e resultados muito precisos.

●	Justificar a escolha da(s) métrica(s) de avaliação do modelo;

R: Utilizei as métricas RMSE, MAPE e MAE pois acredito que elas passam informações confiáveis sobre a performance das predições do modelo. 

Conseguimos verificar se estamos prevendo valores muito discrepantes através da RMSE, a MAPE nos dá uma visão mais de negócio por nos passar os erros em percentual
e a MAE nos dá uma visão da dimensão dos nossos erros na mesma escala da nossa variável alvo.

●	Separar os entregáveis 1 e 2 em dois Jupyter Notebooks;

●	Utilize os notebooks para responder questionamentos e discutir sobre resultados;

●	Subir os entregáveis no GitHub e enviar o link


