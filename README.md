# 🎬 Projeto 01- AWS

Este projeto apresenta conceitos fundamentais de **Computação em Nuvem com AWS** e um **fluxo prático para Delivery de Açaí** utilizando serviços da Amazon.

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

## 📊 Fluxo: Delivery de Açaí com Computação em Nuvem AWS

  ![Delivery de Açaí](https://github.com/davidkuin/Cloud-Computing-EC2/blob/3dbc71a6de102e3e5869f1e30d9a31c3d9def247/aws1.drawio.png).

---

## 🚀 Tecnologias AWS Utilizadas

- **EC2** → processamento e lógica da aplicação.  
- **EBS** → armazenamento das instâncias.  
- **RDS** → Para um banco de dados relacional.  
- **Load Balancer** → Distribui o tráfego entre múltiplas instâncias EC2.
  
1.**Entre Usuário e Load Balancer:**

• "Requisições HTTP/HTTPS para acessar a aplicação."

2. **Entre Load Balancer e EC2:**

• "Redireciona requisições para instâncias EC2 disponíveis."

3. **Entre EC2 e EBS:**

• "Leitura e gravação de dados persistentes."

4. **Entre EC2 e RDS:**

• "Consultas e atualizações de dados no banco de dados."

