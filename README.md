# Projeto Conceitual de Banco de Dados - "E-commerce"

### DADOS DO PROJETO

#### REFINANDO O MODELO

#### Cliente 
>Ao invés de "Identificação" nos atributos, opter por "Tipo", onde a intenção é que seja dada a entrada de dados com "PF" ou "PJ". Adicionei o atributo "Documento", para que seja dada a entrada dos dados de "CPF" ou "CNPJ". Ambos atributos precisam ser "UQ".
#### Pagamento
>Optei por criar a entidade "Pagamento", que recebe os atributos de Pedido e Cliente, além de ter os atributos "Método" que receberia uma ou mais entradas, Status, Valor e Data de Pagamento.
#### Entrega
>Optei por criar como entidade "Entrega", uma vez que posso atribuir um Código de Rastreio único para ela. Essa entidade "puxa" os atributos de id do Pedido e id do Cliente. O endereço optei por deixar como um atributo dessa entidade pois possibilita que seja alterado sem precisar entrar no cadastro do cliente toda vez que a entrega for em um local diferente.
#### Pedido
>Na entidade "Pedido", adicionei os atributos "Produto" e "Quantidade"
---
### COMO ME ENCONTRAR?
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafaeloliveirarso/) 
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rafaeloliveirarso)
[![Gmail](https://img.shields.io/badge/Gmail-000000?style=for-the-badge&logo=gmail&logoColor=red)](mailto:rafael.silvaoliveira1992@gmail.com)



