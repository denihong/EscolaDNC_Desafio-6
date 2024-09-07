# Escola DNC: Desafio 6 🚀🚀

## Dataset: **https://drive.google.com/file/d/1AUntWLIla0u9NHaFpyqgyiK5TVK_a6Cp/view?usp=sharing**

## _Desafio: Preveja os usuários com alta chance de deixar seu Streaming_
Utilize um modelo de classificação para mapear qual o perfil de
usuários tem mais chance de deixar sua plataforma de streaming.
Compreender quem é o perfil que está aumentando o churn do seu
negócio é essencial para tomar ações que reduzam essas perdas,
seja alterando critérios na venda ou modificando o produto.

## _Case:_
Você trabalha em uma plataforma de streaming e a diretoria está preocupada com o
alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível
prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça,
e com base nessa informação tomar ações para reduzir o churn.
Seu objetivo é criar um modelo de classificação capaz de prever se um usuário tem
mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa
forneceu uma base de dados em csv contendo dados sobre as contas dos clientes.

Sobre os dados: Problema de ecommerce, disponível no Kaggle. Acesse os dados aqui:

``` https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75a740fb-4146-455a-8d13-6a24ba56d2c8/streaming_data.csv```

## _🎯Etapas de Desenvolvimento_

* ### Etapa 01) Análise exploratória dos dados (Data Understanding):
  1. Carregue a base de dados;
  2. Realize uma descrição estatística dos dados;
  3. Verifique os tipos de dados;
  4. Verifique a quantidade de valores faltantes;

* ### Etapa 02) Tratamento dos Dados (Data Preparation):
  1. Substituir valores “NaN” por 0 Colunas → Time_on_platform, Num_streaming_services, Churned, Avg_rating, Devices_connected;
  2. Dropar linhas nulas nas colunas Gender, Subscription_type e Age;
  3. Transformando valores churned 0 e 1 por No e Yes;
  4. Transformando valores floats em valores inteiros;

* ### Etapa 03) Modelagem dos Dados - Regressão Logística:
  1. Definir variáveis X e y para o modelo;
  2. Realizar o .fit do modelo;
  3. Separar em train e test;
  4. Realizar a modelagem;
  5. Plotar matrix confusão;
  6. Printar métricas;

* ### Etapa 04) Modelagem dos Dados - Tunning:
  1. Definir variáveis X e y para o modelo;
  2. Realizar o .fit do modelo;
  3. Separar em train e test;
  4. Realizar a modelagem;
  5. Plotar matrix confusão;
  6. Printar métricas;

* ### Etapa 05) Modelagem dos Dados - Random Forest:
  1. Realizar a montagem do grid search;
  2. Realizar o .fit do modelo;
  3. Realizar o Tunning;
  4. Realizar a modelagem;
  5. Plotar matrix confusão;
  6. Printar métricas;


