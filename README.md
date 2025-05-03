# Template para desenvolvimento e entrega do Checkpoint 1

Nome: Leonardo Dantas Marques RM 95384  

Turma: 2TDSPI

Ano: 2023

## Objetivo

Avaliar conceitos sobre Modelagem de dados e Aprendizado de Máquina (ML) adquiridos no curso.


## Descrição do desafio

Você foi contratado por uma empresa que desenvolveu uma plataforma de compra e venda de carros usados. O funcionamento é bem simples, os usuários cadastram o carro que querem vender e esperam que outro usuário os compre, a empresa então fica com uma parte do valor de venda. Seu papel é desenvolver um modelo que possa determinar qual o melhor preço de venda para um usado.

Para nortear o desenvolvimento, você precisa de um ponto de partida e determinou uma pergunta chave: Qual o preço de venda de um veículo Volkswagen Sedan 2.0 a gasolina, ano 2005, com cerca de 172095 km rodados?

## Desenvolvimento do projeto
O projeto se baseia no DataFrame "Carros.csv", onde ele é lido, as informações mais importantes são filtradas (podemos vizualizar através dos gráficos gerados), os modelos de regressão linear, e árvore de decisão são utilizados para descobrirmos qual possuí um melhor desempenho, e utiliza-lo para prever o valor do carro que queremos.

## Como executar o projeto
Baixar o DataFrame (Carros.csv), e executar o projeto
    
## Pré-requisitos
pandas, matplotlib, seaborn, sklearn.model_selection(train_test_split), sklearn.linear_model(LinearRegression), sklearn.metrics(mean_squared_error, mean_absolute_error, r2_score), sklearn.tree (DecisionTreeRegressor).


