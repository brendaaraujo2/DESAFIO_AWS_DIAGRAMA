📘 Desafio – Diagrama de Arquitetura AWSDiagrama AWS 

📌 Sobre o Projeto

Este repositório contém um diagrama de arquitetura AWS, desenvolvido como parte de um desafio prático de modelagem em nuvem. O objetivo é representar, de forma visual e organizada, os principais componentes de uma infraestrutura na AWS, destacando suas conexões, camadas de segurança e fluxos de dados.

O diagrama foi criado utilizando a ferramenta draw.io

🏗️ Arquitetura Representada

A arquitetura proposta inclui os seguintes serviços e componentes da AWS:

IAM – Controle de identidades e permissões (CEO, administradores e funcionários).
EC2 – Servidores virtuais para execução de aplicações.
EBS – Armazenamento em blocos associado à instância EC2.
Lambda – Funções serverless para processamento sob demanda.
SNS – Serviço de notificações para disparo de mensagens.
NoSQL Database – Armazenamento de dados não relacionais.
CloudFront – Rede de distribuição de conteúdo (CDN) para otimizar a entrega.
Security Group – Controle de tráfego e camadas de segurança da rede.

📊 O diagrama mostra as interações entre esses componentes, como:

Usuários acessando via IAM;
EC2 comunicando-se com EBS e bancos NoSQL;
Funções Lambda gerando logs e interagindo com o SNS;
O CloudFront distribuindo conteúdo aos clientes finais.

🎯 Objetivos de Aprendizado

Entender o papel de cada serviço AWS dentro de uma arquitetura moderna.
Praticar a modelagem de soluções em nuvem utilizando diagramas visuais.
Demonstrar boas práticas de segurança, escalabilidade e organização.

Por Brenda Campos.
