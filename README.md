# Subscriber Services

## Descrição

Bem-vindo ao **Subscriber Services**! Este sistema é desenvolvido em Go e tem como objetivo gerenciar assinantes de forma eficiente. Utiliza Redis para armazenamento de sessões e goroutines para envio de emails e gerenciamento de assinaturas, garantindo alta performance.

### Pré-requisitos

✅ Go 1.22 ou superior

### Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/silviobassi/subscriber-services.git
    ```

2. Instale as dependências:
    ```sh
    cd subscriber-services
    go mod tidy
    ```

3. Ainda, na raiz do projeto, utilize o Docker Compose para subir o Redis, Postgres e Mailhog (para testes de envio de emails):
    ```sh
    docker-compose up -d
    ```

## Execução da Aplicação

Para iniciar o serviço, execute:
```sh
go run main.go
```
ou
```
make start
```

