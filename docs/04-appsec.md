# 🟩 Application Security (AppSec)

Esta trilha aborda **segurança de aplicações ponta a ponta**, cobrindo **Secure SDLC**, **segurança de código**, **pipelines CI/CD**, **testes automatizados**, **modelagem de ameaças** e **proteção em runtime**, com foco em **reduzir risco antes, durante e depois do deploy**.

---

## 👥 Carreiras

- **AppSec Engineer**
- **Product Security Engineer**
- **AppSec Lead**

> AppSec atua como **ponte entre desenvolvimento, segurança e negócio**.  
> Não é “time do não”, é **time do código seguro**.

---

## 🧠 Habilidades Técnicas Essenciais

### 🛡️ Secure SDLC
- Requisitos de segurança
- Design seguro
- Threat Modeling
- Gates de segurança
- Segurança contínua em produção

---

### ⚠️ OWASP & Classes de Ameaça
- OWASP Top 10 (Web)
- OWASP API Top 10
- OWASP Mobile Top 10
- CWE Top 25
- Mapeamento para MITRE ATT&CK (quando aplicável)

---

### 🔍 Code Review Seguro
- Revisão manual de código
- Análise de lógica e fluxo
- Sanitização e validação de entrada
- Autorização e controle de acesso

---

### 🧠 Threat Modeling
- STRIDE
- DREAD
- PASTA
- Modelagem baseada em fluxo e ativos
- Documentação viva

---

## 🔄 Fases de Segurança de Código (AppSec Lifecycle)

### 🔎 SAST – Static Application Security Testing
Análise de código-fonte sem executar a aplicação.

Ferramentas open source:
- **Semgrep** – https://semgrep.dev/
- **Bandit (Python)** – https://github.com/PyCQA/bandit
- **FindSecBugs (Java)** – https://find-sec-bugs.github.io/
- **Brakeman (Ruby)** – https://brakemanscanner.org/
- **Psalm (PHP)** – https://psalm.dev/

---

### 🌐 DAST – Dynamic Application Security Testing
Testes com a aplicação em execução.

Ferramentas open source:
- **OWASP ZAP** – https://www.zaproxy.org/
- **Nikto** – https://github.com/sullo/nikto
- **w3af** – https://github.com/andresriancho/w3af

---

### 🧬 IAST – Interactive Application Security Testing
Instrumentação da aplicação durante execução.

Ferramentas:
- *(predominantemente comerciais; open source limitado)*
- Uso comum: integração com APM + testes

---

### 📱 MAST – Mobile Application Security Testing
Segurança de aplicações móveis.

Ferramentas open source:
- **MobSF** – https://github.com/MobSF/Mobile-Security-Framework-MobSF
- **Drozer** – https://github.com/WithSecureLabs/drozer

---

### 🔗 API Security
Testes e validação de APIs REST/GraphQL.

Ferramentas open source:
- **OWASP Amass (enumeração)** – https://github.com/owasp-amass
- **OWASP ZAP API Scan**
- **Postman + scripts**
- **Schemathesis** – https://schemathesis.readthedocs.io/

---

### 📦 SCA – Software Composition Analysis
Análise de dependências e bibliotecas.

Ferramentas open source:
- **OWASP Dependency-Check** – https://owasp.org/www-project-dependency-check/
- **Trivy** – https://github.com/aquasecurity/trivy
- **Syft** – https://github.com/anchore/syft
- **Grype** – https://github.com/anchore/grype

---

### ☁️ IaC Security (Infrastructure as Code)
Segurança de Terraform, CloudFormation, Kubernetes etc.

Ferramentas open source:
- **Checkov** – https://github.com/bridgecrewio/checkov
- **Terrascan** – https://github.com/accurics/terrascan
- **KICS** – https://github.com/Checkmarx/kics
- **tfsec** – https://github.com/aquasecurity/tfsec

---

### 🔑 Secrets Detection
Detecção de chaves e segredos no código.

Ferramentas open source:
- **Gitleaks** – https://github.com/gitleaks/gitleaks
- **TruffleHog** – https://github.com/trufflesecurity/trufflehog

---

## 🧪 Labs Práticos (Essenciais para AppSec)

> AppSec **se aprende quebrando aplicação e corrigindo código**.

### Plataformas de Labs
- **PortSwigger Web Security Academy (gratuito)**  
  https://portswigger.net/web-security

- **OWASP Juice Shop**  
  https://owasp.org/www-project-juice-shop/

- **TryHackMe – AppSec / Web Paths**  
  https://tryhackme.com/

- **Hack The Box Academy – Web & AppSec**  
  https://academy.hackthebox.com/

- **Secure Code Warrior Labs**  
  https://securecodewarrior.com/

- **OWASP WebGoat**  
  https://owasp.org/www-project-webgoat/

---

## 📘 Cursos e Recursos Oficiais

### OWASP
- OWASP Top 10  
  https://owasp.org/www-project-top-ten/
- OWASP ASVS  
  https://owasp.org/www-project-application-security-verification-standard/
- OWASP WSTG  
  https://owasp.org/www-project-web-security-testing-guide/

---

### DevSecOps / AppSec
- **DevSecOps Foundation (DOFD)**  
  https://devopsinstitute.com/certifications/devsecops-foundation/

- **Microsoft Secure DevOps**  
  https://learn.microsoft.com/training/paths/secure-devops/

- **AWS DevSecOps Learning Path**  
  https://aws.amazon.com/training/devsecops/

---

## 🏅 Certificações

### AppSec / Secure Coding
- **CSSLP – ISC2**  
  https://www.isc2.org/certifications/CSSLP

- **GWAPT – GIAC Web App Pentest**  
  https://www.giac.org/certifications/web-application-penetration-tester-gwapt/

- **OSWE – Offensive Security Web Expert**  
  https://www.offsec.com/certifications/oswe/

- **CASE Java – EC-Council**  
  https://www.eccouncil.org/train-certify/certified-application-security-engineer-java-case-java/

- **CASE .NET – EC-Council**  
  https://www.eccouncil.org/train-certify/certified-application-security-engineer-net-case-dot-net/

---

## 🔗 Integração com Outras Trilhas

- **DevOps / Cloud** – pipelines e runtime
- **SOC / Blue Team** – detecção em produção
- **DFIR** – análise de incidentes de aplicação
- **GRC** – requisitos e compliance

---

## 📌 Princípios-Chave de AppSec

- Segurança começa no design
- Código inseguro escala rápido
- Automação sem contexto falha
- AppSec é contínuo, não projeto
- Quem escreve código participa da segurança

---
