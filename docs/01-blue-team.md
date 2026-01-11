# 🟦 Blue Team / SOC / Security Operations

Esta trilha aborda **operações de segurança defensiva**, com foco em **monitoramento, detecção, resposta a incidentes e engenharia de detecção**, tendo o **SIEM como núcleo operacional**, integrado a outras fontes de telemetria (EDR, Cloud, Apps, CTI).

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
- Integração **SIEM ↔ EDR ↔ CTI**

### MITRE ATT&CK Aplicado
- Mapeamento de alertas para TTPs
- Uso do ATT&CK como linguagem comum
- Cobertura de técnicas vs visibilidade real
- ATT&CK aplicado a **threat hunting** e **purple team**

---

### 🚨 Resposta a Incidentes (no contexto do SOC)

> No SOC, resposta a incidentes **não é investigação profunda**, mas **contenção, decisão rápida e coordenação**.

- Triagem e classificação de incidentes
- Análise inicial e validação de alertas
- Escalonamento técnico e gerencial
- Contenção básica (isolamento, bloqueios, revogação de acessos)
- Preservação inicial de evidências
- Comunicação com DFIR, TI, Cloud e Negócio
- Registro e lições aprendidas (post-incident)

---

### Playbooks e Automação
- Criação de playbooks operacionais
- Automação de tarefas repetitivas
- Scripts (Bash, PowerShell, Python)
- Conceitos de **SOAR** (orquestração e resposta automatizada)

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

## 🧪 Labs Práticos (Essenciais para Blue Team / SOC)

> SOC **não se aprende só em curso**. Esses labs simulam **ambientes reais, alertas reais e incidentes reais**.

### Plataformas de Labs
- **TryHackMe – Blue Team & SOC Paths**  
  https://tryhackme.com/paths  
  > Trilhas de SOC, SIEM, incident response e threat hunting.

- **CyberDefenders (Blue Team Labs Online)**  
  https://cyberdefenders.org/  
  > Laboratórios focados em análise de logs, PCAPs, alertas e incidentes.

- **LetsDefend (SOC Analyst Labs)**  
  https://letsdefend.io/  
  > Simulações de SOC com tickets, alertas e fluxo operacional real.

- **DetectionLab (Open Source – GitHub)**  
  https://github.com/clong/DetectionLab  
  > Ambiente local para testes de detecção, SIEM, ATT&CK e ataques simulados.

- **Wazuh Labs (Hands-on)**  
  https://documentation.wazuh.com/current/proof-of-concept-guide/index.html  
  > Casos práticos oficiais com Wazuh.

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
