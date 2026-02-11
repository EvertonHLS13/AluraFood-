Microsserviço de Pagamentos com Java e Spring Boot

Este repositório contém a implementação prática de um microsserviço de pagamentos, desenvolvido durante o curso Microsserviços na prática: implementando com Java e Spring.

O projeto foi construído do zero, aplicando conceitos fundamentais de arquitetura de microsserviços, com foco em organização, escalabilidade, desacoplamento e comunicação entre serviços.

Visão Geral do Projeto

Ao longo do desenvolvimento deste projeto, foram implementados os seguintes tópicos:

Criação de um microsserviço de pagamentos

Desenvolvimento de uma API REST com Spring Boot

Utilização de banco de dados isolado por microsserviço

Organização do código em camadas de responsabilidade

Uso de migrations para criação e versionamento do banco de dados

Implementação de Service Discovery e Service Registry com Eureka

Comunicação síncrona entre os microsserviços de pedidos e pagamentos

Tratamento de falhas quando serviços dependentes estão indisponíveis

Implementação de API Gateway para centralizar as requisições

Configuração de balanceamento de carga

Testes das APIs utilizando o Postman

Arquitetura

A aplicação segue o padrão de arquitetura de microsserviços, onde cada serviço:

Possui seu próprio banco de dados

É registrado no Eureka Server

Descobre outros microsserviços dinamicamente por meio do Service Registry

Se comunica com outros serviços através de chamadas síncronas

É acessado externamente por meio de um API Gateway

Tecnologias Utilizadas

Java 17

Spring Boot

Spring Cloud Netflix Eureka

Spring Cloud Gateway

Spring Data JPA

Flyway

MySQL

OpenFeign

Maven

Postman

Testes

As requisições para os microsserviços foram testadas utilizando o Postman, garantindo o correto funcionamento dos endpoints, da comunicação entre serviços e do tratamento de falhas.

Considerações Finais

Este projeto consolida conceitos essenciais para o desenvolvimento de sistemas baseados em microsserviços, abordando desde a construção da API até a comunicação entre serviços, balanceamento de carga e tolerância a falhas.

Caso tenha dúvidas, sugestões ou feedbacks, utilize o fórum da Alura para interagir com outros estudantes e evoluir ainda mais o projeto.
