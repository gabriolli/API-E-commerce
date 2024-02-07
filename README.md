# API-E-commerce
**Essa API NÃO deve ser utilizada em um ambiente de produção, é apenas um servidor de desenvolvimento e testes.**


Protótipo de uma API de e-commerce simples, construída com Python e Flask.



# Instalação das bibliotecas e pacotes utilizados.
Para utilizar a API, é necessário instalar alguns pacotes na sua máquina, é um processo bem simple.

Primeiramente, você deve ter o python instalado no seu computador, você pode fazer o download e instalar o Python [clicando aqui](https://www.python.org/downloads/)

1. Abra o terminal do seu computador (abra como administrador) e navegue até a pasta da API.
   
2. Agora digite o seguinte comando "pip install -r requirements.txt" e pressione a tecla Enter.

   ![image](https://github.com/gabriolli/API-E-commerce/assets/98133634/e1c81ff8-5b82-4d3c-a93c-2481f9e5068d)

O download e a instalação serão feitos automaticamente.


#Como utilizar a API
Utilizando o aplicativo [Postman](https://www.postman.com/downloads/), você pode navegar entre as rotas criadas e interagir com a API.

Para configurar o Postman, primeiramente rode o programa (arquivo application.py) e copie o endereço onde a aplicação está sendo rodada.
  Estou utilizando o VS Code para abrir e executar a aplicação.
  ![image](https://github.com/gabriolli/API-E-commerce/assets/98133634/05660e1c-8cca-412b-8169-771211697917)
  ![image](https://github.com/gabriolli/API-E-commerce/assets/98133634/e69ac4c6-98d3-4368-a001-df04dcd53ca2)

1. No Postman, vá até *Environments* e clique no "+";
2. Dê um nome ao seu environment, pode ser qualquer nome, mas utilize o "LOCAL" para saber que o mesmo é rodado em sua máquina;
3. Em *Variable*, digite "baseUrl", não pode ser outro texto;
4. Em *Inivial value*, cole o endereço da aplicação que você copiou do terminal;
5. Salve seu environment;
6. Agora selecione o environment que você criou.

   ![image](https://github.com/gabriolli/API-E-commerce/assets/98133634/09f23392-8034-42fa-99f4-dd6a783a4e52)

**A API possui um sistema de login.**

Para logar e utilizar as rotas, você pode usar as seguintes credenciais:

Username: admin

Password: 1579

![image](https://github.com/gabriolli/API-E-commerce/assets/98133634/18d3cbcf-e7e6-459a-aea6-4b59e46e9ed1)


Assim, você terá acesso a todas as rotas da API. As credenciais podem ser alteradas usando o terminal.
