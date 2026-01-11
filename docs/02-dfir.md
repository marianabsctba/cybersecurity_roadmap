# 🟣 DFIR / Incident Response

> **Quando o alerta vira incidente de verdade**

Esta trilha cobre **Resposta a Incidentes (IR)** e **Forense Digital (DFIR)**, com foco em **investigação técnica, contenção avançada, preservação de evidências e análise pós-incidente**.  
É a evolução natural do SOC quando **detectar não é mais suficiente**.

---

## 👥 Carreiras Associadas

- Incident Responder  
- Digital Forensics Analyst  
- CSIRT Analyst  
- DFIR Lead  

> Em ambientes maduros, DFIR atua **em conjunto com o SOC**, porém com **escopo mais profundo**, técnico, investigativo e jurídico.

---

## 🧠 Habilidades Técnicas Essenciais

### 🚨 Resposta a Incidentes (IR)
- Classificação e severidade de incidentes
- Contenção avançada (endpoint, rede, identidade)
- Preservação inicial de evidências
- Coordenação com SOC, TI, Cloud e Negócio
- Comunicação executiva e técnica
- Lições aprendidas e melhoria contínua

---

### 🧬 Forense Digital
- Coleta forense com preservação de integridade
- Cadeia de custódia
- Forense em:
  - Windows
  - Linux
  - Cloud
- Análise de discos e sistemas de arquivos
- Análise de logs e artefatos do sistema

---

### 🕒 Timeline & Artefatos
- Construção de timelines de eventos
- Correlação de múltiplas fontes:
  - Sistema
  - Segurança
  - Aplicação
  - Rede
- Artefatos comuns:
  - Registry
  - Prefetch
  - Event Logs
  - Browser artifacts

---

### 🧠 Memory Forensics
- Coleta de memória
- Análise de processos, DLLs e injeções
- Detecção de rootkits e malware fileless
- Uso de frameworks como Volatility

---

### 🧪 Malware Triage
- Análise estática básica
- Análise dinâmica controlada
- Extração de indicadores
- Classificação e impacto operacional
- Comunicação com SOC e times correlatos

---

## 📚 Livros Essenciais de DFIR & Incident Response

> Estes livros são **referências reais de mercado**, usados por **times DFIR, CSIRTs, consultorias e SANS**, cobrindo investigação, método e prática.

---

### 🧱 Fundamentos de DFIR (Obrigatórios)

#### Incident Response & Computer Forensics  
**Autores:** Jason T. Luttgens, Matthew Pepe, Kevin Mandia  

📌 **Por que ler:**  
Manual clássico que cobre **IR + Forense** de forma integrada.

**Cobre:**
- Resposta a incidentes estruturada
- Coleta e preservação de evidências
- Forense em sistemas e redes
- Casos reais e metodologia

---

#### The Practice of Network Security Monitoring  
**Autor:** Richard Bejtlich  

📌 **Por que ler:**  
Base conceitual para entender **investigação baseada em evidências de rede**.

**Cobre:**
- Network Security Monitoring (NSM)
- Uso de tráfego como evidência
- Integração SOC → DFIR

---

### 🧠 Forense Avançada

#### The Art of Memory Forensics  
**Autores:** Michael Hale Ligh, Andrew Case, Jamie Levy, AAron Walters  

📌 **Por que ler:**  
Padrão ouro em **forense de memória**.

**Cobre:**
- Dumps de RAM
- Estruturas internas de SO
- Detecção de malware avançado
- Uso profundo do Volatility

---

#### Windows Forensic Analysis  
**Autor:** Harlan Carvey  

📌 **Por que ler:**  
Referência prática para **DFIR em ambientes Windows**.

**Cobre:**
- Registry
- Event Logs
- Artefatos de usuário
- Timeline forensics

---

### 🧪 Investigação Prática & Método

#### File System Forensic Analysis  
**Autor:** Brian Carrier  

📌 **Por que ler:**  
Base técnica para **análise de discos e sistemas de arquivos**.

**Cobre:**
- FAT, NTFS, EXT
- Estruturas internas
- Recuperação de dados
- Evidência em baixo nível

---

#### Blue Team Handbook: Incident Response Edition  
**Autor:** Don Murdoch  

📌 **Por que ler:**  
Livro prático e direto para **resposta sob pressão**.

**Cobre:**
- Playbooks
- Checklists
- Decisão rápida em incidentes

---

### 🧠 Complementares (Malware & Investigação)

#### Practical Malware Analysis  
**Autores:** Michael Sikorski, Andrew Honig  

📌 **Por que ler:**  
Base sólida para **triagem e análise de malware**.

---

## 📘 Cursos e Documentação (Formação)

### 🚨 Incident Response
- **CERT.br – Gestão de Incidentes de Segurança**  
  https://cursoseventos.nic.br/

- **SANS DFIR Whitepapers & Resources**  
  https://www.sans.org/digital-forensics/resources/

---

### 🧬 Forense Digital
- **Autopsy – Training & Documentation**  
  https://www.autopsy.com/support/training/  
  https://www.autopsy.com/support/documentation/

- **Volatility Framework – Official Docs**  
  https://volatilityfoundation.org/

- **The Sleuth Kit – Documentation**  
  https://sleuthkit.org/

---

### ☁️ DFIR em Cloud
- **AWS Security Incident Response Guide**  
  https://docs.aws.amazon.com/whitepapers/latest/aws-security-incident-response-guide/welcome.html

- **Microsoft Incident Response Playbooks**  
  https://learn.microsoft.com/security/incident-response/

---

## 🧪 Labs Práticos (DFIR / IR)

> DFIR **só se aprende investigando**.

- CyberDefenders  
  https://cyberdefenders.org/

- TryHackMe – DFIR / IR  
  https://tryhackme.com/

- Blue Team Labs Online  
  https://blueteamlabs.online/

- DFIR IRIS (Open Source)  
  https://dfir-iris.org/

---

## 🏅 Certificações (Validação de Conhecimento)

### GIAC / SANS
- GCFE  
- GCFA  
- GREM  

### EC-Council
- CHFI  

### IACIS
- CFCE  
- BCFE  

---

## 🔗 Integração com Outras Trilhas

- SOC / Blue Team – detecção e escalonamento
- CTI – contexto e atribuição
- Cloud Security – incidentes em IaaS/PaaS
- GRC / Jurídico – conformidade e evidências
- Executivo – impacto, risco e decisão

---

## 📌 Princípios-Chave da Trilha DFIR

- Preservar evidência vem antes de “resolver rápido”
- Sem timeline, não existe investigação
- DFIR não é só ferramenta, é **método**
- Comunicação é tão crítica quanto técnica
- Todo incidente deve melhorar o SOC
