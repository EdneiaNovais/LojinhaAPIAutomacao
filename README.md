# Lojinha API Automação

## Tecnologias utilizadas

- Java
  https://www.oracle.com/br/java/technologies/downloads/#jdk20-windows
- JUnit
  https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-engine/5.9.1
- RestAssured
  https://mvnrepository.com/artifact/io.rest-assured/rest-assured/5.3.0
- Maven
  https://maven.apache.org/

## Testes Automatizados

Testes para validar as partições de equivalência relacionadas ao valor do produto na Lojinha, que estão diretamente vinculados a regra de negócio que diz que o valor do produto deve estar entre R$0,01 e R$7000,00.

## Notas Gerais

- Sempre utilizamos a anotação BeforeEach para capturar o token que
  será utilizado posteriormente nos métodos de testes.
- Armazenamos os dados que são enviados para a API através do uso de classes POJO.
- Criamos dados iniciais através do uso de classe Data Factory para facilitar a criação e controle dos mesmos.
- Nesse projeto fazemos uso do JUnit 5, o que nos dá a possibilidade de usar a anotação DisplayName para dar descrições em Português para o nosso teste.
