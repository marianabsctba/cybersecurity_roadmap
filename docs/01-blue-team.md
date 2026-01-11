# 🟦 Blue Team / SOC / Security Operations

Esta trilha aborda **operações de segurança defensiva**, com foco em **monitoramento, detecção, resposta a incidentes e engenharia de detecção**, tendo o **SIEM como núcleo operacional**, integrado a outras fontes de telemetria (EDR, Cloud, Apps, CTI).

---

## 🧩 Domínios Operacionais do Blue Team / SOC

Blue Team **não é apenas o SOC reagindo a alertas**.  
É o conjunto de **capacidades preventivas, detectivas e responsivas** que atuam **antes, durante e depois do ataque**.

### 📊 Enquadramento de Atividades, Ferramentas e Responsabilidades

| Domínio Blue Team | Atividades Principais | Tecnologias / Ferramentas | Perfis Envolvidos |
|------------------|----------------------|---------------------------|-------------------|
| **Detection & Response (Core SOC)** | Monitoramento, correlação, resposta inicial, escalonamento | SIEM, EDR/XDR, NDR, UEBA | SOC L1 / L2 / L3 |
| **Exposure Management (Gevul)** | Scans de vulnerabilidade, priorização por risco, correlação com CTI | Vulnerability Management, Exposure Management | SOC L2/L3, SecOps, AppSec |
| **Network Security Controls** | Regras, segmentação, bloqueios emergenciais | Firewall / NGFW, IDS, IPS | SOC L2/L3, Network Security |
| **Application Perimeter** | Proteção e detecção em apps expostos | WAF, API Security, Bot Protection | AppSec + SOC |
| **Endpoint Protection** | Detecção comportamental e contenção | EDR / XDR | SOC L1/L2 |
| **Threat-Informed Defense** | Contextualização e priorização de alertas | CTI, MITRE ATT&CK | Threat Hunter, SOC L3 |
| **Automation & Orchestration** | Playbooks, resposta automática | SOAR, Scripts | SOC L3, Detection Engineer |
| **Logging & Telemetry** | Coleta, normalização e qualidade de logs | Agents, Syslog, APIs | SecOps, SOC |
| **Hardening & Preventive Controls** | Redução de superfície de ataque | Patch, Baselines, CIS Benchmarks | SecOps, Infra |
| **Cloud & Platform Security** | Telemetria e controles em nuvem | CSPM, CNAPP, Cloud Logs | SOC + Cloud Security |

---

## 🔍 Considerações Importantes sobre Controles no Blue Team

### 🟠 Gestão de Vulnerabilidades (Gevul)
- Atua **antes do incidente**
- Reduz superfície de ataque
- Alimenta o SOC com contexto de exploração real
- Deve ser correlacionada com **CTI e SIEM**

> Gevul é **Blue Team preventivo**, não ofensivo e não apenas GRC.

---

### 🟠 Firewall / NGFW
- Atua como **controle preventivo e detectivo**
- Permite contenção rápida durante incidentes
- Gera logs críticos para correlação no SIEM

> Firewall é **sensor e atuador** do Blue Team, não apenas “rede”.

---

### 🟠 IDS / IPS / NDR
- Detecção de scans, exploits e C2
- Complementa EDR (rede ≠ endpoint)
- Fundamental para threat hunting

---

### 🟠 WAF / API Security
- Interseção entre **AppSec e Blue Team**
- Protege aplicações e APIs
- SOC responde, AppSec define regra

---

### 🟠 EDR / XDR
- Núcleo da resposta inicial
- Detecção comportamental
- Contenção local imediata

---

---

## 🏢 O que é um SOC (Security Operations Center)

O **SOC (Security Operations Center)** é a **estrutura operacional** responsável por **executar o Blue Team no dia a dia**, funcionando como o **centro nervoso da detecção e resposta**.

Enquanto **Blue Team** representa o **conjunto de capacidades defensivas**, o **SOC é o modelo operacional** que organiza pessoas, processos e tecnologia para executar essas capacidades de forma contínua.

### 🎯 Objetivo do SOC
- Monitorar eventos de segurança em tempo quase real
- Detectar atividades maliciosas ou suspeitas
- Tomar decisões rápidas de contenção
- Coordenar resposta inicial a incidentes
- Garantir continuidade operacional e redução de impacto

---

### 🧱 Componentes Fundamentais de um SOC

| Pilar | Descrição |
|-----|----------|
| **Pessoas** | Analistas L1/L2/L3, Detection Engineers, Threat Hunters, SecOps |
| **Processos** | Playbooks, SLAs, escalonamento, comunicação, pós-incidente |
| **Tecnologia** | SIEM, EDR/XDR, NDR, SOAR, CTI, ferramentas de apoio |
| **Governança** | Métricas, KPIs, melhoria contínua, alinhamento com negócio |

---

### 🔁 O que o SOC faz (e o que ele NÃO faz)

**O SOC faz:**
- Triagem e validação de alertas
- Correlação de eventos
- Contenção inicial
- Escalonamento técnico e gerencial
- Comunicação durante incidentes
- Registro e melhoria contínua

**O SOC NÃO faz (por padrão):**
- Investigação forense profunda
- Análise detalhada de malware
- Recuperação de ambientes
- Decisões estratégicas de risco

> Essas atividades pertencem a **DFIR, Threat Research, Engenharia ou GRC**, mas são **acionadas pelo SOC**.

---

### 🧭 Modelos de SOC

- **SOC Interno (In-house)**  
  Total controle, maior custo, maior maturidade interna.

- **SOC Terceirizado (MSS / MDR)**  
  Escala rápida, dependência do fornecedor.

- **SOC Híbrido**  
  Operação compartilhada (modelo mais comum).

---

### 📊 Métricas Clássicas de um SOC Maduro

- MTTD (Mean Time to Detect)
- MTTR (Mean Time to Respond)
- Taxa de falsos positivos
- Cobertura ATT&CK
- Incidentes contidos vs escalados
- Aderência a playbooks

---

### 🧠 Relação SOC × Blue Team

> Todo SOC é Blue Team.  
> Nem todo Blue Team se resume ao SOC.

- **Blue Team** define capacidades
- **SOC** executa, monitora e responde
- **Engenharia, Gevul, Firewall, AppSec e Cloud** suportam o SOC

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

### 🧠 Threat Hunting

Threat Hunting é a atividade **proativa** do Blue Team que busca identificar ameaças **ainda não detectadas automaticamente**, com base em **hipóteses, comportamentos e inteligência de ameaça**.

**Características principais:**
- Baseado em hipóteses (não em alertas)
- Usa telemetria defensiva existente
- Complementa, não substitui, detecção automática
- Resultado vira regra, playbook ou melhoria de controle

**Fontes usadas no hunting:**
- SIEM
- EDR / XDR
- NDR
- Logs de Cloud, Firewall, Identity
- MITRE ATT&CK
- CTI

**Entregáveis do hunting:**
- Novas detecções
- Ajustes de regras
- Playbooks aprimorados
- Relatórios de achados

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

### 🟦 Blue Team / Defesa (Brasil)
- **RSquad Academy – Cursos de Blue Team, SOC e Defesa**  
  http://rsquadacademy.com.br/cursos
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

## 📌 Regra de Ouro do Blue Team

> Blue Team não é só reagir.  
> É **reduzir a chance do ataque dar certo** e **responder rápido quando ele acontece**.

Ciclo prático:
- Gevul / Hardening → evita ataque  
- Firewall / WAF / IDS → bloqueia cedo  
- SIEM / EDR → detecta e responde  
- CTI / ATT&CK → prioriza e melhora  
- SOAR → escala operação  

Tudo isso é **Blue Team**, em momentos diferentes do ataque.

---

## 🏭 Fabricantes de Soluções Diversas (Ecossistema Blue Team / SOC)

Esta seção apresenta **fabricantes relevantes no ecossistema de operações de segurança**, cobrindo **monitoramento, detecção, resposta, visibilidade, automação e proteção de aplicações expostas**.

O objetivo **não é prescrever stack**, mas ajudar a entender:
- quais categorias de soluções existem no mercado,
- onde cada tipo de ferramenta se encaixa no SOC,
- como essas soluções se complementam operacionalmente.

---

### 📊 SIEM / Centralização e Correlação

- **Splunk**
  - SIEM, analytics e correlação em larga escala
  - Forte em ambientes complexos e altamente customizáveis

- **Elastic (Elastic Security)**
  - SIEM e observabilidade
  - Forte em ambientes cloud e ecossistemas open source

- **IBM QRadar**
  - SIEM corporativo tradicional
  - Fluxo operacional bem definido para SOC

- **Microsoft Sentinel**
  - SIEM nativo em nuvem
  - Forte integração com o ecossistema Microsoft

- **Wazuh**
  - SIEM / XDR open source
  - Forte em ambientes híbridos e Linux

- **ManageEngine (Log360 / EventLog Analyzer)**
  - SIEM com foco em ambientes corporativos
  - Forte integração com Active Directory e identidade
  - Boa relação entre visibilidade, custo e operação

---

### 🖥️ Endpoint Detection & Response (EDR / XDR)

- **CrowdStrike**
  - EDR/XDR baseado em comportamento
  - Forte em resposta rápida e threat hunting

- **Microsoft Defender**
  - EDR/XDR integrado ao Windows, identidade e cloud
  - Alta cobertura em ambientes Microsoft

- **Sophos**
  - EDR/XDR com correlação entre endpoint e rede
  - Boa visibilidade e resposta coordenada

- **SentinelOne**
  - EDR focado em automação, rollback e contenção autônoma
  - Forte em resposta imediata a incidentes

- **Trend Micro**
  - EDR/XDR com foco em **endpoint, workload e cloud**
  - Forte integração com proteção de servidores
  - Boa visibilidade para resposta em ambientes híbridos

---

### 🌐 Network Detection & Response (NDR) / NTA

- **ExtraHop**
  - Análise comportamental de tráfego
  - Detecção fora do endpoint
  - Forte em ambientes de alta visibilidade de rede

- **Darktrace**
  - Detecção baseada em anomalias
  - Visibilidade em rede, cloud e ambientes híbridos

- **Vectra AI**
  - Detecção comportamental focada em tráfego e identidade
  - Forte em ambientes híbridos

- **Lumu**
  - **NTA (Network Traffic Analysis) com foco em comprometimento**
  - Detecção de comunicação com infraestrutura maliciosa (C2, IOC-based)
  - Correlação de tráfego DNS, NetFlow e logs de rede
  - Muito usada para **detecção precoce e resposta orientada a risco**
---

### 🔐 Perímetro, Aplicações e Exposição  
**(WAAP & API Security)**

- **Cloudflare**
  - Proteção DDoS, WAF e edge security
  - Forte em aplicações expostas à Internet

- **Akamai**
  - WAAP (WAF, API Security, Bot Management)
  - Proteção de aplicações e APIs em escala global

- **Imperva**
  - WAF e proteção de aplicações
  - Forte em ambientes corporativos e regulados

- **Cequence**
  - **WAAP e API Security especializados**
  - Proteção contra abuso de APIs, automação maliciosa e fraudes
  - Forte em **lógica de negócio, APIs REST/GraphQL e bots**
  - Muito usada em ambientes com alto volume de transações e integrações

---

### 🔄 Automação & Orquestração (SOAR)

- **Splunk SOAR**
  - Automação de playbooks
  - Integração profunda com SIEM

- **Cortex XSOAR (Palo Alto Networks)**
  - SOAR robusto e integrado ao XDR
  - Forte em resposta coordenada

- **Swimlane**
  - SOAR focado em workflows e automação
  - Integração ampla com ferramentas de SOC

- **ManageEngine (SOAR / Automation)**
  - Automação de resposta e workflows
  - Integração com SIEM, identidade e ITSM
  - Boa opção para SOCs corporativos e híbridos

---

### 📌 Observação Importante

- Ferramentas **não fazem SOC sozinhas**
- Integração vale mais que quantidade
- SIEM sem processo vira ruído
- EDR sem resposta vira alerta isolado
- SOAR sem critério automatiza erro

> 💡 **Regra prática do Blue Team**  
> Primeiro entenda **o fluxo operacional do SOC**.  
> Depois escolha **as ferramentas que sustentam esse fluxo**.

---

# 📚 Livros Essenciais para Blue Team, SOC & Incident Response (IR/DFIR)

Estes livros são amplamente reconhecidos por profissionais e times de segurança defensiva, SOC, detecção e resposta a incidentes — cobrindo desde fundamentos técnicos até práticas de investigação e análise forense.

---

## 🧱 Fundamentos (Base Obrigatória)

### The Practice of Network Security Monitoring  
**Autor:** Richard Bejtlich  
📌 Livro clássico que define o mindset e as práticas de **monitoramento contínuo de rede**.

**Por que é essencial**
- Conceitos de Network Security Monitoring (NSM)
- Arquitetura de sensores / coletores
- Análise de tráfego e detecção baseada em evidências
- Casos reais e estrutura operacional

> Leitura recomendada para **quem quer pensar como um analista de SOC**.

---

### Applied Network Security Monitoring
**Autor:** Chris Sanders & Jason Smith  
📌 Guia prático para implementação de NSM com exemplos reais.

**Cobre**
- Arquitetura de NSM
- Ferramentas (Zeek, Suricata, Wireshark)
- Técnicas de captura e análise de pacotes
- Casos práticos de detecção e investigação

> Excelente para **quem quer praticar análise de rede com ferramentas reais**.

---

## 🧠 Log, Detecção & SIEM

### Logging and Log Management  
**Autor:** Anton Chuvakin, Kevin Schmidt, Chris Phillips  
📌 Referência para entender logs, sua ingestão e uso em detecção.

**Cobre**
- Tipos de logs
- Normalização e retenção
- Correlação e priorização
- Preparação para SIEM e análise

> Base técnica para **quem vai trabalhar com SIEM e telemetria em produção**.

---

### Security Operations Center – Building, Operating, and Maintaining your SOC  
**Autor:** Joseph Muniz, Gary McIntyre, Nadhem AlFardan  
📌 Manual abrangente de SOC como operação.

**Cobre**
- Metrics e KPIs
- Operação L1/L2/L3
- Tuning de deteções
- Integração de controles (EDR, NDR, logs, rede)
  
> Útil para **engenheiros defensivos e líderes de times SOC**.

---

## 🔍 Incident Response & Forensics

### Incident Response & Computer Forensics  
**Autor:** Jason T. Luttgens, Matthew Pepe, Kevin Mandia  
📌 Clássico técnico para resposta a incidentes e análise forense.

**Cobre**
- Coleta de evidências
- Preservação de provas
- Análise de sistemas e memória
- Ferramentas e táticas forenses

> Um guia realista para **investigadores técnicos**.

---

### The Practice of Computer Network Defense  
**Autor:** Richard Bejtlich  
📌 Complementa NSM com foco operacional e resposta.

**Cobre**
- Operações defensivas diárias
- Táticas para equipes de detecção e resposta
- Estudos de caso

> Ideal para quem atua no **meio do ciclo de detecção → resposta**.

---

## 🔬 DFIR (Digital Forensics & Incident Response)

### The Art of Memory Forensics  
**Autores:** Michael Hale Ligh, Andrew Case, Jamie Levy, AAron Walters  
📌 Padrão ouro em **forense de memória**.

**Cobre**
- Análise de dumps de RAM
- Estruturas de dados de SO
- Investigação de malware
- Técnicas avançadas

> Uma leitura profunda para quem faz **análise de incidentes sofisticados**.

---

### Windows Forensic Analysis
**Autor:** Harlan Carvey  
📌 Focado em **Windows DFIR** (logs, artefatos, timeline).

**Cobre**
- Registry
- Artefatos de usuário
- Eventos e timestamps
- Ferramentas DFIR populares

> Essencial para ambientes corporativos com Windows.

---

## 🧠 Threat Hunting & Behavioral Detection

### The Threat Hunter’s Handbook  
**Autor:** Thoroughly Reviewed Community Book  
📌 Um guia prático de **atividades proativas de hunt**.

**Cobre**
- Hipóteses de ameaça
- Detecção orientada por dados
- Playbooks hunters
- Correlação ATT&CK

> Leitura recomendada para quem já domina o básico de SIEM/NSM e quer ir para **detecção proativa**.

---

### Practical Threat Intelligence and Data-Driven Threat Hunting  
**Autora:** Valentina Costa-Giomi  
📌 Conecta CTI com hunting operacional.

**Cobre**
- Dados para detecção
- Enriquecimento e priorização
- Técnicas modernas de busca
- Métricas de eficácia

> Excelente ponte entre **CTI, SOC e hunting real**.

---

## 📊 Análise de Tráfego & Protocolos

### Practical Packet Analysis  
**Autor:** Chris Sanders  
📌 Introdução sólida à análise de pacotes de rede.

**Cobre**
- TCP/IP na prática
- Troubleshooting real
- Ferramentas (Wireshark)
- Casos de análise

> Útil para **analistas de SOC e NSM**.

---

## 🎯 Suplementares (Estratégicos e de Pensamento)

### Blue Team Handbook  
**Autor:** Don Murdoch  
📌 Formato leve, rápido, prática de resposta.

**Cobre**
- Playbooks simplificados
- Táticas de resposta
- Checklists operacionais

> Ótimo para **treinar decisões sob pressão**.

---

### MITRE ATT&CK® Defender Series (MAD)
📌 Série de livros / materiais que conectam **ATT&CK a operações reais**.

**Cobre**
- Técnicas, métricas e cobertura
- Casos de uso e correlações
- Métricas de visibilidade

> Útil para **SOC maduros e engineering teams**.

---

## 🎯 Como usar esta lista

- 📌 Comece por **NSM, logs e SIEM**
- 📌 Aprofunde com **IR & DFIR**
- 📌 Estude protocolos para **análise de tráfego**
- 📌 Faça hunting com foco em **dados contextualizados**
- 📌 Use casos reais para validar aprendizado

---

## ⚠️ Observação Final

Estes livros:
- não são superficiais  
- demandam prática e revisão constante  
- constroem **mentalidade defensiva pragmática**

Mas formam uma base que **separa analistas técnicos de generalistas**.

---


