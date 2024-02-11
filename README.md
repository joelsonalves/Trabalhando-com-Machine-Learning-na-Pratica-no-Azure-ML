# Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML
Trabalhando com Machine Learning na Prática no Azure ML

Segui o passo a passo disponível em: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

## 1. Modelo de previsão

![Modelo](./static/modelo.png)

## 2. Métricas do modelo

### 2.1. Predict vs True
![Predict vs True](./static/predicted_vs_true.png)

### 2.2. Residuals
![Predict vs True](./static/residuals.png)

## 3. Ponto de extremidade

![Ponto de Extremidade](./static/ponto_de_extremidade.png)

## 4. Realização de testes

### 4.1. Entrada
```
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
```

### 4.2. Saída
```
{
  "Results": [
    351.3297544158021
  ]
}
```
