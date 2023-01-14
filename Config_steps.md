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

3 - Conectar o SQL Client Software, criar a tabela "arjadm", na tabela pessoa criar você mesmo e atrelar como usuario com a senha "$12$lFP.RvoZ1w.opk/8LEunMOii.t8HbikSi1NE/8f.Z6GBr8P0AN2A." e o perfil ARJ.