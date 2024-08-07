# Subscriber Services

## Descrição

Bem-vindo ao **Subscriber Services**! Este sistema é desenvolvido em Go e tem como objetivo gerenciar assinantes de forma eficiente. Utiliza Redis para armazenamento de sessões e goroutines para envio de emails e gerenciamento de assinaturas, garantindo alta performance e escalabilidade.

### Pré-requisitos

✅ Go 1.22 ou superior
✅ Redis (instalado e em execução)

### Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/silviobassi/subscriber-services.git
    cd subscriber-services
    ```

2. Instale as dependências:
    ```sh
    go mod tidy
    ```

## Utilização

Para iniciar o serviço, execute:
```sh
go run main.go
```
ou
```
make start
```

