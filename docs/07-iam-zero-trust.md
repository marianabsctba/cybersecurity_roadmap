# 🔐 IAM & Zero Trust

Esta trilha cobre **Gestão de Identidades e Acessos (IAM)** e **Arquiteturas Zero Trust**, com foco em **controle de identidade, autenticação forte, autorização granular e governança de acessos** em ambientes **on-premises, cloud e híbridos**.

> 🔎 **Identidade é o novo perímetro.**  
> Zero Trust não é produto: é **modelo arquitetural baseado em identidade, contexto e verificação contínua**.

---

## 👥 Carreiras

- **IAM Analyst**  
  Atua na operação, suporte e análise de acessos, identidades, autenticações e eventos de identidade.

- **IAM Engineer**  
  Implementa soluções de IAM, integra aplicações, define políticas de acesso e automatiza ciclos de vida.

- **Identity / Zero Trust Architect**  
  Desenha arquiteturas de identidade, governança e Zero Trust, alinhadas a risco, negócio e compliance.

---

## 🧠 Habilidades Técnicas Essenciais

### 🔑 Single Sign-On (SSO)
- Centralização de autenticação
- Redução de credenciais
- Integração com aplicações SaaS e on-prem
- Melhoria de experiência do usuário (UX)

Protocolos:
- **SAML 2.0**
- **OAuth 2.0**
- **OpenID Connect (OIDC)**

---

### 🔐 Multi-Factor Authentication (MFA)
- Fatores de autenticação:
  - Algo que você sabe
  - Algo que você tem
  - Algo que você é
- MFA adaptativo
- MFA resistente a phishing
- Passwordless

---

### 🌐 Federation
- Trust entre domínios
- Integração entre provedores de identidade
- Identidade híbrida (on-prem + cloud)
- B2B e B2C Identity

---

### 🧠 Conditional Access
- Políticas baseadas em:
  - Identidade
  - Dispositivo
  - Localização
  - Risco
- Avaliação contínua
- Resposta dinâmica (step-up auth)

---

### 🛡️ Privileged Access Management (PAM)
- Proteção de contas privilegiadas
- Just-In-Time (JIT) access
- Session recording
- Segregação de funções (SoD)
- Auditoria de acessos críticos

---

## 🧱 Zero Trust (Arquitetura)

### Princípios Fundamentais
- **Nunca confie, sempre verifique**
- Menor privilégio
- Avaliação contínua
- Assumir violação

### Componentes
- Identidade
- Dispositivo
- Aplicação
- Rede
- Dados

### Frameworks de Referência
- **NIST SP 800-207 – Zero Trust Architecture**  
  https://csrc.nist.gov/publications/detail/sp/800-207/final

- **CISA Zero Trust Maturity Model**  
  https://www.cisa.gov/zero-trust-maturity-model

---

## 🧪 Labs Práticos (IAM & Zero Trust)

> IAM **se aprende configurando identidades reais e quebrando acessos indevidos**.

### Plataformas de Labs
- **Microsoft Learn – Identity & Access Labs**  
  https://learn.microsoft.com/training/

- **TryHackMe – Active Directory & IAM Labs**  
  https://tryhackme.com/

- **Azure AD / Entra ID Labs (Free Tier)**  
  https://learn.microsoft.com/entra/

- **AWS IAM Hands-On Labs**  
  https://aws.amazon.com/training/

- **Keycloak Playground (Local / Docker)**  
  https://www.keycloak.org/getting-started/

---

## 📘 Cursos Oficiais (Formação)

### Identidade & Zero Trust
- **Microsoft SC-300 Learning Path (Identity and Access Administrator)**  
  https://learn.microsoft.com/training/paths/implement-identity-access-management/

- **NIST Zero Trust Architecture (Study Resources)**  
  https://csrc.nist.gov/projects/zero-trust-architecture

---

### Cloud & IAM
- **AWS IAM & Security Fundamentals**  
  https://aws.amazon.com/training/digital/aws-security-fundamentals/

- **Google Cloud Identity Training**  
  https://cloud.google.com/identity/docs

- **Cloud Security Alliance – Zero Trust & IAM Training**  
  https://cloudsecurityalliance.org/education/

---

## 🧰 Ferramentas Open Source Importantes

### IAM / Identity
- **Keycloak** – https://www.keycloak.org/
- **Gluu Server** – https://gluu.org/
- **Authelia** – https://www.authelia.com/
- **Dex (OIDC)** – https://dexidp.io/

---

### PAM / Privileged Access
- **Teleport (Community Edition)**  
  https://goteleport.com/

- **HashiCorp Vault (Community)**  
  https://www.vaultproject.io/

---

### Policy & Authorization
- **Open Policy Agent (OPA)**  
  https://www.openpolicyagent.org/

- **OPA Gatekeeper**  
  https://github.com/open-policy-agent/gatekeeper

---

## 🏅 Certificações (Validação de Conhecimento)

### IAM / Zero Trust
- **SC-300 – Microsoft Identity and Access Administrator**  
  https://learn.microsoft.com/credentials/certifications/identity-and-access-administrator/

- **CCSP – Certified Cloud Security Professional (ISC2)**  
  https://www.isc2.org/certifications/ccsp

- **CISSP – Certified Information Systems Security Professional**  
  https://www.isc2.org/certifications/cissp

---

### Complementares Relevantes
- **AZ-500 – Azure Security Engineer**  
  https://learn.microsoft.com/credentials/certifications/azure-security-engineer/

- **AWS Certified Security – Specialty**  
  https://aws.amazon.com/certification/certified-security-specialty/

---

## 🔗 Integração com Outras Trilhas

- **Cloud Security** – identidade como perímetro
- **DevSecOps / Kubernetes** – service identity e workload identity
- **SOC / Blue Team** – detecção de abuso de identidade
- **DFIR** – investigação de compromissos de contas
- **GRC** – compliance, auditoria e risco

---

## 📌 Princípios-Chave de IAM & Zero Trust

- Identidade vem antes da rede
- MFA é obrigatório, não opcional
- Acesso deve ser **contextual**
- Privilégio permanente é risco
- Zero Trust é jornada, não produto

---
