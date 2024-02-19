# **Trabalhando com Machine Learning na Prática no Azure ML**

## Passo 1


    Criação de um Workspace na Azure para o desenvolvimento do projeot


## Passo 2


    Criação de um trabalho automatizado por machine learning, seguindo o passo a passo fornecido pela plataforma da Azure


## Passo 3


    Na aba de visão geral, analisar qual foi o melhor algoritmo em questão de desempenho, que no caso foi VotingEnsemble, com isso criar um modelo para poder encontrar
    os pontos de extremidade e por fim inserir o seguinte imput:


{
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }


 para dessa forma obter como resultado o valor de 374.85293514112186

 
   



