## Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.

Projeto desenvolvido como parte do bootcamp da Digital Innovarion One. 

- *Link do [video](https://web.digitalinnovation.one/lab/desenvolvimento-de-testes-unitarios-para-validar-uma-api-rest-de-gerenciamento-estoques-de-cerveja) realizado por [Rodrigo Peleias](https://github.com/rpeleias)*

Teste unitário de uma API REST para gerenciamento de estoques de cerveja. Ferramentas:

- JUnit
- Mockito
- Hamcrest

<br>

#### Run

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

* Java 14 ou versões superiores. *(Utilizei o Java 15.0.2)*
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.
* Muita vontade de aprender e compartilhar conhecimento :)



<br>

#### Observações

- Este [link](https://www.twilio.com/blog/sdkman-work-with-multiple-versions-java) contém um tutorial de utilização do sdkman que contribuiu modificação da versão do Java.

- No postman, POST json

  ```json
  {
  	“name”:”Colorado apia”,
  	“brand”: “Colorado”,
  	“max”: 20,
  	“quantity”: 10,
  	“type”: “LAGER”
  }
  ```

  Body retornado, ele já faz a verificação se for inserido o mesmo registro

  ```json
  {
      "id": 2,
      "name": "Colorado apia",
      "brand": "Colorado",
      "max": 20,
      "quantity": 10,
      "type": "LAGER"
  }
  ```

  

  

