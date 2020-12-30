 <h2>Sistema de gerenciamento de Meeting Rooms</h2>

Pequeno sistema para o gerenciamento de salas virtuais através de uma API REST, criada com o Spring Boot.

Foram abordados os seguintes tópicos:

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8082/api/v1/rooms
```

#A aplicação encontra-se configurada e conectada a um banco de dados em memória. Após o build do projeto, basta acessar a seguinte url:

```
http://localhost:8082/h2-console
```

Para acesso ao bando de dados, é necessário que a configuração do JDBC esteja igual ao exemplo abaixo:

```
JDBC URL:jdbc:h2:mem:testdb
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

* Java 11 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.

A API espera reeber um objeto json conforme exemplo abaixo:

                             {
                                 "name": "",
                                 "date": "",
                                 "startHour": "",
                                 "endHour": ""
                              }

