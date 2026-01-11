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

## 🧩 Fabricantes & Plataformas (AppSec no mercado)

> AppSec “no mundo real” costuma ser um **stack** (não um produto único).  
> Abaixo estão **fabricantes e plataformas amplamente usados**, por domínio.

### 🧬 SAST (Static Application Security Testing)
- **Snyk Code** — SAST integrado ao fluxo de dev
- **Checkmarx** — SAST enterprise
- **Veracode** — SAST + políticas/gestão
- **SonarSource (SonarQube/SonarCloud)** — qualidade + security rules (muito usado em SDLC)

### 🌐 DAST (Dynamic Application Security Testing)
- **Invicti (Netsparker)** — DAST web comercial
- **Acunetix** — DAST web comercial
- **Rapid7 InsightAppSec** — DAST + integração com pipeline
- **Burp Suite Professional (PortSwigger)** — padrão de mercado para testes manuais (apoia DAST “humano”)

### 🧬 IAST (Interactive Application Security Testing) — *Comerciais (exemplos reais)*
- **Contrast Security (IAST/RASP)** — instrumentação da aplicação + detecção em execução
- **Veracode IAST** — instrumentação e testes durante execução
- **Synopsys Seeker (IAST)** — IAST para apps em execução (linha Seeker)
> IAST costuma entrar quando você quer **achar falhas em runtime** com contexto de código e requisição.

### 📦 SCA (Software Composition Analysis) / Dependências
- **Snyk Open Source** — SCA + priorização
- **Mend (WhiteSource)** — SCA enterprise
- **JFrog Xray** — SCA na cadeia de artefatos
- **Sonatype Nexus Lifecycle** — SCA + governança de dependências

### 🔑 Secrets & Exposure (segredos e vazamentos)
- **GitGuardian** — detecção de secrets e vazamentos em repos
- **Truffle Security (TruffleHog)** — detecção de secrets (muito usado em pipelines)

### ☁️ IaC Security (Terraform/K8s manifests/policy)
- **Snyk IaC** — IaC scanning
- **Palo Alto Prisma Cloud** — IaC + CNAPP (stack cloud)
- **Wiz** — posture/exposure (stack cloud)
- **Checkmarx / Bridgecrew (Checkov)** — muito usado em IaC scanning (via Checkov)

### 🔗 WAAP / API Security (proteção e governança de API)
- **Cequence Security** — **API Security** e proteção contra abuso/bots (forte em APIs)
- **Akamai** — WAAP / edge security (dependendo do pacote/arquitetura)
- **Cloudflare** — WAAP e controles para APIs (quando aplicável)
- **F5** — WAF/WAAP e proteção de apps/APIs
> 📌 **API Security nasce em AppSec** (design/autorização/contratos).  
> WAAP/API Gateway/WAF ajudam na **camada de proteção/observabilidade** em produção.

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
- Exemplos comerciais (IAST):
  - Contrast Security – https://www.contrastsecurity.com/
  - Veracode IAST – https://www.veracode.com/
  - Synopsys Seeker – https://www.synopsys.com/software-integrity/security-testing/interactive-application-security-testing.html

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

---

# 📚 Livros Essenciais de Application Security (AppSec)

Esta lista apresenta **livros reconhecidos e amplamente recomendados** para construção de conhecimento profundo em segurança de aplicações, cobrindo desde princípios, design seguro, análise de código, até testes e melhores práticas.

---

## 🧱 Fundamentos e Web/AppSec “raiz”

### The Web Application Hacker’s Handbook  
**Autores:** Dafydd Stuttard & Marcus Pinto  
Clássico para entender ataques web e defesa prática (auth, sessão, injeções, lógica, etc.).

### The Tangled Web  
**Autor:** Michal Zalewski  
Fundamentos de segurança web moderna (browsers, same-origin, sessões, etc.).

---

## 🧠 Threat Modeling (Design seguro)

### Threat Modeling: Designing for Security  
**Autor:** Adam Shostack  
O livro referência para incorporar threat modeling no SDLC.

---

## 🔍 Code Review / Avaliação de software

### The Art of Software Security Assessment  
**Autores:** Mark Dowd, John McDonald & Justin Schuh  
Profundo e técnico para análise de código e identificação de falhas reais.

### Secure Coding in C and C++  
**Autor:** Robert C. Seacord  
Clássico para vulnerabilidades e boas práticas em baixo nível.

---

## 🔗 APIs, Auth e Identidade

### API Security in Action  
**Autor:** Neil Madden  
Excelente para segurança real de APIs (authn/authz, tokens, JWT, práticas modernas).

### OAuth 2 in Action  
**Autores:** Justin Richer & Antonio Sanso  
Guia prático e sólido sobre OAuth2 e padrões usados no mundo real.

---

## 🏗️ Engenharia de segurança aplicada (base “senior”)

### Security Engineering: A Guide to Building Dependable Distributed Systems  
**Autor:** Ross Anderson  
Livro gigante e fundamental para pensamento de segurança em sistemas distribuídos.

---

## 🧪 Bug bounty / mundo real (complementar)

### Real-World Bug Hunting  
**Autor:** Peter Yaworski  
Casos reais que ajudam a treinar o olhar para falhas que passam em checklist.

---
