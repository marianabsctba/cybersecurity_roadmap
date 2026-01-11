# 🔐 IAM & Zero Trust

Esta trilha cobre **Gestão de Identidades e Acessos (IAM)** e **Arquiteturas Zero Trust**, com foco em **controle de identidade, autenticação forte, autorização granular, governança de acessos e privilégio**, aplicáveis a ambientes **on-premises, cloud e híbridos**.

> 🔎 **Identidade é o novo perímetro.**  
> Zero Trust não é produto.  
> É um **modelo arquitetural baseado em identidade, contexto, verificação contínua e redução de confiança implícita**.

---

## 👥 Carreiras

- **IAM Analyst**  
  Operação e suporte de identidades, acessos, MFA, SSO, eventos de autenticação e revisões de acesso.

- **IAM Engineer**  
  Implementa soluções de IAM, integra aplicações, automatiza ciclo de vida de identidades, define políticas e governa acessos.

- **Identity / Zero Trust Architect**  
  Desenha **arquiteturas de identidade, acesso e confiança**, alinhando IAM, PAM, dispositivos, aplicações e risco ao negócio.

---

## 🧠 Domínios de Conhecimento Essenciais

### 🔑 Identidade Digital (Base de Tudo)

Antes de ferramenta, é preciso entender **o que é identidade**:

- Identidade humana (usuários)
- Identidade não humana (serviços, APIs, workloads)
- Identidade técnica vs identidade de negócio
- Identidade persistente vs temporária
- Identidade federada

📌 **Erro comum:** tratar IAM como “login e senha”.

---

### 🔑 Single Sign-On (SSO)

SSO **não é só comodidade**, é **controle centralizado**.

- Centralização da autenticação
- Redução de credenciais espalhadas
- Integração com SaaS, aplicações internas e APIs
- Base para auditoria e Zero Trust

**Protocolos fundamentais:**
- **SAML 2.0** (enterprise legado)
- **OAuth 2.0** (delegação de acesso)
- **OpenID Connect (OIDC)** (identidade moderna)

---

### 🔐 Multi-Factor Authentication (MFA)

MFA **mitiga 90%+ dos ataques de credencial**, mas só se bem aplicado.

- MFA clássico vs MFA adaptativo
- MFA resistente a phishing (FIDO2, passkeys)
- Passwordless
- Step-up authentication por risco

📌 MFA mal implementado **vira fricção sem segurança**.

---

### 🌐 Federation & Identidade Híbrida

- Trust entre domínios
- Integração on-prem + cloud
- B2B, B2C e parceiros
- External Identities
- IAM como hub central

📌 Identidade híbrida é regra, não exceção.

---

### 🧠 Conditional Access & Contexto

Zero Trust **vive aqui**.

Políticas baseadas em:
- Identidade
- Dispositivo
- Localização
- Horário
- Postura de segurança
- Risco comportamental

Resultado:
- Allow
- Block
- Step-up MFA
- Sessão restrita

---

### 🛡️ Privileged Access Management (PAM)

PAM protege **o que realmente quebra o ambiente**.

- Contas privilegiadas (humanas e técnicas)
- Just-In-Time (JIT)
- Just-Enough-Access (JEA)
- Session recording
- Segregação de funções (SoD)
- Auditoria e trilha de acesso

📌 **Privilégio permanente = risco permanente.**

---

## 🧱 Zero Trust Architecture

### Princípios Fundamentais
- Nunca confie, sempre verifique
- Menor privilégio
- Avaliação contínua
- Assumir violação
- Explícita verificação

### Pilares do Zero Trust
- Identidade
- Dispositivo
- Aplicação
- Rede
- Dados
- Observabilidade

### Frameworks de Referência
- **NIST SP 800-207 – Zero Trust Architecture**  
  https://csrc.nist.gov/publications/detail/sp/800-207/final

- **CISA Zero Trust Maturity Model**  
  https://www.cisa.gov/zero-trust-maturity-model

📌 Zero Trust **é jornada**, não projeto fechado.

---

## 🧪 Labs Práticos (IAM & Zero Trust)

> IAM só se aprende **errando permissão, quebrando acesso e corrigindo fluxo**.

- Microsoft Learn – Identity & Access  
  https://learn.microsoft.com/training/

- TryHackMe – Active Directory & IAM  
  https://tryhackme.com/

- Azure Entra ID (Free Tier)  
  https://learn.microsoft.com/entra/

- AWS IAM Labs  
  https://aws.amazon.com/training/

- Keycloak Playground (Docker)  
  https://www.keycloak.org/getting-started/

---

## 📘 Cursos Oficiais (Formação)

- Microsoft SC-300 – Identity and Access Administrator  
  https://learn.microsoft.com/training/paths/implement-identity-access-management/

- NIST Zero Trust Architecture – Study Resources  
  https://csrc.nist.gov/projects/zero-trust-architecture

- Cloud Security Alliance – IAM & Zero Trust  
  https://cloudsecurityalliance.org/education/

---

## 🏭 Fabricantes & Plataformas (Exemplos Reais de Mercado)

> Fabricantes **implementam controles**.  
> Arquitetura, processo e identidade **definem segurança**.

---

### 🧩 IAM (Identity Governance & Access)

- **Microsoft Entra ID (Azure AD)**
- **Okta**
- **Ping Identity**
- **ForgeRock**
- **IBM Security Verify**
- **Google Cloud Identity**
- **AWS IAM**
- **ManageEngine IAM Suite**
  - ADSelfService Plus (SSO, MFA, Passwordless)
  - AD360 (IGA)
  - PAM360 (PAM)
  - Identity Manager Plus

📌 **ManageEngine** é muito usado em ambientes híbridos e enterprise por unir **IAM + IGA + PAM**.

---

### 🛡️ PAM (Privileged Access)

- **CyberArk**
- **BeyondTrust**
- **Delinea**
- **ManageEngine PAM360**
- **Wallix**
- **One Identity Safeguard**

---

### 🌐 Zero Trust / Access

- **Zscaler**
- **Cloudflare Zero Trust**
- **Palo Alto Prisma Access**
- **Cisco Duo**
- **Microsoft Entra + Defender**
- **Akamai EAA**

---

### 🔐 Identity Governance (IGA)

- **SailPoint**
- **Saviynt**
- **One Identity**
- **IBM IGA**
- **ManageEngine Identity Manager Plus**

---

## 🧰 Ferramentas Open Source Importantes

### IAM / Identity
- **Keycloak** – https://www.keycloak.org/
- **Gluu Server** – https://gluu.org/
- **Authelia** – https://www.authelia.com/
- **Dex (OIDC)** – https://dexidp.io/

### Policy & Autorização
- **Open Policy Agent (OPA)**  
  https://www.openpolicyagent.org/

---

## 🏅 Certificações

- **SC-300 – Microsoft Identity and Access Administrator**
- **CCSP – ISC2**
- **CISSP – ISC2**
- **AZ-500 – Azure Security Engineer**
- **AWS Security – Specialty**

---

## 🔗 Integração com Outras Trilhas

- **Cloud Security** – identidade como perímetro
- **DevSecOps / Kubernetes** – service & workload identity
- **SOC / Blue Team** – detecção de abuso de identidade
- **DFIR** – investigação de comprometimento de contas
- **GRC** – auditoria, risco e compliance

---

## 📌 Princípios-Chave de IAM & Zero Trust

- Identidade vem antes da rede
- MFA é obrigatório
- Acesso deve ser contextual
- Privilégio permanente é falha de design
- Zero Trust é **arquitetura viva**

> Quem controla identidade, controla o ambiente.
