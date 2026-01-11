# 🏭 OT / ICS Security

Esta trilha aborda **segurança de ambientes industriais e sistemas de controle** (OT/ICS), com foco em **disponibilidade, segurança funcional, resiliência operacional e proteção de processos físicos**, considerando **plantas industriais, energia, saneamento, manufatura, óleo & gás e infraestrutura crítica**.

> ⚠️ **OT não é IT mal configurado.**  
> Em OT, **disponibilidade e segurança física** vêm antes de confidencialidade, e mudanças exigem **controle extremo, validação e coordenação com engenharia**.

---

## 👥 Carreiras

- **OT Security Engineer**  
  Atua na proteção de ambientes industriais, integração IT/OT, visibilidade de rede, segmentação e mitigação de riscos operacionais.

- **ICS Security Specialist**  
  Especialista em protocolos industriais, arquiteturas de automação, hardening de controladores e resposta a incidentes OT.

---

## 🧠 Domínios Técnicos Essenciais

### 🏗️ Arquitetura OT / ICS
- Purdue Model (níveis 0–5)
- Zonas e conduítes (IEC 62443)
- Segmentação IT/OT
- DMZ industrial
- Integração segura com TI corporativa e cloud (IIoT)

---

### 📡 Protocolos Industriais
- Modbus (TCP/RTU)
- DNP3
- IEC 60870-5-104
- OPC / OPC UA
- Profinet, EtherNet/IP

> Entender protocolo é essencial para **detecção de abuso e anomalias**, não para “pentest agressivo” em produção.

---

### 🔍 Visibilidade e Monitoramento
- Descoberta **passiva** de ativos
- Inventário de PLCs, RTUs, IEDs e HMIs
- Detecção de comportamento anômalo
- Monitoramento de comandos, estados e mudanças de lógica

---

### 🛡️ Hardening & Gestão de Risco OT
- Gestão de vulnerabilidades **orientada a risco operacional**
- Patch management controlado e testado
- Avaliação de risco OT (segurança funcional × ciber)
- Priorização por impacto físico e segurança de pessoas

---

### 🚨 Resposta a Incidentes em OT
- Identificação e classificação de incidentes industriais
- Contenção **sem interromper processo**
- Coordenação com engenharia, operação e segurança
- Preservação de evidências OT
- Comunicação de impacto físico, ambiental e financeiro

---

## 📘 Frameworks, Normas e Referências

### Normas e Padrões
- IEC 62443 – Industrial Automation and Control Systems Security  
  https://www.iec.ch

- NIST SP 800-82 – Guide to ICS Security  
  https://csrc.nist.gov/publications/detail/sp/800-82/rev-3/final

- ISA Secure / ISA99  
  https://www.isasecure.org/

---

### Modelos de Referência
- Purdue Enterprise Reference Architecture  
  https://www.cisa.gov/ics

- MITRE ATT&CK for ICS  
  https://attack.mitre.org/matrices/ics/

---

## 🧪 Labs Práticos (OT / ICS)

> Em OT, **laboratório vem antes** de qualquer ação em produção.

- CISA – ICS Training & Labs  
  https://www.cisa.gov/ics-training-available-through-cisa

- RangeForce – ICS / OT Labs  
  https://www.rangeforce.com/

- TryHackMe – ICS & Industrial Rooms  
  https://tryhackme.com/

- OpenPLC Project  
  https://www.openplcproject.com/

- MiniCPS / PowerGrid Labs  
  https://github.com/satejnikamane/miniCPS

---

## 🧰 Ferramentas Open Source Importantes

### 🔎 Visibilidade & Análise
- Zeek (ICS plugins) – https://zeek.org/
- Wireshark (protocolos industriais) – https://www.wireshark.org/
- Snort / Suricata (ICS rules) – https://suricata.io/

### 🏭 OT / ICS Específicas
- GRASSMARLIN (CISA) – https://github.com/nsacyber/GRASSMARLIN
- ICSREF – https://github.com/udacity/icsref
- Conpot (ICS Honeypot) – https://github.com/mushorg/conpot

---

## 🏭 Fabricantes e Soluções Comerciais (Exemplos)

> Fabricantes **não substituem engenharia**, mas viabilizam **escala, visibilidade e governança** em OT.

### Visibilidade, Risco e Vulnerabilidades OT
- **Tenable One (OT Security)**  
  Descoberta passiva, inventário OT, correlação IT + OT e priorização por **exposição e impacto operacional**.

- Claroty  
  Visibilidade OT, inventário de ativos e monitoramento de tráfego industrial.

- Nozomi Networks  
  Detecção de anomalias OT e monitoramento profundo de protocolos industriais.

- Dragos  
  OT threat intelligence, detecção e resposta focadas em ICS.

---

### Segmentação & Microsegmentação (IT / OT)
- **Akamai Guardicore Segmentation**  
  **Microsegmentação baseada em identidade e fluxo**, aplicável a ambientes híbridos e convergência IT/OT, reduzindo movimento lateral e impacto de incidentes.

- Palo Alto Networks (Industrial NGFW)  
  Segmentação por zonas e conduítes com inspeção de tráfego.

- Cisco Industrial Security  
  Segmentação, switches industriais e integração IT/OT.

---

## 📘 Cursos e Conteúdos Oficiais

- SANS ICS410 – ICS/SCADA Security Essentials  
  https://www.sans.org

- SANS ICS515 – ICS Visibility, Detection & Response  
  https://www.sans.org

- CISA ICS Training Program  
  https://www.cisa.gov/ics-training

---

## 🏅 Certificações

- GICSP – GIAC Global Industrial Cyber Security Professional  
- IEC 62443 Cybersecurity Expert / Lead Implementer  
- CSSA – Certified SCADA Security Architect  

---

## 📚 Livros Essenciais de OT / ICS / IoT Security

### Industrial Cybersecurity – Pascal Ackerman  
Base prática de segurança industrial e integração IT/OT.

### Applied Industrial Cybersecurity – Pascal Ackerman  
Aplicação real de controles de segurança em ambientes industriais.

### Securing Industrial Control Systems – Tyson Macaulay  
Fundamentos técnicos e alinhamento com NIST e cenários reais.

### Industrial Network Security – Eric D. Knapp  
Segmentação, redes industriais e proteção de comunicação OT.

### Practical Internet of Things Security – Brian Russell & Drew Van Duren  
Segurança de IoT e IIoT conectados a ambientes industriais.

---

## 📌 Princípios-Chave de OT / ICS Security

- Disponibilidade é prioridade máxima
- Mudança sem engenharia é risco
- Visibilidade vem antes de controle
- Segmentação reduz impacto
- Segurança em OT protege **pessoas, processos e o negócio**
