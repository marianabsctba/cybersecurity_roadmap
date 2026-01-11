# 🟥 Red Team / Pentest

Esta trilha cobre **testes de intrusão, simulação de adversários e operações ofensivas**, com foco em **descoberta de falhas reais, exploração, pós-exploração e evasão**, sempre com **escopo autorizado**.

Red Team **não é ferramenta**: é **método, processo e disciplina**.

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

## 📐 Métodos e Frameworks de Pentest

Pentest **profissional** segue metodologia. Framework ≠ burocracia.

### Metodologias Reconhecidas
- **PTES – Penetration Testing Execution Standard**  
  https://www.pentest-standard.org/  
  > Planejamento → Enumeração → Exploração → Pós-exploração → Relatório.

- **NIST SP 800-115 – Technical Guide to Information Security Testing**  
  https://csrc.nist.gov/publications/detail/sp/800-115/final  
  > Guia técnico amplamente usado em ambientes regulados.

- **OSSTMM – Open Source Security Testing Methodology Manual**  
  https://www.isecom.org/OSSTMM.3.pdf  
  > Metodologia focada em mensuração e controle operacional.

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
  > Formação prática, forte no mercado brasileiro, com foco real em exploração.

- **Offensive Security – Training Catalog**  
  https://www.offsec.com/courses/

- **Pentester Academy / INE**  
  https://ine.com/learning/paths/penetration-testing

- **PortSwigger Web Security Academy (Gratuito)**  
  https://portswigger.net/web-security

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
  > Pentest prático com foco em planejamento, exploração, pós-exploração e relatório.

- **DESEC Pentest Certified (DPC)**  
  https://desecsecurity.com/certificacoes/  
  > Certificação prática amplamente reconhecida no Brasil, focada em exploração real.

- **eJPT – Junior Penetration Tester**  
  https://elearnsecurity.com/product/ejpt-certification/  
  > Introdução prática ao pentest de redes e aplicações.

- **PNPT – Practical Network Penetration Tester (TCM Security)**  
  https://certifications.tcm-sec.com/pnpt/  
  > Pentest prático com forte foco em Active Directory e relatório profissional.

- **CEH – Certified Ethical Hacker**  
  https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/  
  > Certificação conceitual e introdutória em hacking ético.

- **GPEN – GIAC Penetration Tester**  
  https://www.giac.org/certifications/penetration-tester-gpen/  
  > Pentest de redes, metodologias e exploração em ambientes corporativos.

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
  > Certificações exigidas em diversos contratos internacionais de Red Team.

---

### 📌 Outras Certificações Relevantes (Contexto Pentest)

- **CompTIA Security+**  
  https://www.comptia.org/certifications/security  
  > Base de segurança que ajuda na leitura de ambientes antes do ataque.

- **CompTIA CySA+**  
  https://www.comptia.org/certifications/cysa  
  > Útil para transição Red ↔ Blue / Purple Team.

---

## 📌 Observações Importantes

- **PenTest+** é a principal certificação **vendor-neutral** de pentest da CompTIA.  
- Certificações práticas (OSCP, PNPT, DPC) têm **peso maior** que teóricas.  
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
