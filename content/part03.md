# Parte 3 - Elementos da Solução

1. Criar um Node-RED Starter

   1.1. Executar as configurações de segurança para proteger com usuário e senha a editor Node-RED
  
   1.2. Adicionar o componente IBMIOT no editor Node-RED
  
2. Criar um serviço IBM Watson IoT Platform

    2.1 Vincular a aplicação Node-RED Starter ao serviço IBM Watson IoT Platform
  
    2.2 No serviço IBM Watson IoT Platform, configurar a opção de conexão de segurança para TLS Optional
    
    2.3 Criar Device Type WashingMachine
    
    2.4 Criar Device ID Washer01
    
    2.5 Definir senha
  
3. Criar um serviço IBM Cloud Object Storage (ICOS)

4. Criar um serviço IBM Watson Machine Learning

    4.1 Configurar o ICOS

5. Importar o Flow1 e Flow2 dentro do editor Node-RED
  
    5.1 Flow 1 (https://github.com/cesariojr/cogiot/blob/master/content/flow1.json)
  
    5.2 Flow 2 (https://github.com/cesariojr/cogiot/blob/master/content/flow2).json

6. Criar database washing dentro do Cloudant

7. Criar novo projeto no IBM Watson Machine Learning

    7.1 Criar novo notebook, dentro do novo projeto com o runtime tipo "Default Spark Python 3.6 XS" e apontar na opção "From URL" o endereço https://raw.githubusercontent.com/cesariojr/cogiot/master/content/CognitiveIoT.ipynb

    7.2 Atualizar os dados de Hostname, user e password do Cloudant dentro do notebook, utilizando as informações encontradas na aplicação Node-RED Starter, menu Runtime, Environment Variables, seção  "cloudantNoSQLDB"

    7.3 Executar o Notebook, não executando apenas as duas últimas linhas.

8. No editor Node-RED, atualizar o Flow 2 com o HTTP Endpoint (ver seção 5 - https://developer.ibm.com/tutorials/iot-cognitive-iot-app-machine-learning/)

9. No editor Node-RED, atualizar o Flow 1 com o MQTT Endpoint (ver seção 6 - https://developer.ibm.com/tutorials/iot-cognitive-iot-app-machine-learning/)

13. No editor Node-RED, testar os Endpoints dos Flows 1 e 2

14. Voltar ao IBM Watson Machine Learning, dentro do projeto e notebook, executar as duas últimas linhas do mesmo

***
Links Rápidos :
[Índice](https://github.com/cesariojr/cogiot/) - [Parte 1](/content/pat01.md) - [Parte 2](/content/part02.md) - **[Parte 3](/content/part03.md)**
