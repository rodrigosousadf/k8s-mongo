# k8s-mongo

Este repositório fornece recursos e informações para implantar o MongoDB no Kubernetes (K8s). O Kubernetes é uma plataforma de código aberto para automação, escalonamento e gerenciamento de aplicativos em contêiner. O MongoDB é um banco de dados NoSQL altamente flexível.

## Conteúdo

1. [Introdução](#introdução)
2. [Pré-Requisitos](#pré-requisitos)
3. [Instruções de Implantação](#instruções-de-implantação)
4. [Contribuição](#contribuição)

## 1. Introdução

Este repositório contém recursos e informações relacionados à implantação do MongoDB no ambiente do Kubernetes. Oferecemos scripts, configurações e orientações para ajudar você a executar o MongoDB no Kubernetes de maneira eficiente e confiável.

## 2. Pré-Requisitos

Antes de começar, certifique-se de ter os seguintes requisitos:

- Acesso a um cluster Kubernetes configurado e operacional.
- O utilitário `kubectl` instalado e configurado para acessar o cluster Kubernetes.
- Conhecimento básico do funcionamento do Kubernetes e do MongoDB.

## 3. Instruções de Implantação

Siga estas etapas para implantar o MongoDB no seu cluster Kubernetes:

- Clone este repositório em seu ambiente de desenvolvimento:

   ```bash
   git clone https://github.com/rodrigosousadf/k8s-mongo.git
   ```

- Navegue até o diretório do projeto:

   ```bash
   cd k8s-mongo
   ```

- Personalize as configurações e manifestos conforme necessário para o seu ambiente. Você pode encontrar modelos e exemplos no diretório `kubernetes-configs`.

- Aplique as configurações no Kubernetes:

   ```bash
   kubectl apply -f kubernetes-configs/
   ```

- Monitore o status da implantação e verifique se o MongoDB está em execução no seu cluster:

   ```bash
   kubectl get pods
   ```

## 4. Contribuição

Adoraríamos receber sua contribuição para este projeto. Sinta-se à vontade para criar issues, enviar solicitações de pull ou fornecer feedback. Juntos, podemos melhorar e expandir este recurso.

