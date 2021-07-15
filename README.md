<h2>Digital Innovation: Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>
<h3>BootCamp DIO em parceria com a GFT - Java fullstack 2</h3>

Treinamento com objetivo de desenvolver testes unitários em uma API REST para o gerenciamento de estoques de cerveja. 
Conceitos e vantagens de criar testes unitários com JUnit e Mockito. 
Desenvolver funcionalidades da nossa API através da prática do TDD.

Tópicos abordados:

* Baixar um projeto através do Git para desenvolver nossos testes unitários. 
* Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, importância de cada tipo de teste durante o ciclo de desenvolvimento.
* Foco nos testes unitários: importância do desenvolvimento de testes como parte do ciclo de desenvolvimento de software.
* Frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest. 
* Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão.
* TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento no estoque.

Comando para executar o projeto no terminal:

```shell script
mvn spring-boot:run 
```

Comando para executar a suíte de testes desenvolvida:

```shell script
mvn clean test
```

Após executar, abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

Pré-requisitos para a execução do projeto:

* Java 11 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT.
* ... vontade de aprender e compartilhar conhecimento :)

Links sobre tópicos abordados:

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

[Neste link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), seguem os slides apresentados como o roteiro utilizado para o desenvolvimento do projeto da nossa sessão.

projeto ministrado por Rodrigo Peleias: https://github.com/rpeleias



