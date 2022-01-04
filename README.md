# Estudos-Integra-o

# API

Acronomo para apliccation program interface(Interface de programação de Aplicações) sendo ele um conjunto de rotinas e padrões estabelicidos por uma aplicação, para que outras aplicações possam utilizar as funcionalidades desta aplicação.


            API
Client -> Serviço -> Server


# Rest 

Um acronimo para REpresentional State Trasfer(Transferencia de Estado Representativo)
 
Basicamente nossas boas praticas. 

- Ele determina obrigações em trasferenças de dados 
- A transferencia de dados, geralmente, usando o protocolo HTTP

O Rest, delimita algumas obrigações nessas transferencias de dados

## Erros Rest 


HTTP Status Code 

Dividindo em 5 familias 

Familia 100 - informacionais 
Familia 200 - sucesso
Familia 300 - redirecionamento
Familia 400 - erro no cliente
Familia 500 - erro no server

Exemplo de Payload:

{
  "codigo": "COD123",
  "mensagem": "msg",
  "dataHora": 
}


