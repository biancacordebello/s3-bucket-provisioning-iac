# S3 Static Website Provisioning

## Português
Este repositório contém um playbook do Ansible que automatiza a criação de um bucket S3 na AWS, configurado para hospedar um site estático. O playbook aplica tags de ambiente, permissões de acesso e configura documentos de índice e erro do site.

## Funcionalidades

- Criação de bucket S3 configurado para site estático
- Aplicação de tags ao bucket S3, como Nome e Ambiente
- Configuração de permissões de acesso público
- Definição de documentos de índice e erro (ex.: `index.html` e `error.html`)
- Integração com GitHub Actions para automação

## Pré-requisitos

- Conta AWS com permissões de gerenciamento do S3 (S3 Full Access)
- Chave de acesso e chave secreta configuradas no GitHub Secrets (`AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`)
- Python e Ansible instalados localmente, ou uso do GitHub Actions


## English
This repository contains an Ansible playbook that automates the creation of an S3 bucket on AWS, configured to host a static website. The playbook applies environment tags, sets access permissions, and configures index and error documents for the website.

## Features

- Provision an S3 bucket configured for static website hosting
- Apply tags to the S3 bucket, such as Name and Environment
- Configure public access permissions
- Define index and error documents (e.g., `index.html` and `error.html`)
- GitHub Actions integration for automation

## Prerequisites

- AWS account with S3 management permissions (S3 Full Access)
- Access key and secret key configured in GitHub Secrets (`AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`)
- Python and Ansible installed locally, or GitHub Actions setup
