# ☁️ Infraestrutura Cloud Multi-Tier (AWS)

![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

Documentação e modelagem da **Fase 4** do projeto prático de infraestrutura em nuvem. O objetivo principal foi desenhar e implementar uma arquitetura de alta disponibilidade, escalável e segura, dividida em múltiplas camadas (Multi-Tier).

### 🛠️ Serviços e Arquitetura

A arquitetura corporativa foi construída utilizando os seguintes serviços gerenciados:

- 🌐 **VPC (Virtual Private Cloud):** Criação de um ambiente de rede isolado, configurando sub-redes públicas (para roteamento web) e privadas (para dados).
- 💻 **EC2 Auto Scaling:** Instâncias elásticas na camada de aplicação para suportar picos de tráfego e garantir performance.
- 🗄️ **Amazon RDS:** Banco de dados relacional protegido e isolado na camada privada da infraestrutura.

### 🎯 Objetivos de Negócio Alcançados
- Garantir a continuidade do serviço (Alta Disponibilidade) em caso de falha de instâncias.
- Isolar o banco de dados da internet pública por motivos de segurança.
- Aplicar conceitos modernos de Cloud Computing exigidos pelo mercado.
