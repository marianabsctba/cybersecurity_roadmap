# 🟥 Red Team & Pentest

Esta trilha cobre **testes de intrusão, simulação de adversários e operações ofensivas**, com foco em **descoberta de falhas reais, exploração, pós-exploração e evasão**, sempre com **escopo autorizado**.

> 🔴 **Pentest** valida *falhas técnicas* em um escopo definido.  
> 🔴 **Red Team** valida *capacidade de detecção, resposta e resiliência* contra um objetivo.  

Red Team **não é ferramenta**: é **método, processo e disciplina**.

---

## 🧭 Red Team × Pentest (diferença conceitual)

### 🔍 Pentest (Penetration Test)
- Escopo **bem definido**
- Tempo limitado
- Objetivo: **encontrar e provar vulnerabilidades**
- Resultado: **relatório técnico com evidências**
- Foco: **aplicação, sistema, rede ou ativo específico**

### 🎯 Red Team
- Escopo **orientado a objetivos**
- Pode ser **covert / semi-covert**
- Objetivo: **simular adversário e medir detecção/resposta**
- Resultado: **lições operacionais + gaps de processo/telemetria/decisão**
- Foco: **organização como um todo (pessoas + processos + tecnologia)**

---

## 🧩 Tipos de Pentest (de Web até Hardware Hacking)

Pentest não é “um tipo só”. Aqui estão os principais:

### 🌐 Pentest Web
- OWASP Top 10
- Falhas lógicas, autenticação/autorização, sessão
- XSS, SQLi, CSRF, SSRF, deserialização, IDOR

### 🔗 Pentest de API (REST/GraphQL)
- OWASP API Top 10
- BOLA/BFLA, rate limit, auth, abuse de lógica
- Broken object/property level authorization

### 🖥️ Pentest de Infraestrutura (externo/interno)
- Serviços expostos, VPN, AD-adjacent, segmentação
- Enumeração, exploração, pivoting, movement

### 🪪 Pentest Active Directory
- Enumeração, trusts, delegações, ACLs
- Kerberoasting/AS-REP, paths e abuso de privilégios

### ☁️ Pentest Cloud (AWS/Azure/GCP)
- IAM como perímetro
- storage exposto, permissões excessivas, identity attacks
- misconfig e abuso de serviços

### 📱 Pentest Mobile (Android/iOS)
- armazenamento inseguro, bypass, hardcoded secrets
- instrumentação e interceptação de tráfego

### 🧠 Pentest de Engenharia Social
- phishing/vishing/pretexting
- avaliação de controle humano e processos

> sempre com **autorização formal e jurídica**.

### 🏭 Pentest OT / ICS
- protocolos industriais (ex.: Modbus/DNP3/IEC)
- impacto físico/operacional e continuidade

### 🔌 Pentest IoT
- firmware, boot chain, interfaces expostas
- protocolos fracos e credenciais padrão

### 🧠 Hardware Hacking (especializado)
- UART/JTAG, dump e análise de firmware
- side-channel e análise física

Ferramentas típicas:
- logic analyzer, Bus Pirate, ChipWhisperer

---

## 👥 Progressão de Carreira

- Pentester Jr  
- Pentester  
- Red Team Operator  
- Exploit Developer  

> A progressão não é linear. Muitos profissionais alternam entre **pentest tradicional**, **red team** e **especializações** (AD, Web, Exploit Dev).

---

## 🧠 Habilidades Técnicas Essenciais

### 🔍 Enumeração & Reconhecimento
- Reconhecimento passivo e ativo
- Enumeração de rede, web e identidade
- Descoberta de superfície de ataque

Ferramentas open source:
- `nmap`, `masscan`
- `amass`, `dnsx`
- `whatweb`, `httpx`
- `enum4linux`, `ldapsearch`

---

### 💥 Exploração
- Exploração de CVEs e falhas lógicas
- Exploração web e infraestrutura
- Uso manual de exploits

Ferramentas:
- `metasploit`
- `sqlmap`
- `ffuf`, `wfuzz`
- `nikto`
- `nuclei`
- `searchsploit`

---

### 🪪 Active Directory
- Enumeração de AD
- Abuso de permissões e delegações
- Kerberoasting / AS-REP Roasting
- Lateral movement

Ferramentas:
- `BloodHound` / `SharpHound`
- `NetExec`
- `CrackMapExec`
- `Impacket`
- `Rubeus`
- `Mimikatz`
- `Responder`

---

### 🔓 Pós-Exploração
- Escalada de privilégios
- Persistência
- Pivoting e tunelamento
- Exfiltração controlada

Ferramentas:
- `linpeas` / `winpeas`
- `pspy`
- `chisel`
- `ligolo-ng`
- `netcat`

---

### 🕵️‍♂️ Evasão & OPSEC
- Evasão de AV/EDR
- Living Off the Land (LOLBins)
- Payload obfuscation
- Controle de ruído operacional

Ferramentas:
- `Sliver`
- `Covenant`
- `Mythic`
- `PowerSploit`
- `Donut`
- `ScareCrow`

---

### 🧬 Exploit Development (Avançado)
- Análise de binários
- Buffer overflow e heap
- Bypass de mitigações (ASLR, DEP)

Ferramentas:
- `Ghidra`
- `radare2`
- `pwntools`
- `pwndbg`
- `gef`

---

## 🧰 Fabricantes e Plataformas Usadas em Red Team (Mercado)

> Red Team “de verdade” normalmente envolve **infraestrutura**, **canais controlados**, **simulação de adversário** e **validação operacional**.  
> Abaixo estão **plataformas amplamente usadas** (comerciais) e onde elas entram.

### 🛰️ Adversary Emulation / Breach & Attack Simulation (BAS)
- **Picus Security** — validação contínua de controles via simulação (BAS)
- **AttackIQ** — emulação de TTPs e validação de defesa
- **SafeBreach** — simulação e verificação contínua de controles
- **XM Cyber** — foco forte em exposição e caminhos de ataque (attack path management)

### 🎯 External Attack Surface Management (EASM) / Exposure
- **SOCRadar** — ASM + inteligência de exposição (inclui DRP/brand monitoring em alguns pacotes)
- **Tenable** — Attack Surface / Exposure Management (dependendo do portfólio e módulos)
- **Rapid7** — exposição + VM (conforme stack)
- **Microsoft Defender EASM** — visão de superfície externa (ecossistema MS)

### 🧑‍💻 Pentest / Reporting / Gestão de Evidências
- **Pentera** — automação de validação ofensiva em ambientes corporativos (mais “security validation”)
- **Cobalt** — pentest sob demanda (plataforma + rede de testers)
- **Synack** — plataforma de testes com rede de pesquisadores (modelo gerenciado)
- **Horizon3.ai** — automação ofensiva com foco em validação

### 🧠 AppSec (suporte ao ofensivo em Web/API)
- **Burp Suite Professional (PortSwigger)** — padrão de mercado em pentest web
- **Invicti (Netsparker)** — DAST comercial
- **Acunetix** — DAST comercial (muito usado em VA/pentest web)
- **Contrast Security** — IAST / RASP (segurança “dentro” da app em execução)

---

## 📐 Métodos e Frameworks de Pentest

Pentest **profissional** segue metodologia. Framework ≠ burocracia.

### Metodologias Reconhecidas
- **PTES – Penetration Testing Execution Standard**  
  https://www.pentest-standard.org/  

- **NIST SP 800-115 – Technical Guide to Information Security Testing**  
  https://csrc.nist.gov/publications/detail/sp/800-115/final  

- **OSSTMM – Open Source Security Testing Methodology Manual**  
  https://www.isecom.org/OSSTMM.3.pdf  

---

### Frameworks Específicos
- **OWASP Web Security Testing Guide (WSTG)**  
  https://owasp.org/www-project-web-security-testing-guide/

- **OWASP API Security Top 10**  
  https://owasp.org/www-project-api-security/

- **MITRE ATT&CK** (para Red Team / Adversary Emulation)  
  https://attack.mitre.org/

---

## 📘 Cursos e Formação (Ofensivo)

### Pentest / Red Team
- **DESEC – Formação Pentest Profissional**  
  https://desecsecurity.com/

- **Offensive Security – Training Catalog**  
  https://www.offsec.com/courses/

- **Pentester Academy / INE**  
  https://ine.com/learning/paths/penetration-testing

- **PortSwigger Web Security Academy (Gratuito)**  
  https://portswigger.net/web-security

- **RedScan Academy**  
  https://redscanacademy.mindz.com.br/ 

---

### Active Directory / Red Team
- **TryHackMe – Red Team & AD Paths**  
  https://tryhackme.com/

- **Hack The Box Academy – AD & Red Team**  
  https://academy.hackthebox.com/

---

### Exploit Development
- **OpenSecurityTraining**  
  https://opensecuritytraining.info/

- **LiveOverflow – Binary Exploitation**  
  https://www.youtube.com/c/LiveOverflow

---

## 🧪 Labs Práticos (Ofensivos)

> Pentest se aprende **quebrando laboratório**, não só lendo PDF.

- **Hack The Box (HTB)**  
  https://www.hackthebox.com/

- **Hack The Box Academy**  
  https://academy.hackthebox.com/

- **TryHackMe**  
  https://tryhackme.com/

- **PentesterLab**  
  https://pentesterlab.com/

- **VulnHub (VMs locais)**  
  https://www.vulnhub.com/

---

## 🏅 Certificações (Validação de Conhecimento)

### 🔰 Entry / Intermediate (Pentest e Red Team)
- **CompTIA PenTest+**  
  https://www.comptia.org/certifications/pentest  

- **DESEC Pentest Certified (DPCT)**  
  https://desecsecurity.com/certificacoes/  

- **eJPT – Junior Penetration Tester**  
  https://elearnsecurity.com/product/ejpt-certification/  

- **PNPT – Practical Network Penetration Tester (TCM Security)**  
  https://certifications.tcm-sec.com/pnpt/  

- **CEH – Certified Ethical Hacker**  
  https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/  

- **GPEN – GIAC Penetration Tester**  
  https://www.giac.org/certifications/penetration-tester-gpen/  

---

### 🔥 Advanced (Red Team / Exploit / Web / Infra)
- **OSCP – Offensive Security Certified Professional**  
  https://www.offsec.com/certifications/oscp/

- **OSWA – Offensive Security Web Assessor**  
  https://www.offsec.com/certifications/oswa/

- **OSWE – Offensive Security Web Expert**  
  https://www.offsec.com/certifications/oswe/

- **OSEP – Offensive Security Experienced Pentester**  
  https://www.offsec.com/certifications/osep/

- **OSED – Offensive Security Exploit Developer**  
  https://www.offsec.com/certifications/osed/

- **GXPN – GIAC Exploit Researcher and Advanced Penetration Tester**  
  https://www.giac.org/certifications/exploit-researcher-gxpn/

- **CREST CRT / CCT**  
  https://www.crest-approved.org/  

---

### 📌 Outras Certificações Relevantes (Contexto Pentest)
- **CompTIA Security+**  
  https://www.comptia.org/certifications/security  

- **CompTIA CySA+**  
  https://www.comptia.org/certifications/cysa  

---

## 📌 Observações Importantes
- Certificações práticas (OSCP, PNPT, DPC) tendem a ter **peso maior** que teóricas.  
- Certificação **não substitui lab** — mas valida método, ética e maturidade.

---

## 🔗 Integração com Outras Trilhas
- **Purple Team** – validação de detecção
- **Blue Team / SOC** – melhoria de alertas
- **AppSec** – correções estruturais
- **CTI** – simulação de adversários reais
- **GRC / Jurídico** – escopo, ética e autorização

---

## 📌 Princípios-Chave da Trilha Red Team
- Ferramenta não substitui técnica  
- Enumeração vale mais que exploit  
- OPSEC é parte do ataque  
- Relatório é tão importante quanto o acesso  
- Red Team bom **eleva o Blue Team**

---

# 📚 Offensive Security – Livros Essenciais

Lista curada de livros **clássicos e amplamente reconhecidos** em **Offensive Security**, Pentest, Red Team, Exploit Development e Malware Analysis.

---

## 🧱 Fundamentos de Offensive Security

### The Web Application Hacker’s Handbook  
**Autores:** Dafydd Stuttard, Marcus Pinto  
**Foco:** Pentest Web  

---

### Hacking: The Art of Exploitation  
**Autor:** Jon Erickson  
**Foco:** Exploração de baixo nível  

---

## 🔴 Pentest & Red Team (Operação Real)

### Metasploit: The Penetration Tester’s Guide  
**Autores:** David Kennedy et al.  
**Foco:** Exploração com Metasploit  

---

### Red Team Field Manual (RTFM)  
**Autor:** Ben Clark  
**Foco:** Red Team operacional  

---

### The Hacker Playbook (Volumes 1, 2 e 3)  
**Autor:** Peter Kim  
**Foco:** Pentest e Red Team corporativo  

---

## 🦠 Malware, Reverse Engineering & Exploit Dev

### Practical Malware Analysis  
**Autores:** Michael Sikorski, Andrew Honig  
**Foco:** Análise de malware  

---

### The Shellcoder’s Handbook  
**Autores:** Chris Anley et al.  
**Foco:** Exploit development avançado  

---

## 🧠 Mentalidade Ofensiva & Engenharia Social

### Ghost in the Wires  
**Autor:** Kevin Mitnick  
**Foco:** Engenharia social e mindset  

---

### The Cuckoo’s Egg  
**Autor:** Clifford Stoll  
**Foco:** história e investigação de intrusão  

---

# 🔴 Offensive Security – Canais Essenciais (Pentest & Red Team)

### Daniel Donda
YouTube: https://www.youtube.com/@DanielDonda

### Penegui
YouTube: https://www.youtube.com/@penegui

### Prof. Julio Della Flora
YouTube: https://www.youtube.com/@HardwareHacking

### Gabriel Pato
YouTube: https://www.youtube.com/@gabrielpato
