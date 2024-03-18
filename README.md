# Alura Food

O Alura Food é um projeto desenvolvido durante o curso de arquitetura de microsserviços da Alura.
Ele se propõe a transformar um sistema monolítico em uma arquitetura de microsserviços para melhorar a escalabilidade e a manutenção do sistema.


[![microsservicos.png](https://i.postimg.cc/dVkd0TZX/microsservicos.png)](https://postimg.cc/gxprSjDq)


[![Video no meu canal](https://i.postimg.cc/vmt418P5/Microservi-os.png)](https://www.youtube.com/watch?v=32iWKuWLqPg&t=880s)

- Video no meu canal

https://www.youtube.com/watch?v=32iWKuWLqPg&t=880s

## Visão Geral

O projeto atualmente está focado na decomposição do monolito em microsserviços. Inicia-se com a criação do microsserviço de pagamento, utilizando um banco de dados MySQL para armazenamento de dados.

Para facilitar a comunicação entre os microsserviços, implementa-se o Service Discovery com o Eureka, uma solução do Spring Cloud. Também adiciona-se uma API Gateway usando o Spring Cloud Gateway para centralizar as requisições ao sistema.

Depois adiciona um novo microsserviço para lidar com pedidos, explorando a comunicação síncrona e o balanceamento de carga entre múltiplas instâncias em execução.

Para garantir a resiliência do sistema, aplica-se conceitos de circuit breaker e fallback utilizando o Resilience4J. Isso  permite lidar com falhas em serviços individuais de forma controlada, garantindo a disponibilidade contínua do sistema.

## Tecnologias Utilizadas

- Java
- Spring Boot
- MySQL
- Eureka (Spring Cloud Netflix)
- Spring Cloud Gateway
- Resilience4J

## Como Executar

1. Clone o repositório para sua máquina local.
2. Certifique-se de ter o JDK e o Maven instalados.
3. Importe o projeto em sua IDE de preferência.
4. Execute os microsserviços individualmente ou utilize um ambiente de desenvolvimento local para simular a comunicação entre eles.

## Contribuições

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

## Link do curso 

- Microsserviços na prática: implementando com Java e Spring
https://cursos.alura.com.br/course/microsservicos-implementando-java-spring/task/107184

