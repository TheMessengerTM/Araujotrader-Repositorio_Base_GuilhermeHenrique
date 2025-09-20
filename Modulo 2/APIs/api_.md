# Aula: Trabalhando com APIs em Python

    Vamos desvendar o mundo das APIs, entender o que são e como podemos "conversar" com elas usando Python.
    Aprenderemos a utilizar as bibliotecas requests e "urllib" para buscar e interagir com dados na web, uma habilidade essencial para qualquer desenvolvedor nos dias de hoje.

## Conceito: O que são APIs?

    Imagine que você está em um restaurante. Você (o cliente) quer uma comida específica, mas não tem acesso direto à cozinha (o servidor onde os dados estão). Para fazer seu pedido, você chama o garçom (a API). Você entrega seu pedido ao garçom, ele o leva até a cozinha, a cozinha prepara o prato e o entrega de volta ao garçom, que finalmente o traz até sua mesa.

    No mundo da programação, uma API (Application Programming Interface - Interface de Programação de Aplicações) funciona de maneira muito semelhante. 
    
    Ela é um conjunto de regras e definições que permite que diferentes sistemas de software se comuniquem entre si.

    Cliente: É o programa que faz a solicitação (nosso script Python).

    Servidor: É o sistema que contém os dados e a lógica que queremos acessar (por exemplo, um site de previsão do tempo, uma rede social, um banco de dados de filmes).

    API: É o intermediário que recebe a solicitação do cliente, a traduz para o servidor, recebe a resposta do servidor e a entrega de volta ao cliente em um formato que ele possa entender (geralmente JSON ou XML).

    Quando "consumimos" uma API, estamos enviando uma solicitação (request) para um endereço específico (chamado de endpoint) e recebendo uma resposta (response).

## Atividade prática - Consultando o preço do Bitcoin

 
    Nossa missão será criar um script em Python que consulta uma API pública para obter o preço atual do Bitcoin em Reais (BRL), Dólares (USD) e Euros (EUR) e exibi-lo de forma amigável.

    Usaremos a API da CoinGecko, que é gratuita e não exige chave de autenticação para consultas simples.

Endpoint que usaremos: 

https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=brl,usd,eur


## Exercício Prático 2: BeautifulSoup - Extraindo Dados de HTML 


    Objetivo: Aprender a extrair informações diretamente de uma página da web. Vamos "raspar" (scrape) os títulos das últimas notícias da página principal do portal G1.

    Conceito: Nem sempre os dados que queremos estão em uma API organizada. Muitas vezes, eles estão simplesmente exibidos em uma página HTML. Web scraping é a técnica de automatizar a extração desses dados. O BeautifulSoup é uma biblioteca fantástica que analisa o código HTML de uma página e nos dá ferramentas para navegar e encontrar as informações que queremos.

