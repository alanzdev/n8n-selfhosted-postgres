# n8n-selfhosted-postgres

Este repositório disponibiliza uma estrutura completa para executar o **n8n** de forma **self-hosted**, utilizando **Docker Compose** e **PostgreSQL** como banco de dados principal.

A proposta é facilitar a implantação do n8n em ambientes locais, servidores ou VPS, garantindo **persistência de dados**, **controle total do ambiente** e **independência de serviços externos**.

---

## 🚀 Funcionalidade

- Executa o n8n em ambiente self-hosted
- Utiliza PostgreSQL como banco de dados
- Persistência de dados via volumes Docker
- Configuração simples e padronizada
- Ideal para automações corporativas, RPA e integrações internas

---

## 🧱 Arquitetura

A solução é composta por:

- **n8n**
  - Orquestrador de automações
  - Interface web para criação e gestão de workflows

- **PostgreSQL**
  - Armazena workflows, execuções, credenciais e configurações
  - Garante persistência e confiabilidade dos dados

- **Docker Compose**
  - Gerenciamento dos serviços
  - Facilita deploy, manutenção e escalabilidade

