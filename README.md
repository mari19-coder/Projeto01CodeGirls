# 🎬 Projeto 01 AWS

Este projeto apresenta conceitos fundamentais de **Computação em Nuvem com AWS** e um **Delivery de Açaí** utilizando serviços da Amazon.

---

## ☁️ Introdução à Nuvem e AWS

- **OPEX x CAPEX**: Cloud é um investimento **OPEX** (custo recorrente), diferente de **CAPEX** (infraestrutura física de longo prazo).  
- **Modelos de serviço**:  
  - **IaaS**: infraestrutura (servidores, rede, SO).  
  - **PaaS**: infraestrutura + SO + banco de dados + ferramentas.  
  - **SaaS**: software completo entregue como serviço.  
- **CDN (Content Delivery Network)**: rede de servidores que entregam conteúdo com menor latência.  
- **Critérios para escolher região**: compliance, disponibilidade, custo e latência.  
- **AWS Snowball**: transporte físico de grandes volumes de dados para a nuvem.

---

## 👩‍💻 Usuários e Identidade

- **Centro de Identidade**: gerencia acessos de forma centralizada, com políticas de segurança e credenciais individuais.  
- **IAM**: usado para serviços específicos (CodeCommit, Keyspaces) ou acessos de backup/emergência.  

---

## ⚙️ Computação em Nuvem com EC2

- **EC2 (Elastic Compute Cloud)**: máquinas virtuais em modelo **IaaS**.  
- **Cálculo de custos**: feito pelo **AWS Price Calculator**.  
- **Instâncias**:  
  - Sob demanda → flexíveis e temporárias.  
  - Reservadas → mais baratas, contrato anual.  
  - Spot → até 90% mais baratas, mas podem ser encerradas a qualquer momento.  

---

## 📊 Fluxo: Compra de Ingresso de Cinema com Computação em Nuvem AWS

![Fluxograma da compra de ingresso](<img width="654" height="482" alt="aws" src="https://github.com/user-attachments/assets/d2a3d6b6-6d31-497b-85ba-0615e3bc6cfd" />
).  

---

## 🚀 Tecnologias AWS Utilizadas

- **EC2** → processamento e lógica da aplicação.  
- **EBS** → armazenamento das instâncias.  
- **Load Balancer** → Para distribuir o tráfego.  
- **RDS ** → Para um banco de dados relacional.  

S3 → histórico de compras.

S3 Glacier → arquivamento de longo prazo.
