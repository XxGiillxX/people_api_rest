<h2>Digital Innovation: Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot</h2>

Desenvolvendo um pequeno sistema para o gerenciamento de pessoas de uma empresa através de uma API REST, criada com o Spring Boot.

Foi desenvolvido com os seguintes tópicos:

* Modelo de projeto com o Spring Boot Initialzr.
* Criação de modelo de dados para o mapeamento de entidades ultilizando o banco H2.
* Desenvolvimento de CRUD básico (Cadastro, leitura, atualização e remoção de pessoas de um sistema).
* Ultilização do padrão arquitetural REST.
* Desenvolvimento de testes unitários para validação das funcionalidades com Postman.
* Implantação do sistema na nuvem através do Heroku.


São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido:

* Java 11 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.
* Conta no GitHub para o armazenamento do seu projeto na nuvem.
* Conta no Heroku para o deploy do projeto na nuvem

  


Para executar o projeto no terminal, digite o seguinte comando:
```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```





