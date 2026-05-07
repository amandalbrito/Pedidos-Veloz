# 🐳 Pedidos Veloz

## 📌 Sobre
O **Pedidos Veloz** é um projeto acadêmico focado em arquitetura de microsserviços, conteinerização e orquestração de aplicações cloud-native.

A proposta do projeto é simular uma plataforma de pedidos para um e-commerce, aplicando práticas modernas de DevOps, Kubernetes, CI/CD e observabilidade em um ambiente distribuído.

O sistema foi estruturado em múltiplos serviços independentes, permitindo escalabilidade, padronização de ambientes e maior confiabilidade durante deploys. :contentReference[oaicite:0]{index=0}

---

## 🚀 Tecnologias
- Docker  
- Docker Compose  
- Kubernetes (K8s)  
- Terraform  
- Java  
- MySQL  
- Nginx  
- YAML  

---

## 🏗️ Arquitetura do Projeto

O sistema é composto pelos seguintes microsserviços:

- API Gateway  
- Serviço de Pedidos  
- Serviço de Pagamentos  
- Serviço de Estoque  
- Banco de Dados  
- Observabilidade e infraestrutura Kubernetes  

Cada serviço possui sua própria estrutura e configuração, seguindo o modelo de aplicações distribuídas. :contentReference[oaicite:1]{index=1}

---

## 🎯 Funcionalidades
- Arquitetura baseada em microsserviços  
- Containerização com Docker  
- Ambiente local automatizado com Docker Compose  
- Orquestração com Kubernetes  
- Configuração de ConfigMaps e Secrets  
- Estrutura para CI/CD  
- Deploy escalável e padronizado  
- Organização de infraestrutura como código com Terraform  
- Estrutura inicial de observabilidade e monitoramento  

---

## ▶️ Como executar

### 🐳 Ambiente local
```bash
docker compose up --build
