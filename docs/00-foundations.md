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

**Vídeos essenciais para entender o Modelo OSI na prática**
- [Modelo OSI x TCP/IP (comparação detalhada)](https://www.youtube.com/watch?v=c5vfwNBbl4g)
- [What is OSI Model | Real World Examples](https://www.youtube.com/watch?v=0y6FtKsg6J4)

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
**Introdução a CyberSecurity**
Introdução a CyberSecurity 

https://academy.secday.com.br/cursos/introducao-a-cibersecurity/

Introdução à Cibersegurança - Cisco NetAcad 

https://www.netacad.com/pt/courses/introduction-to-cybersecurity?courseLang=pt-BR

**Redes**  
Cisco Networking Essentials – Cisco NetAcad  
https://www.netacad.com/courses/networking/networking-essentials  

Base Fundamental - Redes - SECDAY

https://academy.secday.com.br/cursos/fundamentos-base-redes/

Introduction to Network Analysis - SECURITY BLUE TEAM

https://www.securityblue.team/courses/introduction-to-network-analysis

**Linux**  
NDG Linux Essentials – Cisco NetAcad

https://www.netacad.com/courses/os-it/ndg-linux-essentials  

Base Fundamental - Linux - SECDAY

https://academy.secday.com.br/cursos/linux/

**Inglês Técnico para TI**  
English for IT 1  
https://www.netacad.com/courses/english-for-it/english-for-it-1  

English for IT 2  
https://www.netacad.com/courses/english-for-it/english-for-it-2  

**Virtualização**

Base Fundamental - Virtualização - SECDAY

https://academy.secday.com.br/cursos/fundamentos-base-virtualizacao/

Introduction to Virtual Machines -  - SECURITY BLUE TEAM

https://www.securityblue.team/courses/introduction-to-virtual-machines

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

---

  # 📚 Livros Essenciais de Redes de Computadores

Esta lista reúne **livros clássicos e amplamente reconhecidos** para o estudo profundo de **redes de computadores**, cobrindo desde **fundamentos teóricos** até **protocolos, arquitetura, desempenho e troubleshooting**.

São livros usados em **universidades, engenharia de redes e segurança**, e formam a base real para áreas como:
- Cibersegurança
- SOC / Blue Team
- Cloud
- Infraestrutura
- Protocolos e tráfego
- Arquitetura de sistemas distribuídos

---

## 🧱 Fundamentos Clássicos (Base Obrigatória)

### Computer Networks
**Autores:** Andrew S. Tanenbaum, David J. Wetherall  

📌 **Por que é essencial:**  
É a referência clássica e mais completa sobre redes de computadores.

**Cobre:**
- Modelo OSI e TCP/IP
- Camadas, protocolos e arquitetura
- Ethernet, Wireless, Switching, Routing
- Controle de congestionamento
- Segurança em redes
- Casos práticos e visão acadêmica sólida

> Livro ideal para **entender como a rede funciona de verdade**, não apenas como configurar.

---

### Data Communications and Networking
**Autor:** Behrouz A. Forouzan  

📌 **Por que é essencial:**  
Excelente para **fundamentos conceituais**, com linguagem clara e progressiva.

**Cobre:**
- Comunicação de dados
- OSI e TCP/IP
- Codificação, multiplexação
- Protocolos e endereçamento
- Introdução a redes modernas

> Muito usado como **primeiro livro sério de redes**.

---

## 🌐 Protocolos, Arquitetura e Internet

### TCP/IP Illustrated – Volume 1
**Autor:** W. Richard Stevens  

📌 **Por que é essencial:**  
Referência absoluta sobre **TCP/IP em nível profundo**.

**Cobre:**
- IP, ICMP, ARP
- TCP, UDP
- Handshakes, estados e fluxos
- Funcionamento real dos protocolos na pilha

> Leitura obrigatória para quem analisa tráfego, logs e incidentes.

---

### Internetworking with TCP/IP
**Autor:** Douglas E. Comer  

📌 **Por que é essencial:**  
Excelente equilíbrio entre teoria e prática.

**Cobre:**
- Arquitetura da Internet
- Endereçamento e roteamento
- Protocolos principais
- Design de redes escaláveis

---

## 🔀 Switching, Routing & Desempenho

### High Performance Browser Networking
**Autor:** Ilya Grigorik  

📌 **Por que é essencial:**  
Livro moderno focado em **desempenho de rede para aplicações**.

**Cobre:**
- Latência e throughput
- TCP, TLS, HTTP/2, QUIC
- Impacto da rede em aplicações web
- Otimização real de tráfego

> Ponte perfeita entre **redes + aplicações + segurança**.

---

### Routing TCP/IP
**Autores:** Jeff Doyle, Jennifer Carroll  

📌 **Por que é essencial:**  
Livro clássico sobre **roteamento em profundidade**.

**Cobre:**
- Conceitos de roteamento
- Protocolos de roteamento
- Design e troubleshooting
- Escalabilidade de redes

---

## 🔐 Redes & Segurança (Base Técnica)

### Network Security Essentials
**Autor:** William Stallings  

📌 **Por que é essencial:**  
Conecta **redes tradicionais com segurança da informação**.

**Cobre:**
- Criptografia aplicada a redes
- VPNs
- Firewalls
- Autenticação e controle de acesso
- Segurança em protocolos

---

### Practical Packet Analysis
**Autor:** Chris Sanders  

📌 **Por que é essencial:**  
Introdução prática à **análise de pacotes**.

**Cobre:**
- Leitura de tráfego
- TCP/IP na prática
- Diagnóstico de falhas
- Base para SOC e IR

---

## 🧠 Sistemas Distribuídos (Complementar)

### Distributed Systems
**Autores:** Andrew S. Tanenbaum, Maarten van Steen  

📌 **Por que é relevante:**  
Expande o entendimento de redes para **sistemas modernos e distribuídos**.

**Cobre:**
- Comunicação entre processos
- Consistência e falhas
- Sincronização
- Arquitetura de sistemas distribuídos

---

## 🎯 Como usar esta lista

- 📌 Comece pelos **fundamentos clássicos**
- 📌 Avance para **TCP/IP e protocolos**
- 📌 Aprofunde em **tráfego e desempenho**
- 📌 Conecte com **segurança e observabilidade**

> 💡 Redes não são uma etapa inicial da carreira.  
> São uma **competência permanente**.

---

## ⚠️ Observação Importante

Esses livros:
- ❌ não são rápidos
- ❌ não são superficiais
- ❌ não prometem atalhos

Mas:
- ✅ constroem base sólida
- ✅ explicam o *porquê* das coisas
- ✅ diferenciam profissionais no médio e longo prazo

---

## 🏭 Fabricantes de Redes & Network Security

Esta seção apresenta **fabricantes amplamente utilizados em ambientes corporativos**, data centers e provedores, cobrindo **infraestrutura de rede** e **segurança de rede**.

O objetivo aqui **não é prescrever ferramentas**, mas ajudar a entender:
- o que existe no mercado,
- onde cada fabricante costuma atuar,
- e como isso se conecta com os fundamentos estudados.

---

### 🌐 Infraestrutura de Redes (Switching, Routing, Wireless)

- **Cisco**
  - Switching, routing, wireless, WAN
  - Amplamente presente em ambientes corporativos e ISP

- **Juniper Networks**
  - Routing e switching de alto desempenho
  - Muito usado em backbone, data center e provedores

- **Arista Networks**
  - Switching para data center e ambientes de alta escala
  - Forte em automação e redes modernas

- **Huawei**
  - Infraestrutura de redes e telecom
  - Presença forte em backbone e ambientes de grande porte

- **HPE Aruba**
  - Switching e wireless corporativo
  - Forte em redes campus e WLAN

- **Extreme Networks**
  - Switching e redes corporativas
  - Ambientes de campus e data center

---

### 🔐 Network Security (Proteção, Controle e Monitoramento)

- **Palo Alto Networks**
  - Firewalls de próxima geração
  - Inspeção de tráfego e controle de aplicações

- **Check Point**
  - Firewalls, gateways de segurança
  - Segmentação e políticas de rede

- **Cisco (Security)**
  - Firewalls, IDS/IPS, segurança integrada à rede

- **Fortinet**
  - Firewalls e segurança de rede integrada
  - Presença forte em ambientes distribuídos

- **Sophos**
  - Firewalls e segurança perimetral
  - Integração com endpoints
 
- **Sophos**
  - Firewalls de próxima geração
  - Integração entre **network security e endpoint**
  - Visibilidade e resposta coordenada a incidentes

---

### 🧠 Visibilidade, Detecção e Tráfego

- **Gigamon**
  - Network Visibility Fabric
  - Espelhamento e inspeção de tráfego

- **Arbor Networks**
  - Proteção contra DDoS
  - Monitoramento de tráfego em larga escala

- **ExtraHop**
  - Network Detection & Response (NDR)
  - Análise comportamental de tráfego

---

### 📌 Observação Importante

- Fabricantes **não substituem fundamentos**
- Ferramentas mudam, **protocolos permanecem**
- Quem entende **OSI, TCP/IP e tráfego** aprende qualquer fabricante
- Segurança de rede começa no **design**, não no appliance

> 💡 **Regra prática do roadmap**  
> Primeiro entenda **como a rede funciona**.  
> Depois entenda **como cada fabricante implementa isso**.

---



