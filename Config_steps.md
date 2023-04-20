# DIARIO PERF

### Arquitetura de Microserviço

![Alt Text](https://raw.githubusercontent.com/thiagofmart/PERF/main/assets/diagrama.jpg)

## API

- https://dev.perfcloud.app/api/gateway/docs


## Configuração do ambiente de desenvolvimento
### Requisitos
- Docker
- RabbitMQ
- Qualquer SQL Client Software (Exemplo HeidiSQL)
- Postman

### Passo a passo

1 - Para cada microserviço baixe o arquivo docker-compose referente aos seus respectivos diretórios e rode o comando para incializar o container da aplicação

    docker-compose -f MICROSERVIÇO-docker-compose.yml up --build -d

2 - Depois dar git pull em todos os repo do gitlab e criar um virtualenv para cada requirements.txt

