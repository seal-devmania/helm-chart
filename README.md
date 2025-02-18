
# Orki - Sistema Lowcode para Criação de Apps

## Índice

1. [O que é?](#o-que-é)
2. [Como instalar?](#como-instalar)
3. [Quais componentes de cloud usa?](#quais-componentes-de-cloud-usa)
   - [MongoDB](#mongodb)
   - [Redis](#redis)
   - [MQTT](#mqtt)
   - [RabbitMQ](#rabbitmq)
4. [Como começar?](#como-começar)

## O que é?

Orki é um sistema lowcode que permite a criação de aplicativos de forma simplificada e rápida, possibilitando a prototipagem e desenvolvimento de soluções sem a necessidade de codificação complexa. A plataforma Orki é utilizada por diversas empresas e desenvolvedores para criar aplicativos personalizados com menor tempo de desenvolvimento e maior flexibilidade.

## Como instalar?

Para instalar o Orki, você precisará usar os seguintes comandos Helm:

### Add repository  

```sh
helm repo  add  orki-repo  https://seal-devmania.github.io/helm-chart
```  

### Install
```sh
helm  install  my-orki-repo  orki-repo/orki
```


## Quais componentes de cloud usa?

### MongoDB

MongoDB é um banco de dados NoSQL orientado a documentos que oferece escalabilidade, alta performance e disponibilidade. É utilizado por empresas como Adobe, Google e Verizon para armazenar e gerenciar grandes volumes de dados em seus aplicativos. Orki utiliza MongoDB para armazenar informações dos aplicativos, como modelos de dados e configurações.

### Redis

Redis é um sistema de armazenamento em cache de chave-valor em memória, utilizado para otimizar consultas e processamento de dados. Empresas como Twitter, GitHub e Pinterest usam Redis para melhorar a performance de suas aplicações. No Orki, Redis é utilizado para acelerar o acesso aos dados e garantir uma experiência de usuário mais ágil e responsiva.

### MQTT

MQTT é um protocolo de comunicação leve e eficiente, projetado especificamente para ambientes de Internet das Coisas (IoT) e comunicação entre dispositivos e serviços. Empresas como Amazon Web Services, Microsoft e IBM utilizam MQTT em seus serviços de IoT. Orki utiliza MQTT para facilitar a troca de mensagens entre dispositivos, sensores e serviços do aplicativo.

### RabbitMQ

RabbitMQ é um sistema de mensageria open-source confiável e escalável, que permite a comunicação entre serviços e componentes de uma aplicação. Empresas como Cisco, VMware e Nokia usam RabbitMQ para garantir a entrega de mensagens e integração entre sistemas. No Orki, RabbitMQ é utilizado para gerenciar a comunicação entre os serviços e componentes do aplicativo, garantindo a integridade das informações e a sincronização dos processos.


## Como começar?

1. Faça seu cadastro inicial no Orki.
2. Configure os modelos de dados, APIs e visões do seu aplicativo.
3. Exponha as APIs necessárias para a comunicação entre os componentes e dispositivos.
4. Escreva os scripts de negócio para implementar a lógica de sua aplicação.

Com esses passos, você estará pronto para criar e gerenciar seu aplicativo lowcode utilizando o Orki!

ORKI

# helm-chart

## To Build and `pump version`, create a new branch with version. Example: 

```bash
git checkout -b 0.1.5
```

## Add repository

```sh
helm repo add orki-repo https://seal-devmania.github.io/helm-chart
```


## Install

```sh
helm install my-orki-repo orki-repo/orki
```


# Development

## Pull Request branch

Example: `0.1.22`
Command:
```sh
git checkout -b 0.1.22
```

## Local generate

```sh
helm template . | less
```
