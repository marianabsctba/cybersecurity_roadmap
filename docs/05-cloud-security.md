# ☁️ Cloud Security

Esta trilha cobre **segurança em ambientes de computação em nuvem**, com foco em **identidade, rede, monitoramento, postura de segurança e resposta a incidentes**, considerando **AWS, Azure e Google Cloud** em cenários **single-cloud e multi-cloud**.

Cloud Security **não é firewall na nuvem**.  
É **arquitetura, identidade, visibilidade e governança**.

---

## 👥 Carreiras

- **Cloud Security Engineer**  
  Implementa controles de segurança, monitora ambientes cloud, integra ferramentas e responde a incidentes.

- **Cloud Security Architect**  
  Desenha arquiteturas seguras, define padrões, governa riscos e integra segurança ao negócio.

---

## 🧠 Habilidades Técnicas Essenciais

### 🔐 Identity & Access Management (IAM)
- Identidades humanas e não humanas
- Princípio do menor privilégio
- RBAC, ABAC, políticas e roles
- MFA e autenticação forte
- Federation e identidade híbrida

---

### 📊 Logging & Monitoring
- Centralização de logs
- Logs de identidade, rede e workload
- Cloud-native SIEM integration
- Detecção de comportamento anômalo
- Auditoria e rastreabilidade

---

### 🌐 Network Controls
- Segmentação de rede
- Security Groups / NSGs / Firewalls
- VPC / VNet / Subnets
- Controle de tráfego leste-oeste
- Proteção de serviços expostos à internet

---

### 🛡️ Cloud Security Posture Management (CSPM)
- Avaliação contínua de postura
- Hardening de serviços cloud
- Detecção de misconfiguration
- Benchmarks CIS
- Gestão de risco em cloud

---

### 🌍 Multicloud Security
- Padrões de segurança entre clouds
- Normalização de logs
- Controle centralizado de identidade
- Governança e visibilidade unificada
- Risco de shadow IT em cloud

---

## 🔄 Segurança ao Longo do Ciclo Cloud

- **Design seguro (Landing Zones)**
- **Provisionamento seguro (IaC)**
- **Segurança em runtime**
- **Resposta a incidentes em cloud**
- **Governança contínua**

---

## 🧪 Labs Práticos (Essenciais para Cloud Security)

> Cloud Security **se aprende configurando, errando e corrigindo**.

### Plataformas de Labs
- **AWS Well-Architected Labs (Security Pillar)**  
  https://wellarchitectedlabs.com/security/

- **AWS CloudGoat (Vulnerable by Design)**  
  https://github.com/RhinoSecurityLabs/cloudgoat

- **Azure Security Labs (Microsoft Learn)**  
  https://learn.microsoft.com/security/

- **GCP Security Foundations Labs**  
  https://cloud.google.com/security

- **TryHackMe – Cloud Security Labs**  
  https://tryhackme.com/

- **Attack Detection in AWS (DetectionLab-Cloud)**  
  https://github.com/clong/DetectionLab

---

## 📘 Cursos Oficiais (Formação)

### ☁️ AWS
- **AWS Security Fundamentals**  
  https://aws.amazon.com/training/digital/aws-security-fundamentals/

- **AWS Well-Architected – Security Pillar**  
  https://aws.amazon.com/architecture/well-architected/

- **AWS Cloud Security Learning Path**  
  https://aws.amazon.com/training/learn-about/security/

---

### ☁️ Microsoft Azure
- **Secure Your Cloud Data (Microsoft Learn)**  
  https://learn.microsoft.com/training/paths/secure-your-cloud-data/

- **Azure Security Engineer Learning Path (AZ-500)**  
  https://learn.microsoft.com/training/paths/design-implement-azure-security/

---

### ☁️ Google Cloud
- **Google Cloud Security Foundations**  
  https://cloud.google.com/training/security

- **Google Cloud Skills Boost – Security**  
  https://www.cloudskillsboost.google/paths

---

### 🌍 Multicloud / Vendor Neutral
- **Cloud Security Alliance – Training**  
  https://cloudsecurityalliance.org/education/

- **MITRE ATT&CK for Cloud**  
  [https://attack.mitre.org/matrices/cloud/](https://attack.mitre.org/matrices/enterprise/cloud/)

---

## 🧰 Ferramentas Open Source Importantes

### CSPM / Auditoria
- **ScoutSuite** – https://github.com/nccgroup/ScoutSuite
- **Prowler (AWS)** – https://github.com/prowler-cloud/prowler
- **CloudMapper** – https://github.com/duo-labs/cloudmapper

### IaC Security
- **Checkov** – https://github.com/bridgecrewio/checkov
- **tfsec** – https://github.com/aquasecurity/tfsec
- **Terrascan** – https://github.com/accurics/terrascan

### Logging & Detection
- **Falco (runtime)** – https://falco.org/
- **OpenSearch Security Analytics** – https://opensearch.org/docs/latest/security-analytics/

### Identity
- **Keycloak** – https://www.keycloak.org/
- **Open Policy Agent (OPA)** – https://www.openpolicyagent.org/

---

## 🏅 Certificações (Validação de Conhecimento)

### ☁️ AWS
- **AWS Certified Security – Specialty**  
  https://aws.amazon.com/certification/certified-security-specialty/

- **AWS Certified Solutions Architect – Associate/Professional**  
  https://aws.amazon.com/certification/solutions-architect/

---

### ☁️ Microsoft Azure
- **AZ-500 – Azure Security Engineer Associate**  
  https://learn.microsoft.com/credentials/certifications/azure-security-engineer/

- **SC-100 – Microsoft Cybersecurity Architect**  
  https://learn.microsoft.com/credentials/certifications/cybersecurity-architect/

---

### ☁️ Google Cloud
- **Google Professional Cloud Security Engineer**  
  https://cloud.google.com/certification/cloud-security-engineer

---

### 🌍 Vendor Neutral / Multicloud
- **CCSK – Certificate of Cloud Security Knowledge**  
  https://cloudsecurityalliance.org/education/ccsk/

- **CCSP – Certified Cloud Security Professional (ISC2)**  
  https://www.isc2.org/certifications/ccsp

---

## 🔗 Integração com Outras Trilhas

- **SOC / Blue Team** – detecção e resposta em cloud
- **DFIR** – investigação de incidentes cloud
- **AppSec** – segurança de workloads e APIs
- **DevSecOps** – IaC e pipelines
- **GRC** – risco, compliance e governança

---

## 📌 Princípios-Chave de Cloud Security

- IAM é o novo perímetro
- Misconfiguration é o maior risco
- Logs são obrigatórios, não opcionais
- Segurança precisa escalar automaticamente
- Multicloud sem governança vira caos

---
# 📚 Livros Técnicos Essenciais de Cloud Security

Esta lista reúne **livros técnicos amplamente reconhecidos** para quem deseja **entender segurança em nuvem de forma profunda**, indo além de configurações pontuais e cobrindo **arquitetura, identidade, governança, risco e resposta a incidentes**.

São leituras usadas por:
- Cloud Security Engineers
- Cloud Architects
- AppSec em ambientes cloud
- SOC e DFIR com foco em nuvem
- Liderança técnica

---

## 🧱 Fundamentos de Cloud & Arquitetura Segura

### Cloud Security and Privacy
**Autores:** Tim Mather, Subra Kumaraswamy, Shahed Latif  

📌 **Por que é essencial:**  
Livro clássico que estabelece a **base conceitual de segurança em nuvem**.

**Cobre:**
- Modelos de responsabilidade compartilhada
- Riscos de cloud computing
- Identidade, isolamento e governança
- Aspectos legais e de compliance

> Ideal para entender **o porquê das decisões de segurança em cloud**, não só o como.

---

### Designing Secure Cloud Architecture
**Autor:** Michael S. Smith  

📌 **Por que é essencial:**  
Foco direto em **arquitetura segura**, não em ferramentas.

**Cobre:**
- Design seguro em AWS, Azure e GCP
- Segmentação, identidade e logging
- Arquiteturas resilientes e escaláveis
- Threat modeling em cloud

---

## 🔐 Identidade, Controle de Acesso & Zero Trust

### Identity and Data Security for Web Development
**Autor:** Jonathan LeBlanc  

📌 **Por que é relevante:**  
Conecta **identidade, autenticação e autorização** com aplicações modernas em cloud.

**Cobre:**
- IAM moderno
- OAuth, OIDC e tokens
- Autorização em ambientes distribuídos
- Segurança orientada a identidade

---

### Zero Trust Networks
**Autor:** Evan Gilman, Doug Barth  

📌 **Por que é essencial:**  
Base conceitual de **Zero Trust**, extremamente aplicável a cloud.

**Cobre:**
- Identity-first security
- Segmentação lógica
- Aplicação prática de Zero Trust
- Casos reais de adoção

---

## 🌐 Redes, Tráfego & Perímetro em Cloud

### Practical Cloud Security
**Autor:** Chris Dotson  

📌 **Por que é essencial:**  
Livro extremamente prático, focado em **segurança operacional em cloud**.

**Cobre:**
- Network security em cloud
- IAM, logging e monitoramento
- Resposta a incidentes em cloud
- Casos reais e armadilhas comuns

> Excelente ponte entre **Cloud + SOC + DFIR**.

---

### AWS Security
**Autor:** Albert Anthony  

📌 **Por que é relevante:**  
Foco técnico em **segurança aplicada na AWS**, com conceitos reutilizáveis em outras clouds.

**Cobre:**
- IAM e políticas
- Segurança de rede
- Logging e auditoria
- Hardening de serviços

---

## 📊 Governança, Risco & Postura de Segurança

### Cloud Governance
**Autor:** Jeroen Mulder  

📌 **Por que é essencial:**  
Aborda **governança real em ambientes cloud**, não só compliance teórico.

**Cobre:**
- Políticas e padrões
- Gestão de risco
- Controle de custos e segurança
- Cloud em larga escala

---

### Security and Privacy in Cloud Computing
**Autores:** Siani Pearson, George Yee  

📌 **Por que é relevante:**  
Visão acadêmica e estratégica sobre **privacidade, risco e segurança em cloud**.

---

## 🧠 Cloud + Incidentes & DFIR

### Incident Response in the Cloud
**Autor:** Chris Dotson  

📌 **Por que é essencial:**  
Livro focado em **resposta a incidentes especificamente em cloud**.

**Cobre:**
- Logs e evidências em cloud
- Limitações forenses
- Coordenação com SOC e DFIR
- Casos reais de incidentes

---

## 🎯 Como Usar Esta Lista

- 📌 Comece pelos **fundamentos de arquitetura**
- 📌 Aprofunde em **identidade e redes**
- 📌 Avance para **governança e resposta a incidentes**
- 📌 Conecte com **AppSec, SOC e DFIR**

> 💡 Cloud Security não é uma trilha isolada.  
> Ela **cruza identidade, redes, aplicações, logs e risco**.

---

## ⚠️ Observação Importante

Esses livros:
- ❌ não são rápidos
- ❌ não são tutoriais passo a passo
- ❌ não prometem atalhos

Mas:
- ✅ formam base sólida
- ✅ explicam decisões arquiteturais
- ✅ diferenciam profissionais seniores

---

> Cloud muda rápido.  
> **Fundamentos bons duram décadas.**

