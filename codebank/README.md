# Codebank-go

## Aula 1 - Estudo de caso

- docker-compose up -d
- docker-compose ps
- docker exec -it appbank bash  

pasta .pgdata: tem todos os dados do BD postgres

- go mod init github.com/cesaralmeida93/codebank
-go mod tidy

- domain: regras de negócio
- entidades: identidade, representa algo único no sitema que faz parte do projeto
- repository: local onde possui métodos importantes para gravar informações em algum lugar(banco de dados, API, txt, etc)
- dto: recebe dados de fora da aplicação(por exemplo, requisição via grpc, rest, etc. É necessário pegar esses dados de "fora" e jogar no "coração da aplicação)
- o dto pega esses dados, modela eles e joga na aplicação


parei no 1:26:00
- https://www.youtube.com/watch?v=J0JCd1z6P3s&t=2872s&ab_channel=FullCycle

## configurações no PGAdmin
- aba connection:
    - hotsname/address: db
    - port: 5432
    - database: codebank
    - password: root