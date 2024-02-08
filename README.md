# API-E-commerce
**Essa API NÃO deve ser utilizada em um ambiente de produção, é apenas um servidor de desenvolvimento e testes.**


Protótipo de uma API de e-commerce simples, construída com Python e Flask.



# Instalação das bibliotecas e pacotes utilizados.
Para utilizar a API, é necessário instalar alguns pacotes na sua máquina, é um processo bem simple.

Primeiramente, você deve ter o python instalado no seu computador, você pode fazer o download e instalar o Python [clicando aqui](https://www.python.org/downloads/)

1. Abra o terminal do seu computador (abra como administrador) e navegue até a pasta da API.
   
2. Agora digite o seguinte comando "pip install -r requirements.txt" e pressione a tecla Enter.

   ![cmd-image](https://github.com/gabriolli/API-E-commerce/assets/98133634/57522330-f95d-4c0f-adc8-13a08f29523e)


O download e a instalação serão feitos automaticamente.


#Como utilizar a API
Utilizando o aplicativo [Postman](https://www.postman.com/downloads/), você pode navegar entre as rotas criadas e interagir com a API.

Após instalar o Postman na sua máquina, importe o arquivo swagger.yaml:

1. Clique no botão *Import*;
2. Selecione a opção de importar arquivos;
3. selecione o arquivo swagger.yaml na pasta da API. 

![pirmeiro-postman](https://github.com/gabriolli/API-E-commerce/assets/98133634/db1bf433-3053-413b-89c0-a4b5e93e41cc)


Agora, para configurar o Postman, primeiramente rode o programa (arquivo application.py) e copie o endereço onde a aplicação está sendo rodada.

  Estou utilizando o VS Code para abrir e executar a aplicação.

  ![run-api](https://github.com/gabriolli/API-E-commerce/assets/98133634/7df37128-9a1f-45e3-b399-ecf90ed19fd5)



1. No Postman, vá até *Environments* e clique no "+";
2. Dê um nome ao seu environment, pode ser qualquer nome, mas utilize o "LOCAL" para saber que o mesmo é rodado em sua máquina;
3. Em *Variable*, digite "baseUrl", não pode ser outro texto;
4. Em *Initial value*, cole o endereço da aplicação que você copiou do terminal;
5. Salve seu environment;
6. Agora selecione o environment que você criou.

   ![segundo-postamn](https://github.com/gabriolli/API-E-commerce/assets/98133634/a2b99b19-2e35-4901-aa45-169b7ddc959a)


**A API possui um sistema de login.**

Para logar e utilizar as rotas, você pode usar as seguintes credenciais:

Username: admin

Password: 1579

![login-postman](https://github.com/gabriolli/API-E-commerce/assets/98133634/5308c6fd-2f7f-4fe1-b0f2-a1cca8a42fd3)


Assim, você terá acesso a todas as rotas da API. As credenciais podem ser alteradas usando o terminal.

**LEMBRANDO QUE PARA QUE A API FUNCIONE NO POSTMAN, A APLICAÇÃO DEVE ESTAR RODANDO - NO MEU CASO ESTÁ RODANDO NO VS CODE**
