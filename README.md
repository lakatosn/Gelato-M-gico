# Previsão de Vendas de Sorvete 🍦

## Descrição
Este projeto utiliza Machine Learning para prever vendas de sorvete com base na temperatura do dia. O objetivo é auxiliar sorveterias a planejar melhor a produção, evitando desperdícios e maximizando lucros.

## Estrutura do Projeto
- `inputs/` : Dados históricos de vendas
- `src/train_model.py` : Treina e registra o modelo no MLflow
- `src/predict.py` : Gera previsões
- `requirements.txt` : Dependências do projeto

## Como Executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Treine o modelo: `python src/train_model.py`
3. Pegue o `RUN_ID` do modelo no terminal
4. Faça previsões: `python src/predict.py` (substituindo o RUN_ID)

## Resultados
- Modelo de regressão linear treinado
- Métricas: MAE, MSE, R²
- Registro do modelo no MLflow para rastreabilidade

## Insights
- Vendas aumentam com a temperatura
- Previsão ajuda no planejamento de produção
- Modelo simples, mas pode ser expandido com variáveis adicionais
