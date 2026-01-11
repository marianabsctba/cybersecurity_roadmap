# ⚖️ Perícia Forense Digital

> **Investigação técnica com validade jurídica**

Perícia Forense Digital é a disciplina responsável por **coletar, preservar, analisar e apresentar evidências digitais** de forma **técnica, imparcial e juridicamente válida**.

Ela **não tem como objetivo principal conter incidentes**, como no DFIR, mas **produzir prova técnica** para:
- processos judiciais
- investigações administrativas
- auditorias
- disputas corporativas
- perícias trabalhistas, civis ou criminais

---

## ❗ Perícia Forense Digital ≠ DFIR

Embora compartilhem ferramentas e técnicas, **os objetivos são diferentes**.

| Aspecto | DFIR | Perícia Forense Digital |
|------|-----|------------------------|
| Objetivo | Conter e responder ao incidente | Produzir prova técnica |
| Foco | Operacional | Jurídico e probatório |
| Tempo | Urgente | Metodológico |
| Ambiente | SOC, Cloud, Infra | Judiciário, auditoria, compliance |
| Cadeia de custódia | Importante | **Obrigatória** |
| Neutralidade | Defesa do ambiente | **Imparcialidade técnica** |

> 📌 DFIR quer **parar o sangramento**.  
> Perícia quer **provar o que aconteceu**.

---

## 👥 Atuação Profissional

- Perito Forense Digital
- Assistente Técnico Judicial
- Perito Criminal (quando aplicável)
- Consultor Forense
- Auditor Forense de TI

> Em muitos países, o perito pode atuar como:
> - perito nomeado pelo juiz
> - assistente técnico das partes
> - perito corporativo (investigação interna)

---

## 🧠 Princípios Fundamentais da Perícia

- **Imparcialidade**
- **Reprodutibilidade**
- **Rastreabilidade**
- **Integridade da evidência**
- **Cadeia de custódia**
- **Metodologia documentada**

Sem esses princípios, **a prova pode ser invalidada**, mesmo que tecnicamente correta.

---

## 🔗 Cadeia de Custódia

A cadeia de custódia garante que a evidência:
- não foi alterada
- foi manipulada por pessoas autorizadas
- seguiu procedimentos documentados

### Elementos essenciais
- Identificação da evidência
- Registro de coleta
- Hashes criptográficos
- Armazenamento seguro
- Registro de acessos
- Registro de análise

---

## 🧬 Tipos de Evidência Digital

- Discos rígidos e SSDs
- Imagens forenses (bit a bit)
- Memória volátil (quando aplicável)
- Logs de sistema
- Logs de aplicação
- E-mails
- Mensagens e arquivos
- Dispositivos móveis
- Ambientes cloud (snapshots, logs, objetos)

---

## 🔍 Técnicas de Perícia Forense

### 🗄️ Forense de Disco
- Aquisição forense
- Análise de sistemas de arquivos
- Recuperação de dados apagados
- Análise de metadados

### 🪟 Forense em Sistemas Operacionais
- Windows (Registry, Event Logs, artefatos)
- Linux (logs, processos, filesystem)
- Análise de usuários e atividades

### 📱 Forense em Dispositivos Móveis
- Extração lógica e física
- Análise de aplicativos
- Metadados e geolocalização

### ☁️ Forense em Cloud
- Logs de acesso
- Eventos administrativos
- Evidências em SaaS, IaaS e PaaS
- Limitações de coleta e preservação

---

## 🧠 Análise e Laudo Pericial

O produto final da perícia **não é um alerta**, é um **laudo técnico**.

### Um laudo pericial deve conter:
- Objeto da perícia
- Metodologia utilizada
- Evidências analisadas
- Procedimentos executados
- Resultados técnicos
- Conclusões fundamentadas
- Limitações encontradas

> O laudo deve ser **compreensível para leigos**,  
> mas **tecnicamente defensável**.

---

## 🛠️ Ferramentas Comuns (Exemplos)

> Ferramentas **não definem a perícia**, o método define.

- Autopsy
- The Sleuth Kit
- FTK
- EnCase
- Volatility
- X-Ways Forensics
- Cellebrite (mobile)
- Magnet AXIOM

---

## 📚 Livros Essenciais de Perícia Forense Digital

### File System Forensic Analysis  
**Autor:** Brian Carrier  
> Base técnica de análise de discos e sistemas de arquivos.

---

### Digital Evidence and Computer Crime  
**Autores:** Eoghan Casey  
> Referência acadêmica e jurídica sobre evidência digital.

---

### Windows Forensic Analysis  
**Autor:** Harlan Carvey  
> Análise prática de artefatos Windows para fins periciais.

---

### The Art of Memory Forensics  
**Autores:** Michael Hale Ligh et al.  
> Forense de memória com rigor técnico.

---

## 📘 Formação e Referências

- NIST SP 800-86 – Guide to Integrating Forensic Techniques  
- NIST SP 800-101 – Mobile Device Forensics  
- ISO/IEC 27037 – Identificação e coleta de evidências digitais  
- ISO/IEC 27042 – Análise e interpretação de evidências digitais  

---

## 📌 Princípios-Chave da Perícia Forense Digital

- Sem cadeia de custódia, não existe prova
- Neutralidade técnica é obrigatória
- Ferramenta não substitui método
- Evidência precisa ser reproduzível
- Laudo é tão importante quanto a análise

---

## 🧭 Relação com DFIR

- DFIR pode **gerar evidências**
- Perícia forense **valida e formaliza**
- Nem todo DFIR vira perícia
- Toda perícia exige rigor maior que DFIR

> DFIR é **resposta técnica**.  
> Perícia Forense Digital é **prova técnica**.
