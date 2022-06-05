# Patterns

## Design Patterns

### **Behavioral Patterns**

#### **Mediator**

Mediator é um padrão de design comportamental que permite reduzir dependências caóticas entre objetos. O padrão restringe as comunicações diretas entre os objetos e os força a colaborar apenas por meio de um objeto mediador.

Exemplo de utilização:

- Command Bus
- Event Bus

#### **Command**

É um padrão de design comportamental que transforma uma solicitação em um objeto autônomo que contém todas as informações sobre a solicitação. Essa transformação permite passar solicitações como argumentos de método, atrasar ou enfileirar a execução de uma solicitação e oferecer suporte a operações reversíveis

- [Ref](https://refactoring.guru/design-patterns/command)

<br>
<br>

## Other Patterns

### **Domain Notification / Notification Pattern**

- [Exception VS Domain Notification](https://balta.io/blog/exception-vs-domain-notification)
- [Não lance Exceptions em seu domínio: use Notifications!](https://imasters.com.br/back-end/nao-lance-exceptions-em-seu-dominio-use-notifications)

### **Fail-Fast Validations**

- [Fail-fast Validations com Pipeline Behavior no MediatR e ASP.Net Core](https://medium.com/tableless/fail-fast-validations-com-pipeline-behavior-no-mediatr-e-asp-net-core-f3854d3c21fa)
- [Fail Fast](https://www.martinfowler.com/ieeeSoftware/failFast.pdf)
