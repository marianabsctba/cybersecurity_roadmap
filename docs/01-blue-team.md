# 🟦 Blue Team / SOC / Security Operations

Esta trilha aborda **operações de segurança defensiva**, com foco em **monitoramento, detecção, resposta inicial a incidentes e engenharia de detecção**, tendo o **SIEM como núcleo operacional**, integrado a outras fontes de telemetria (EDR, Cloud, Apps, CTI).

---

## 👥 Progressão de Carreira

> **Importante:** não existe progressão linear obrigatória.  
> Em ambientes reais é comum encontrar **juniores atuando em L3** (escopos específicos) e **sêniores em L1** (operações críticas).

### Papéis comuns
- SOC Analyst L1  
- SOC Analyst L2  
- SOC Analyst L3  
- Detection Engineer  
- Threat Hunter  
- SecOps Engineer  

---

## 🧠 Habilidades Técnicas Essenciais

### SIEM e Detecção
- Ingestão de dados (agents, syslog, APIs)
- Normalização, parsing e enriquecimento
- Correlação de eventos
- Criação, tuning e versionamento de regras
- Redução de falsos positivos
- Métricas de detecção (coverage, fidelity, MTTR)

### Engenharia de Detecção
- Detecção baseada em comportamento
- Uso de fontes de dados corretas por TTP
- Validação contínua de regras
- Integração SIEM ↔ EDR ↔ CTI

### MITRE ATT&CK Aplicado
- Mapeamento de alertas para TTPs
- Uso do ATT&CK como linguagem comum
- Cobertura de técnicas vs visibilidade real
- ATT&CK para threat hunting e purple team

### Operações e Resposta Inicial
- Triagem de alertas
- Análise inicial de incidentes
- Escalonamento e contenção básica
- Comunicação com DFIR e outras áreas

### Playbooks e Automação
- Criação de playbooks operacionais
- Automação de tarefas repetitivas
- Scripts (Bash, PowerShell, Python)
- Conceitos de SOAR (orquestração)

---

## 📘 Cursos e Documentação (Formação)

### 🧠 MITRE ATT&CK (Base Obrigatória)
- **MITRE ATT&CK – Base de Conhecimento Oficial**  
  https://attack.mitre.org/

- **ATT&CK Training – Portal Oficial**  
  https://attack.mitre.org/resources/learn-more-about-attack/training/

---

### 🛡️ Wazuh (SIEM / XDR Open Source)
- **Wazuh Training – Cursos Oficiais**  
  https://wazuh.com/services/training-courses/

- **Wazuh Documentation – Oficial**  
  https://documentation.wazuh.com/

- **Wazuh Blog – Guias Técnicos**  
  https://wazuh.com/blog/

---

### 🔎 Splunk (SIEM)
- **Splunk Training – Free Courses (Oficial)**  
  https://www.splunk.com/en_us/training/free-courses/overview.html

- **Splunk Training – Portal Geral**  
  https://www.splunk.com/en_us/training.html

- **Splunk Documentation – Oficial**  
  https://docs.splunk.com/Documentation

---

### 🌐 Palo Alto Networks (SOC / XDR / XSIAM)
- **Palo Alto Networks Beacon – Plataforma Oficial de Cursos**  
  https://beacon.paloaltonetworks.com/

- **Palo Alto Networks TechDocs – Documentação Oficial**  
  https://docs.paloaltonetworks.com/

---

## 🏅 Certificações (Validação de Conhecimento)

### SOC / Blue Team / Operações
- **CompTIA CySA+**  
  https://www.comptia.org/certifications/cysa  
  > Análise de ameaças, detecção e resposta em ambientes corporativos.

- **ISC2 SSCP**  
  https://www.isc2.org/certifications/sscp  
  > Operações de segurança, monitoramento e resposta.

---

### GIAC (SANS – Blue Team / Detection / IR)
- **GIAC – Catálogo Oficial**  
  https://www.giac.org/certifications/

  Certificações relevantes:
  - **GSEC** – Security Essentials  
  - **GCIA** – Intrusion Analyst  
  - **GCIH** – Incident Handling  
  - **GCED** – Enterprise Defender  
  - **GMON** – Continuous Monitoring  

---

### Microsoft (SOC / SIEM / XDR)
- **SC-200 – Microsoft Security Operations Analyst**  
  https://learn.microsoft.com/en-us/credentials/certifications/security-operations-analyst/

- **SC-100 – Microsoft Cybersecurity Architect**  
  https://learn.microsoft.com/en-us/credentials/certifications/cybersecurity-architect/

---

## 🔗 Integração com Outras Trilhas

- **DFIR / Incident Response** – investigação aprofundada  
- **Cyber Threat Intelligence (CTI)** – enriquecimento e priorização  
- **Cloud Security** – telemetria e detecção em nuvem  
- **AppSec** – eventos e segurança de aplicações  
- **GRC** – métricas, risco e conformidade  

---

## 📌 Princípios-Chave da Trilha

- SIEM é **meio**, não fim  
- Detecção sem ATT&CK vira regra cega  
- SOC sem automação não escala  
- Threat hunting complementa, não substitui, monitoramento  
- Logs sem contexto geram ruído, não segurança  

---
