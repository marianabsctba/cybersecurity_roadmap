# 🧱 Fundamentos de Cibersegurança
> **Base obrigatória para qualquer trilha do roadmap**

Esta seção estabelece o **alicerce técnico comum** a todas as áreas da cibersegurança.  
Sem estes fundamentos, não existe SOC eficiente, Red Team consistente, CTI de qualidade ou GRC técnico.

---

## 🌐 Redes (Fundamentos Essenciais)

> Redes são o **sistema circulatório da cibersegurança**.  
> Entender tráfego, protocolos e segmentação é entender **onde ataques nascem, se movem e são detectados**.

---

### 🗺️ Modelos e Arquitetura de Rede

| Conceito | O que você precisa saber |
|--------|--------------------------|
| **Modelo OSI** | Camadas, funções e troubleshooting por camada |
| **Modelo TCP/IP** | Pilha prática usada na Internet |
| **Cliente-servidor** | Serviços centralizados, autenticação, logs |
| **Peer-to-peer** | Comunicação direta, riscos e limitações |
| **Tipos de rede** | LAN, WAN, MAN, WLAN |

---

### 🧩 Modelo OSI – Visão Operacional

| Camada | Função | Exemplos práticos |
|------|------|------------------|
| 7 – Aplicação | Interface com o usuário | HTTP, DNS, SMTP |
| 6 – Apresentação | Formato e criptografia | TLS, SSL |
| 5 – Sessão | Controle de sessão | Sessões autenticadas |
| 4 – Transporte | Confiabilidade | TCP, UDP |
| 3 – Rede | Roteamento | IP, ICMP |
| 2 – Enlace | Endereçamento físico | Ethernet, ARP |
| 1 – Física | Meio físico | Cabo, sinal, Wi-Fi |

> 💡 **Dica prática:**  
> Saber **mapear um problema para a camada correta** acelera troubleshooting e investigação de incidentes.

---

### 📍 Endereçamento IP

- IPv4 e IPv6  
- Endereçamento **estático vs dinâmico**  
- CIDR e subnetting  
- Gateway padrão  
- ARP (IPv4) e Neighbor Discovery (IPv6)

---

### 🔌 Protocolos Fundamentais

| Protocolo | Papel |
|---------|------|
| TCP | Confiabilidade e controle |
| UDP | Baixa latência |
| DNS | Resolução de nomes (A, AAAA, CNAME, MX, TXT) |
| HTTP / HTTPS | Comunicação de aplicações |
| TLS/SSL | Criptografia, handshake e certificados |
| ICMP | Diagnóstico e troubleshooting |
| DHCP | Atribuição automática de IP (DORA) |
| NTP | Sincronização de tempo (logs e correlação) |

---

### 🔀 Switching e Segmentação

- Switching Ethernet  
- VLANs  
- Trunking (802.1Q)  
- STP (conceito)  
- Unicast, multicast e broadcast  
- Segmentação como **controle de segurança**

---

### 📶 Wireless (WLAN)

- Padrões 802.11 (a/b/g/n/ac/ax)  
- Autenticação e criptografia:
  - WPA2  
  - WPA3  
- Principais riscos em redes sem fio

---

### 🔐 Segurança de Rede (Fundamentos)

| Conceito | Visão essencial |
|--------|----------------|
| Firewalls | Stateless vs Stateful |
| NAT / PAT | Tradução de endereços |
| VPN | Site-to-site e Remote Access |
| IDS vs IPS | Detecção vs prevenção |
| Segmentação | Redução de superfície de ataque |

---

### 🛠️ Troubleshooting de Rede

**Ferramentas essenciais:**
- `ping`
- `traceroute / tracert`
- `nslookup / dig`
- `netstat`
- `ip a / ifconfig`

**Habilidades-chave:**
- Análise de caminhos de rede  
- Correlação entre falhas de rede e incidentes de segurança  

---

## 🐧 Linux – Fundamentos Operacionais

- Processos (`ps`, `top`, `htop`)  
- Permissões e ownership  
- Filesystem  
- Logs (`/var/log`)  
- Serviços (`systemd`)  
- Comandos de rede (`ip`, `ss`, `tcpdump` – nível introdutório)

---

## 🪟 Windows – Fundamentos Operacionais

- Serviços do Windows  
- Event Viewer (Security, System, Application)  
- Registry (estrutura e impacto)  
- Usuários, grupos e permissões  
- Conceitos básicos de Active Directory  

---

## 📊 Logs e Observabilidade

| Aspecto | Importância |
|------|------------|
| Tipos de logs | Sistema, Aplicação, Segurança, Rede |
| Timestamp | Base da investigação |
| Timezone | Evita erro de correlação |
| Correlação | Entender o ataque como fluxo |
| SIEM (intro) | Centralização e análise |

---

## 🧠 MITRE ATT&CK

- O que é o MITRE ATT&CK  
- Táticas, Técnicas e Subtécnicas  
- Uso ofensivo vs defensivo  
- ATT&CK como **linguagem comum entre times**

---

## ⚙️ Automação (Fundamentos)

| Linguagem | Uso principal |
|--------|--------------|
| Bash | Automação operacional em Linux |
| PowerShell | Automação e IR em Windows |
| Python | Scripts, parsing de logs, integrações |

---

## 🧠 Conceitos Fundamentais de Segurança

- CIA (Confidencialidade, Integridade, Disponibilidade)  
- AAA (Authentication, Authorization, Accounting)  
- Zero Trust  
- Least Privilege  
- Defense in Depth  
- Separação de funções (SoD)  
- Redução de superfície de ataque  

---

## 🎓 Cursos e Certificações – Fundamentos

> Esta seção separa **formação** de **validação de conhecimento**, conforme boas práticas de roadmap profissional.

### 📘 Cursos (Formação)

**Redes**  
Cisco Networking Essentials – Cisco NetAcad  
https://www.netacad.com/courses/networking/networking-essentials  

**Linux**  
NDG Linux Essentials – Cisco NetAcad  
https://www.netacad.com/courses/os-it/ndg-linux-essentials  

**Inglês Técnico para TI**  
English for IT 1  
https://www.netacad.com/courses/english-for-it/english-for-it-1  

English for IT 2  
https://www.netacad.com/courses/english-for-it/english-for-it-2  

---

## 📡 Canais de Cibersegurança – Redes & Segurança de Infraestrutura

### 🧱 Fundação Técnica
- Professor Messer  
  https://www.youtube.com/@professormesser

- David Bombal  
  https://www.youtube.com/@DavidBombal

### 🔐 Segurança de Redes
- NetworkChuck  
  https://www.youtube.com/@NetworkChuck

### 🧪 Tráfego e Pacotes
- Chris Greer  
  https://www.youtube.com/@ChrisGreer

### 🧠 Visão Profissional
- Black Hills Information Security  
  https://www.youtube.com/@BlackHillsInformationSecurity

### 🇧🇷 Conteúdo em Português
- Bóson Treinamentos  
  https://www.youtube.com/@bosontreinamentos
