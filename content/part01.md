# Parte 1 - Introdução

## Créditos

Esse conteúdo foi baseado no artigo "Build a cognitive IoT app in just 7 steps", (https://developer.ibm.com/tutorials/iot-cognitive-iot-app-machine-learning/) de Romeo Kienzler.

## Solução cognitiva de IoT

Vamos criar uma solução cognitiva de IoT usando o IBM Cloud, a plataforma IBM Watson IoT e o IBM Watson Studio.
Nosso novo cenário ou caso de uso é baseado em eletrônicos de consumo: uma máquina de lavar inteligente.
Vamos considerar um fabricante de dispositivos que descobriu que o motor usado em um modelo específico é danificado quando a corrente elétrica é instável.
A princípio, o fabricante confiou nos dados da nuvem para detectar anomalias na corrente elétrica. Quando a solução IoT recebeu dados de que a corrente elétrica era instável, um comando foi enviado de volta à máquina de lavar para desligar o motor.
Eventualmente, o fabricante percebe que a latência é muito alta e a estabilidade da conexão à Internet é muito baixa. Portanto, o fabricante decide implementar a análise no componente de borda, omitindo a nuvem para esse processo específico.

## Modelo Operacional

<p align="center">
<img src="https://github.com/cesariojr/cogiot/blob/master/images/Picture1.png" width="700">
</p>

Figura 1: Modelo Operacional
Fonte: Adaptado de Romeo Kienzler, https://developer.ibm.com/tutorials/iot-cognitive-iot-app-machine-learning/

## Componentes IBM Cloud utilizados

Todos os recursos do catálogo da IBM Cloud aqui listados serão utilizados com a camada Lite.

1. Node-RED Starter, aplicação Cloud Foundry, baseada em Node.js que já acompanha uma instância do Cloudant (https://cloud.ibm.com/catalog/starters/node-red-template)
2. IBM Watson IoT Platfom (https://cloud.ibm.com/catalog/services/internet-of-things-platform)
3. IBM Cloud Object Storage - ICOS (https://cloud.ibm.com/catalog/services/cloud-object-storage)
4. IBM Watson Machine Learning (https://cloud.ibm.com/catalog/services/machine-learning)

## Artigos interessantes

https://developer.ibm.com/recipes/tutorials/machine-learning-and-ibm-watson-studio/
https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/ml-overview.html


***
Links Rápidos :
[Índice](https://github.com/cesariojr/cogiot/) - **[Parte 1](/content/pat01.md)** - [Parte 2](/content/part02.md) - [Parte 3](/content/part03.md) - [Parte 4](/content/part04.md) - [Parte 5](/content/part05.md) - [Parte 6](/content/part06.md) - [Parte 7](/content/part07.md) - [Parte 8](/content/part08.md)

