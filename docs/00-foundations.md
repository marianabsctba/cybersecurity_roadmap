# 🧱 Fundamentos de Cibersegurança

Base obrigatória para **qualquer trilha**.

---

## 🌐 Redes (Networking Essentials → CCNA)

### Modelos e Arquitetura de Rede
- Modelo **OSI** (camadas, funções e troubleshooting)
- Modelo **TCP/IP**
- Arquitetura cliente-servidor
- Arquitetura peer-to-peer
- Tipos de rede: **LAN, WAN, MAN, WLAN**

### Endereçamento IP
- **IPv4 e IPv6**
- Endereçamento estático vs dinâmico
- **CIDR e subnetting**
- Gateway padrão
- **ARP** e **Neighbor Discovery (IPv6)**

### Protocolos Fundamentais
- **TCP vs UDP** (confiabilidade, latência, uso)
- **DNS** (registros A, AAAA, CNAME, MX, TXT)
- **HTTP / HTTPS**
- **TLS/SSL** (handshake, certificados, cadeia de confiança)
- **ICMP** (diagnóstico e troubleshooting)
- **DHCP** (processo DORA)
- **NTP** (sincronização de tempo para logs)

### Switching e Segmentação
- Switching Ethernet
- **VLANs**
- Trunking (802.1Q)
- Conceito de **STP**
- Unicast, multicast e broadcast
- Segmentação de rede como controle de segurança

### Wireless (WLAN)
- Padrões 802.11 (a/b/g/n/ac/ax)
- Autenticação e criptografia:
  - WPA2
  - WPA3
- Principais riscos em redes sem fio

### Segurança de Rede (Fundamentos)
- Firewalls (stateless vs stateful – conceito)
- **NAT / PAT**
- **VPNs**:
  - Site-to-site
  - Remote access
- **IDS vs IPS** (conceito)
- Segmentação de rede e redução de superfície de ataque

### Troubleshooting de Rede
- Ferramentas:
  - `ping`
  - `traceroute / tracert`
  - `nslookup / dig`
  - `netstat`
  - `ip a / ifconfig`
- Análise de caminhos de rede
- Correlação entre falhas de rede e incidentes de segurança

---

## 🐧 Linux (Fundamentos Operacionais)
- Processos e gerenciamento (`ps`, `top`, `htop`)
- Permissões e ownership
- Filesystem
- Logs (`/var/log`)
- Serviços (`systemd`)
- Comandos básicos de rede (`ip`, `ss`, `tcpdump` – nível introdutório)

---

## 🪟 Windows (Fundamentos Operacionais)
- Serviços do Windows
- Event Viewer (Security, System, Application)
- Registry (estrutura e impacto)
- Usuários, grupos e permissões
- Conceitos básicos de Active Directory

---

## 📊 Logs e Observabilidade
- Tipos de logs:
  - Sistema
  - Aplicação
  - Segurança
  - Rede
- Timestamp, timezone e sincronização
- Correlação de eventos
- Conceito introdutório de SIEM

---

## 🧠 MITRE ATT&CK
- O que é o MITRE ATT&CK
- Táticas, Técnicas e Subtécnicas
- Uso ofensivo vs defensivo
- ATT&CK como linguagem comum entre times

---

## ⚙️ Automação (Fundamentos)
- **Bash** – automação operacional em ambientes Linux
- **PowerShell** – automação e resposta a incidentes em Windows
- **Python** – scripts, parsing de logs, integrações simples

---

## 🧠 Conceitos Fundamentais de Segurança
- **CIA** – Confidencialidade, Integridade, Disponibilidade
- **AAA** – Authentication, Authorization, Accounting
- **Zero Trust**
- **Least Privilege**
- **Defense in Depth**
- Separação de funções (SoD)
- Redução de superfície de ataque

---

## 🎓 Certificações – Fundamentos (Links Oficiais)

### Base / Entry
- **ISC2 – Certified in Cybersecurity (CC)**  
  https://www.isc2.org/certifications/cc

- **CompTIA ITF+**  
  https://www.comptia.org/certifications/it-fundamentals

- **CompTIA A+**  
  https://www.comptia.org/certifications/a

- **LPI Linux Essentials**  
  https://www.lpi.org/our-certifications/linux-essentials-overview

---

### Redes (Cisco + Vendor Neutral)
- **Cisco – Networking Essentials (NetAcad)**  
  https://www.netacad.com/courses/networking/networking-essentials

- **Cisco – CCNA (Cisco Certified Network Associate)**  
  https://www.cisco.com/site/us/en/learn/training-certifications/certifications/enterprise/ccna/index.html

- **CompTIA Network+**  
  https://www.comptia.org/certifications/network

---

### Segurança (Fundamentos)
- **CompTIA Security+**  
  https://www.comptia.org/certifications/security

---

