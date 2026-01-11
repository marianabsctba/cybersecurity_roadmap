# 🧱 Fundamentos de Cibersegurança

Base obrigatória para **qualquer trilha**.

---

## 🌐 Redes

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

## 🎓 Cursos e Certificações – Fundamentos (Links Oficiais)

Esta seção separa **cursos (formação e aprendizado)** de **certificações (validação de conhecimento)**, conforme boas práticas de roadmap profissional.

---

## 📘 Cursos (Formação)

### Redes
- **Cisco Networking Essentials – Cisco NetAcad**  
  https://www.netacad.com/courses/networking/networking-essentials  
  > Curso introdutório de redes: modelos, endereçamento IP, switching básico e troubleshooting.

### Linux
- **NDG Linux Essentials – Cisco NetAcad (alinhado ao LPI)**  
  https://www.netacad.com/courses/os-it/ndg-linux-essentials  
  > Curso oficial de Linux oferecido pela Cisco Networking Academy, cobrindo fundamentos de sistema operacional, linha de comando, processos, permissões e uso do Linux.  
  > **Preparatório direto para a certificação LPI Linux Essentials (LPIC)**.


### Idiomas (Inglês Técnico para TI)
- **English for IT 1 – Cisco Networking Academy**  
  https://www.netacad.com/courses/english-for-it/english-for-it-1  
  > Inglês técnico aplicado à TI: vocabulário essencial, leitura de documentação, comunicação básica em ambientes técnicos.

- **English for IT 2 – Cisco Networking Academy**  
  https://www.netacad.com/courses/english-for-it/english-for-it-2  
  > Inglês técnico intermediário: leitura avançada de documentação, comunicação profissional, reuniões técnicas e troubleshooting.

---

## 🏅 Certificações (Validação de Conhecimento)

### Base / Entry Level
- **ISC2 – Certified in Cybersecurity (CC)**  
  https://www.isc2.org/certifications/cc  
  > Validação de conhecimentos fundamentais em segurança da informação, risco e governança.

- **CompTIA ITF+ (IT Fundamentals+)**  
  https://www.comptia.org/certifications/it-fundamentals  
  > Fundamentos de TI: hardware, software, redes e noções iniciais de segurança.

- **CompTIA A+**  
  https://www.comptia.org/certifications/a  
  > Validação de conhecimentos em sistemas operacionais, hardware e troubleshooting.

- **LPI – Linux Essentials**  
  https://www.lpi.org/our-certifications/linux-essentials-overview  
  > Validação de fundamentos de Linux, linha de comando, processos e permissões.

- **CompTIA Security+**  
  https://www.comptia.org/certifications/security  
  > Validação de fundamentos de segurança: ameaças, vulnerabilidades, criptografia, identidade e risco.

- **Cisco CCNA – Cisco Certified Network Associate**  
  https://www.cisco.com/site/us/en/learn/training-certifications/certifications/enterprise/ccna/index.html  
  > Validação prática de conhecimentos em redes, routing, switching, wireless e segurança básica.

- **CompTIA Network+**  
  https://www.comptia.org/certifications/network  
  > Validação vendor neutral de fundamentos de redes, protocolos e operações.

---
*** Essas certificações não necessariamente precisam ser feitas. Estudar o conteúdo delas pode ajudar e ser enriquecedor.


# 📡 Canais de Cibersegurança – Redes, CCNA & Network Security

Curadoria de **canais técnicos e confiáveis** para aprender **redes de computadores**, **CCNA**, **análise de tráfego** e **segurança de redes**, do nível iniciante ao avançado.

---

## 🧱 Redes & CCNA (Fundação Técnica)

### Professor Messer
- CCNA, Network+, Security+
- Explicações diretas e objetivas
- Forte em fundamentos de protocolos

YouTube: https://www.youtube.com/@professormesser

---

### David Bombal
- CCNA, CCNP, automação
- Packet Tracer, GNS3, Wireshark
- Muito focado em **laboratórios práticos**

YouTube: https://www.youtube.com/@DavidBombal

---

## 🔐 Segurança de Redes (Ataque & Defesa)


### NetworkChuck
- Redes + segurança + labs
- Wireshark, VPN, Linux, Zero Trust
- Conteúdo acessível e prático

YouTube: https://www.youtube.com/@NetworkChuck

---

## 🧪 Análise de Tráfego & Pacotes

### Chris Greer
- Análise de tráfego em nível avançado
- Casos reais de troubleshooting
- Forma analistas de SOC de verdade

YouTube: https://www.youtube.com/@ChrisGreer

---

## 🧠 Redes + Cibersegurança Profissional

### Black Hills Information Security (BHIS)
- Ataques e detecção em rede
- Conteúdo Blue Team e Red Team
- Alto nível técnico

YouTube: https://www.youtube.com/@BlackHillsInformationSecurity

---


## 🇧🇷 Conteúdo em Português

### Bóson Treinamentos
- Redes, CCNA, Linux
- Muito bom para fundamentos

YouTube: https://www.youtube.com/@bosontreinamentos

---
