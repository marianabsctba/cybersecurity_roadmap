# 🟩 Application Security (AppSec)

> **Segurança de aplicações do design ao runtime**

Esta trilha aborda **segurança de aplicações ponta a ponta**, cobrindo **Secure SDLC**, **segurança de código**, **pipelines CI/CD**, **testes automatizados**, **modelagem de ameaças** e **proteção em runtime**, com foco em **reduzir risco antes, durante e depois do deploy**.

AppSec existe para **evitar que vulnerabilidades cheguem à produção** — e, quando chegam, garantir que o impacto seja mínimo.

---

## 👥 Carreiras em AppSec

- **AppSec Engineer**
- **Product Security Engineer**
- **AppSec Lead**

> 🧠 AppSec atua como **ponte entre desenvolvimento, segurança e negócio**.  
> Não é “time do não”, é **time do código seguro e do design correto**.

---

## 🧠 Habilidades Técnicas Essenciais

### 🛡️ Secure SDLC (Base de Tudo)
- Requisitos de segurança
- Design seguro
- Threat Modeling
- Gates de segurança
- Segurança contínua em produção

> Segurança não entra no final.  
> **Segurança nasce no design.**

---

### ⚠️ OWASP & Classes de Ameaça

| Domínio | O que cobre |
|------|-----------|
| OWASP Top 10 (Web) | Vulnerabilidades clássicas de aplicações web |
| OWASP API Top 10 | Falhas de autorização, lógica e exposição em APIs |
| OWASP Mobile Top 10 | Segurança em apps móveis |
| CWE Top 25 | Erros comuns de programação |
| MITRE ATT&CK | Correlação quando aplicável |

---

### 🔍 Code Review Seguro
- Revisão manual de código
- Análise de lógica e fluxo
- Sanitização e validação de entrada
- Autorização e controle de acesso

> Muitas falhas **não são detectáveis por ferramenta**.  
> Elas vivem na **lógica de negócio**.

---

### 🧠 Threat Modeling
- STRIDE
- DREAD
- PASTA
- Modelagem baseada em fluxo e ativos
- Documentação viva

---

## 🔐 API Security (Parte Central de AppSec)

APIs **são aplicações** — e hoje concentram **os maiores riscos modernos**.

API Security não é apenas testar endpoints.  
É garantir que **autenticação, autorização e lógica de negócio** estejam corretas **desde o design**.

### Principais riscos em APIs
- Broken Object Level Authorization (BOLA)
- Broken Function Level Authorization (BFLA)
- Excessive Data Exposure
- Falhas de rate limiting
- Abuso de lógica e automação maliciosa

> 📌 **Importante**  
> API Security **nasce em AppSec**.  
> Blue Team entra depois, monitorando e respondendo a abuso.

---

## 🔄 AppSec Lifecycle – Segurança de Código

> Cada técnica cobre **uma parte do risco**.  
> Nenhuma é suficiente sozinha.

---

### 🔎 SAST – Static Application Security Testing
Análise de código-fonte sem executar a aplicação.

**Ferramentas open source:**
- Semgrep – https://semgrep.dev/
- Bandit (Python) – https://github.com/PyCQA/bandit
- FindSecBugs (Java) – https://find-sec-bugs.github.io/
- Brakeman (Ruby) – https://brakemanscanner.org/
- Psalm (PHP) – https://psalm.dev/

---

### 🌐 DAST – Dynamic Application Security Testing
Testes com a aplicação em execução.

**Ferramentas open source:**
- OWASP ZAP – https://www.zaproxy.org/
- Nikto – https://github.com/sullo/nikto
- w3af – https://github.com/andresriancho/w3af

---

### 🧬 IAST – Interactive Application Security Testing
Instrumentação da aplicação durante execução.

- Predominantemente comercial
- Uso comum: integração com APM + testes

---

### 📱 MAST – Mobile Application Security Testing

**Ferramentas open source:**
- MobSF – https://github.com/MobSF/Mobile-Security-Framework-MobSF
- Drozer – https://github.com/WithSecureLabs/drozer

---

### 🔗 API Security – Testes Técnicos

**Ferramentas open source:**
- OWASP Amass (enumeração) – https://github.com/owasp-amass
- OWASP ZAP API Scan
- Postman + scripts
- Schemathesis – https://schemathesis.readthedocs.io/

---

### 📦 SCA – Software Composition Analysis
Análise de dependências e bibliotecas.

**Ferramentas open source:**
- OWASP Dependency-Check – https://owasp.org/www-project-dependency-check/
- Trivy – https://github.com/aquasecurity/trivy
- Syft – https://github.com/anchore/syft
- Grype – https://github.com/anchore/grype

---

### ☁️ IaC Security (Infrastructure as Code)

**Ferramentas open source:**
- Checkov – https://github.com/bridgecrewio/checkov
- Terrascan – https://github.com/accurics/terrascan
- KICS – https://github.com/Checkmarx/kics
- tfsec – https://github.com/aquasecurity/tfsec

---

### 🔑 Secrets Detection
Detecção de chaves e segredos no código.

**Ferramentas open source:**
- Gitleaks – https://github.com/gitleaks/gitleaks
- TruffleHog – https://github.com/trufflesecurity/trufflehog

---

## 🧪 Labs Práticos (Essenciais)

> AppSec **se aprende quebrando aplicação e corrigindo código**.

- PortSwigger Web Security Academy  
  https://portswigger.net/web-security

- OWASP Juice Shop  
  https://owasp.org/www-project-juice-shop/

- TryHackMe – AppSec / Web Paths  
  https://tryhackme.com/

- Hack The Box Academy – Web & AppSec  
  https://academy.hackthebox.com/

- Secure Code Warrior Labs  
  https://securecodewarrior.com/

- OWASP WebGoat  
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
- DevSecOps Foundation (DOFD)  
  https://devopsinstitute.com/certifications/devsecops-foundation/
- Microsoft Secure DevOps  
  https://learn.microsoft.com/training/paths/secure-devops/
- AWS DevSecOps Learning Path  
  https://aws.amazon.com/training/devsecops/

---

## 🏅 Certificações

- CSSLP – ISC2  
- GWAPT – GIAC  
- OSWE – Offensive Security  
- CASE Java / .NET – EC-Council  

---

## 🔗 Integração com Outras Trilhas

- DevOps / Cloud → pipelines e runtime
- SOC / Blue Team → detecção e abuso
- DFIR → resposta a incidentes de aplicação
- GRC → requisitos, risco e compliance

---

## 📌 Princípios-Chave de AppSec

- Segurança começa no design
- Código inseguro escala rápido
- Automação sem contexto falha
- AppSec é contínuo, não projeto
- Quem escreve código participa da segurança
