# 🕵️ Cyber Threat Intelligence (CTI)

Esta trilha aborda **Inteligência de Ameaças Cibernéticas** com foco em **coleta, análise, contextualização e disseminação de inteligência acionável**, apoiando **SOC, DFIR, Red Team, GRC e tomada de decisão executiva**.

> CTI não é ferramenta, nem dump de IOC.  
> CTI é **processo analítico estruturado**, orientado a decisão — com **método, evidência e rastreabilidade**.

---

## 👥 Carreiras

- **CTI Analyst**  
  Produz inteligência **tática e operacional** para SOC, DFIR e times técnicos (detecção, hunting, priorização).

- **Threat Researcher**  
  Pesquisa campanhas, TTPs, atores, malware e infraestrutura, traduzindo achados em **hipóteses e deteções**.

- **Intelligence Lead / CTI Manager**  
  Define estratégia, prioriza **Intelligence Requirements (IRs)**, cria governança de CTI e integra CTI ao negócio.

> CTI maduro tem “cliente interno”: SOC, DFIR, AppSec, Executivo, GRC.  
> Sem consumidor e IR bem definido, vira **relatório bonito sem impacto**.

---

## 🧠 Domínios Técnicos Essenciais

### 🎯 Direcionamento (IRs) e Planejamento
- Definir **perguntas que importam** (IRs): o que o negócio precisa decidir?
- Priorizar por risco/impacto (coroa, crown jewels, processos críticos)
- Definir escopo de monitoramento (marca, domínios, IPs, apps, terceiros, cloud)
- Operacionalizar demanda: backlog, SLAs, cadência de relatórios e alertas

📌 CTI bom começa com **boa pergunta**.

---

### 🔍 Coleta & OSINT Estruturado (com método)
- Coleta automatizada e manual
- Fontes abertas, técnicas e humanas (quando aplicável)
- Avaliação de confiabilidade da fonte e do conteúdo
- Validação, deduplicação e enriquecimento
- Pipelines (ETL/ELT), normalização e taxonomia

📌 OSINT sem validação vira **boato em escala**.

---

### 🌑 Deep & Dark Web Intelligence (controlado e ético)
- Monitoramento de fóruns, marketplaces e chats
- Vazamentos, credenciais, stealer logs, “combos” e ofertas criminosas
- Entendimento de reputação, confiança e sinalização no underground
- Coleta ética e controlada (OPSEC, legal e escopo)

📌 Aqui o ganho é **contexto e antecipação**, não “curiosidade mórbida”.

---

### 🧠 Análise de Ameaças (o coração do CTI)
- Kill Chain, Diamond Model e ATT&CK
- Análise de campanha (timeline, hipóteses, alvos, infraestrutura)
- Correlação de: indicador + infraestrutura + comportamento + motivação
- Atribuição **com cautela** (grau de confiança e evidência)
- Produção de hipóteses acionáveis (detecção, hardening, resposta)

📌 Indicador sem hipótese é só **string**.

---

### 🧭 MITRE ATT&CK Aplicado
- ATT&CK como **linguagem comum** entre CTI, SOC, DFIR e Purple
- Mapeamento de TTPs por campanha/ator
- CTI orientado a detecção e hunting
- Gap analysis de cobertura defensiva (visibilidade x detecção x resposta)

📌 ATT&CK não é checklist: é **mapa para priorizar engenharia de detecção**.

---

### 🧪 Engineering Output (CTI que vira controle)
- Regras: Sigma / SIEM / EDR (quando aplicável)
- Watchlists: domínios, IPs, ASNs, hashes (com validade e contexto)
- Playbooks: triagem, validação, enriquecimento e decisão
- Hardening: recomendações pragmáticas (identidade, e-mail, borda, cloud)
- Detecção: hipóteses + fontes de telemetria + testes

📌 “Inteligência acionável” = **muda decisão ou muda controle**.

---

### 📝 Intelligence Reporting (para técnico e executivo)
- **Tático:** IOC + contexto + janela de validade + ação recomendada
- **Operacional:** campanhas e TTPs + priorização + impacto operacional
- **Estratégico:** tendência, risco, exposição, recomendações e investimento
- Escrita clara, objetiva e auditável (com evidência e confiança)

📌 Relatório bom é o que **vira decisão**, não o que “fica bonito”.

---

## 🔄 Ciclo de Inteligência (CTI Lifecycle)

1. **Direcionamento (IRs)**  
2. **Coleta**  
3. **Processamento** (normalização, dedupe, enriquecimento)  
4. **Análise** (hipóteses, correlação, confiança)  
5. **Disseminação** (alertas, relatórios, briefings)  
6. **Feedback** (o que gerou ação? o que foi ruído?)

---

## 🧩 Integração com o Ecossistema (CTI de verdade)

### CTI ↔ SOC
- Prioriza alertas com contexto (campanha, TTP, alvo, risco)
- Alimenta hunting com hipóteses e pivôs
- Ajuda no tuning (reduz FP e melhora fidelidade)

### CTI ↔ DFIR
- Acelera investigação (infra, tooling, padrões, IOCs com contexto)
- Ajuda na narrativa pós-incidente (linha do tempo e campanha)
- Sustenta lições aprendidas com visão do adversário

### CTI ↔ AppSec / DevSecOps
- Campanhas e exploits relevantes para stack do negócio
- Priorização de correções por exploração ativa (exploit in the wild)
- Proteção de supply chain e dependências críticas

### CTI ↔ GRC / Executivo
- Tendências e risco (setor, região, cadeia de fornecedores)
- Briefings de ameaças para decisão (investimento, prioridade, política)
- Métricas de exposição e efetividade de resposta

---

## 📘 Conteúdos e Referências Oficiais

### Frameworks e metodologia
- **MITRE ATT&CK – Base Oficial**  
  https://attack.mitre.org/

- **Lockheed Martin Cyber Kill Chain**  
  https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html

- **NIST SP 800-150 – Guide to Cyber Threat Information Sharing**  
  https://csrc.nist.gov/publications/detail/sp/800-150/final

### Guias e relatórios
- **ENISA – Threat Landscape**  
  https://www.enisa.europa.eu/topics/threat-risk-management/threats-and-trends

- **SANS – CTI Resources / Roadmap**  
  https://www.sans.org/cyber-security-skills/roadmaps/cyber-threat-intelligence/

---

## 🧪 Labs Práticos (CTI)

> CTI se aprende **analisando campanha real**, não só lendo feed.

- CyberDefenders – CTI & Threat Analysis  
  https://cyberdefenders.org/

- TryHackMe – CTI / OSINT / SOC  
  https://tryhackme.com/

- Blue Team Labs Online (BTLO)  
  https://blueteamlabs.online/

---

## 🧰 Ferramentas Open Source Importantes

### OSINT & Coleta
- Maltego CE – https://www.maltego.com/
- theHarvester – https://github.com/laramies/theHarvester
- Amass – https://github.com/owasp-amass
- SpiderFoot – https://github.com/smicallef/spiderfoot

### TIP / CTI Platforms
- OpenCTI – https://www.opencti.io/
- MISP – https://www.misp-project.org/
- Yeti – https://github.com/yeti-platform/yeti

### Enriquecimento & detecção
- Sigma – https://github.com/SigmaHQ/sigma
- ATT&CK Navigator – https://mitre-attack.github.io/attack-navigator/
- CAPE Sandbox – https://github.com/kevoreilly/CAPEv2

---

## 🏅 Certificações (Validação de Conhecimento)

- CTIA – EC-Council  
  https://www.eccouncil.org/train-certify/certified-threat-intelligence-analyst-ctia/

- GCTI – GIAC  
  https://www.giac.org/certifications/cyber-threat-intelligence-gcti/

- SANS Intelligence Track  
  https://www.sans.org/cyber-security-skills/roadmaps/cyber-threat-intelligence/

---

## 🏭 Fabricantes e Soluções (Exemplos) — CTI, DRP e ASM

> Aqui é “quem costuma aparecer no mundo real” para operacionalizar CTI/DRP/ASM.  
> **Ferramenta ajuda**, mas o diferencial é processo + analista + integração.

### 📌 CTI / DRP / Brand Protection (muito usado no Brasil)
- **Axur** — DRP, marca, phishing, vazamentos, takedown e monitoramento de superfícies digitais
- **SOCRadar** — CTI + ASM/DRP (dependendo do módulo/escopo)
- **CTI e-Safer** — operação/serviço e integração de CTI 

### 🌐 Threat Intelligence Platforms / TIP (plataforma)
- **Recorded Future**
- **Mandiant Advantage**
- **Microsoft Threat Intelligence**
- **Palo Alto Networks Unit 42**
- **CrowdStrike Intelligence**
- **CTI e-Safer** — operação/serviço e integração de CTI 

### 🛰️ Attack Surface Management (ASM) e Exposição
- **SOCRadar** (quando contratado com ASM/DRP)
- **Tenable** (Exposure/ASM dependendo do produto/escopo)
- **Akamai** (quando o foco é borda + redução/controle de exposição e proteção de superfície web, conforme arquitetura)
- **CTI e-Safer** — operação/serviço e integração de CTI 

### 🧾 Compartilhamento e padronização (integração)
- **STIX/TAXII** (padrões, não fabricante)
- Integração com **SIEM/SOAR/ITSM** para virar ticket, playbook e controle

---

## 📌 Princípios-Chave de CTI

- IOC sem contexto não é inteligência
- ATT&CK é linguagem, não checklist
- Atribuição exige evidência e grau de confiança
- Inteligência precisa ser acionável
- CTI serve à decisão, não ao ego

---

# 📘 Cyber Threat Intelligence (CTI) – Livros Essenciais

Lista curada de livros **fundamentais** para CTI **de verdade**: método analítico, integração com IR/SOC, e base técnica para acompanhar adversário.

## Fundamentos e CTI aplicado
- **Intelligence-Driven Incident Response** — Scott J. Roberts, Rebekah Brown  
  (CTI + IR/SOC, ciclo de inteligência aplicável ao operacional)

- **The Threat Intelligence Handbook** — Recorded Future  
  (visão ampla de CTI: estratégico, operacional e tático)

- **Structured Analytic Techniques for Intelligence Analysis** — Heuer Jr., Pherson  
  (metodologia e técnicas analíticas para reduzir vieses e aumentar rigor)

## CTI técnico (malware e pesquisa)
- **Practical Malware Analysis** — Sikorski, Honig  
  (base sólida para CTI técnico e entendimento de comportamento)

- **Learning Malware Analysis** — Monnappa K A  
  (técnicas modernas e correlação com TTPs)

- **Blue Fox: Arm Assembly Internals and Reverse Engineering** — Maria Markstedter  
  (reverse mais profundo, útil para pesquisa avançada e ecossistemas modernos)

## OSINT (com estrutura)
- **Open Source Intelligence Techniques** — Michael Bazzell  
  (OSINT com método e disciplina)

---

## 🎯 Observação final

CTI maduro:
- começa com IR bem definido
- transforma dados em hipótese
- entrega output que vira controle
- mede impacto (o que foi evitado, acelerado ou priorizado)

> Feed é insumo.  
> Inteligência é **decisão sustentada por evidência**.
