# rock-in-rio-arquitetura
Arquitetura para suportar venda de ingressos em alta demanda. Utiliza Redis para fila justa por ordem de chegada e controle de estoque atômico, evitando oversell. API Gateway gerencia autenticação e rate limit. Após a compra, RabbitMQ notifica o usuário de forma assíncrona. Serviços construídos com ASP.NET Core e Entity Framework.
