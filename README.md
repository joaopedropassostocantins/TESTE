# Projeto: Previsão de Utilidade de Kit Médico

Este projeto utiliza Machine Learning para prever se um kit médico adquirido por passageiros de uma companhia aérea será útil ou não, baseado em dados demográficos e de vendas.

## Modelo Utilizado
- **Algoritmo:** XGBoost Classifier (Gradient Boosting).
- **Métrica Alvo:** F1-Score Weighted.
- **Técnicas:** Label Encoding para variáveis categóricas e tratamento de desbalanceamento de classes.

## Como usar
1. Garanta que `train.csv` e `test.csv` estejam no diretório raiz.
2. Execute `python main.py`.
3. O arquivo `submission.csv` será gerado para submissão.
