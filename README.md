# toy-store-compose

# Toystore - Ambiente Local com Docker Compose

Este projeto configura todo o ambiente necessário para a execução do ecossistema Toystore utilizando Docker Compose.

## 🚀 Serviços Disponíveis

| Serviço      | Porta Local | Container               |
|--------------|-------------|--------------------------|
| PostgreSQL   | 5432        | postgres-toy-store       |
| MongoDB      | 27017       | mongo-toy-store          |
| RabbitMQ     | 5672 / 15672| rabbitmq-toy-store       |
| Pagamento    | 8081        | toy-store-pagamento      |
| Estoque      | 8082        | toy-store-stock          |
| Cliente      | 8083        | toystore-customer-app    |
| Produto      | 8084        | toy-store-product        |
| Pedido       | 8080        | pedido-service           |

## 🔧 Como Usar

1. Clone este repositório:

```bash
git clone https://github.com/ViniCampos/toy-store-compose.git
```

2. Clone este repositório:
```bash
docker-compose up -d
docker ps
docker-compose down

```
