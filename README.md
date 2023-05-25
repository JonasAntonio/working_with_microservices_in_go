# Projeto de Desenvolvimento de Microservices em Go

Este é um projeto desenvolvido como parte do curso **"Working with Microservices in Go (Golang)"** do professor **Trevor Sawler** disponível na plataforma Udemy. O objetivo deste projeto é aprender a desenvolver microservices em Go, compreendendo o conceito de microservices, sua aplicação e como eles se comunicam entre si.

## Link para o curso

<https://www.udemy.com/course/working-with-microservices-in-go/>

## Descrição

Neste curso, são explorados os fundamentos e práticas do desenvolvimento de microservices em Go:

1. Aprender sobre microservices e quando utilizá-los como arquitetura para sistemas distribuídos.
2. Desenvolver microservices de propósito único e com acoplamento fraco, que trabalham em conjunto como um sistema distribuído.
3. Explorar diferentes métodos de comunicação entre microservices, como REST, RPC e gRPC.
4. Utilizar o Advanced Message Queuing Protocol (AMQP) em conjunto com o RabbitMQ para enviar eventos para microservices.
5. Empacotar seus microservices em contêineres Docker e utilizar o Docker Compose para gerenciar e orquestrar os serviços em um ambiente local.
6. Dimensionar e implantar seus microservices em um Docker Swarm, aproveitando os recursos de escalabilidade e alta disponibilidade.
7. Automatizar as builds e execução das aplicações no Docker utilizando o Makefile.

## Requisitos

Para executar este projeto é necessário:

- Go (versão 1.20 ou superior) instalado em seu sistema.
- Docker instalado em seu sistema.
- Make (utilitário de automação de tarefas) instalado em seu sistema.
- Um editor de texto ou IDE configurado para Go. Recomendável o **Visual Studio Code**.

## Instalação

Para configurar e executar o projeto:

1. Clone este repositório.
2. Certifique-se de ter o Go instalado corretamente em seu sistema.
3. Certifique-se de ter o Docker instalado e em execução em seu sistema.
4. Certifique-se de ter o Make instalado em seu sistema.
5. Abra o projeto em seu editor de texto ou IDE configurado para Go.
6. Abra a pasta `project` em um terminal e execute o comando `make up_build` para subir os containers Docker e realizar a build as aplicações Go.
