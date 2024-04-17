# Detecção de Fraude em Cartões de Crédito

## Visão Geral

Este projeto visa desenvolver um modelo de aprendizado de máquina para identificar transações fraudulentas de cartões de crédito.

## Dados

O conjunto de dados utilizado consiste em transações de cartões de crédito, onde cada transação é rotulada como fraudulenta ou não. Os dados são altamente desbalanceados, com uma pequena proporção de transações fraudulentas em comparação com transações legítimas.

## Metodologia

O projeto segue uma abordagem de aprendizado supervisionado, utilizando o algoritmo **Naive bayes** e o algoritmo de **Regressão Logística**. Técnicas de pré-processamento de dados, como normalização e codificação, são aplicadas para preparar os dados para o treinamento do modelo.

## Resultados

Os modelos são avaliados com base em métricas como precisão, F1 score, recall, área sob a curva ROC (AUC) e a matriz de confusão.

### Naive Bayes

|     Metrícas     |                 Performance               |
|     --------     |                   -------                 |
| Accuracy         |                     97%                   |
| F1 score         |                     13%                   |
| Recall score     |                     82%                   |
| ROC AUC          |                     96%                   |
| Confusion matrix | TN = 83446, FP = 1827, FN = 29, TP = 141  |

### Regressão Logística

|     Metrícas     |                 Performance               |
|     --------     |                   -------                 |
| Accuracy         |                     99%                   |
| F1 score         |                     67%                   |
| Recall score     |                     54%                   |
| ROC AUC          |                     96%                   |
| Confusion matrix | TN = 85261, FP = 12, FN = 78, TP = 92     |

## Observação

Este projeto tem fins apenas educacionais e não deve ser usado em casos reais.

Banco de dados utilizado: <https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud>

## Qualquer dúvida entre em contato

- Email: <dev.venicius1912@gmail.com>

- LinkedIn: <https://www.linkedin.com/in/venicius-santana-lima/>
