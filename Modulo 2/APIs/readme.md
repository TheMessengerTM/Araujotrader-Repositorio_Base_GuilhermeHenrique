# Aula 04 - API's

## O que é uma "api"?

    API significa: 
        Application Programming Interface 
        Interface de Programação de Aplicações

    Podemos explicar fazendo uma analogia com um garçom que
    pega o pedido(frontend) leva para a cozinha(backend) onde vai ser preparada a comida (processado o pedido)
    Esse garçom também trás de volta a comida pronta(resposta do pedido da api).

    exemplos:
        - e-commerce consome uma api dos correios para calcular frete.
        - aplicativo consome api para buscar previsão do tempo
        - uber consome api para calcular preço, buscar motoristas disponíveis.

    Permite que aplicativos diferentes "conversem".

## Como funciona ?

    Existem vários métodos: Rest, Soap, Rpc, Web Sockets

    Vamos utilizar "REST" (Representational State Transfer)

    Rest utiliza como meio de comunicação o HTTP (mesmo meio que sites)
    HTTP(Hyper Text Transfer Protocol)

    Rest via Http utiliza 5 tipos de requisições:

        - Get (pegar/visualizar - muito usado! "Consumir a api")
        - Post (envia dados via api)
        - Put (atualiza algum dado que está no servidor)
        - Patch (atualizar parte de um conteúdo)
        - Delete (apaga do servidor)
    * pertinente associar métodos rest com CRUD de banco de dados
    