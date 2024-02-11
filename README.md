# Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML
Trabalhando com Machine Learning na Prática no Azure ML

Segui o passo a passo disponível em: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

## 1. Criamos o modelo de previsão

## 2. Métricas do modelo

## 3. Configuramos o ponto de extremidade

## 4. Realização de testes

### 4.1. Entrada
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

### 4.2. Saída
{
  "Results": [
    351.3297544158021
  ]
}

1. Crie um novo repositório no github com um nome a sua preferência
2. Crie um modelo de previsão com seus devidos pontos de extremidade configurados
3. Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa
4. Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade
5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'
