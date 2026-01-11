# 🤖 Segurança de Inteligência Artificial (AI Security)

Este documento descreve os **fundamentos, riscos, controles e carreiras** relacionados à **segurança de sistemas de Inteligência Artificial**, incluindo **Machine Learning (ML), LLMs, GenAI e AI-enabled systems**.

Segurança de IA **não é uma disciplina isolada**.  
Ela é uma **extensão natural de AppSec, Data Security, Cloud, DevSecOps e GRC**, com **novas superfícies de ataque**.

---

## 🎯 Objetivos da Trilha

- Entender **como sistemas de IA realmente funcionam**
- Identificar **vetores reais de ataque (não teóricos)**
- Aplicar **controles técnicos e organizacionais**
- Integrar segurança de IA ao **SDLC, DevSecOps e GRC**
- Preparar profissionais para **AI Security e AI Governance**

---

## 🧱 Fundamentos Técnicos de IA (Obrigatórios)

### Conceitos de IA e ML
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning
- Modelos supervisionados, não supervisionados e por reforço
- Pipeline de ML: coleta → treinamento → validação → inferência
- Overfitting, underfitting e data leakage

Conteúdos base:
- https://developers.google.com/machine-learning/crash-course
- https://www.coursera.org/learn/machine-learning

---

### LLMs e GenAI
- Large Language Models (LLMs)
- Tokens, contexto e embeddings
- Prompting e prompt chaining
- Fine-tuning vs **RAG (Retrieval-Augmented Generation)**
- Modelos fechados vs open source
- APIs de inferência e agentes

Conteúdos:
- https://platform.openai.com/docs
- https://huggingface.co/docs
- https://lilianweng.github.io/posts/2023-06-23-agent/

---

## 🧨 Principais Ameaças em Segurança de IA

### Ataques ao Modelo
- **Prompt Injection**
- **Jailbreak de LLM**
- Model Inversion
- Model Extraction
- Membership Inference

### Ataques aos Dados
- **Data Poisoning**
- Training data leakage
- Dataset bias intencional
- Manipulação de datasets externos (RAG)

### Ataques à Infraestrutura de IA
- Comprometimento de pipelines de ML
- Abuso de APIs de inferência
- Exposição de tokens e chaves
- Falhas de IAM em serviços de IA
- Escalada via plugins/agentes

### Ataques de Uso Indevido
- Geração de malware
- Phishing e engenharia social em escala
- Abuso de automações baseadas em IA
- Bypass de controles humanos

---

## 🧩 Superfícies de Ataque em Sistemas de IA

- Prompts e entradas do usuário
- APIs de inferência
- Pipelines de dados
- Ambientes de treinamento
- Artefatos de modelo (weights, checkpoints)
- Integrações com sistemas corporativos
- Plugins, agentes e ferramentas externas

---

## 🛡️ Controles de Segurança para IA

### 🔧 Controles Técnicos
- Validação e sanitização de prompts
- Rate limiting e autenticação forte
- Isolamento de ambientes (train / test / prod)
- Monitoramento de inferência
- Logging e auditoria de prompts e respostas
- Proteção de modelos e artefatos
- Sandbox / containers para execução

---

### 🧪 Controles de Aplicação (Secure AI SDLC)
- Threat Modeling específico para IA
- Testes de segurança em prompts
- Red Teaming de IA
- Guardrails de entrada e saída
- Human-in-the-loop para decisões críticas

---

### 🧬 Controles de Dados
- Classificação e rotulagem de dados
- Minimização de dados
- Mascaramento e anonimização
- Controle de acesso a datasets
- Auditoria de datasets de treinamento

---

## 🧠 Frameworks e Referências Técnicas

### Frameworks Oficiais
- **NIST AI Risk Management Framework (AI RMF)**  
  https://www.nist.gov/itl/ai-risk-management-framework

- **OWASP Top 10 for LLM Applications**  
  https://owasp.org/www-project-top-10-for-large-language-model-applications/

- **MITRE ATLAS – Adversarial Threat Landscape for AI Systems**  
  https://atlas.mitre.org/

- **ISO/IEC 23894 – AI Risk Management**  
  https://www.iso.org/standard/77304.html

- **ISO/IEC 27001 / 27701** (controles transversais)

---

## 🧰 Ferramentas Open Source Importantes

### 🔍 AI / LLM Security
- **PromptFoo** – https://github.com/promptfoo/promptfoo
- **Garak (LLM Vulnerability Scanner)** – https://github.com/leondz/garak
- **LLM Guard** – https://github.com/protectai/llm-guard
- **Rebuff (Prompt Injection Defense)** – https://github.com/protectai/rebuff

---

### 🧪 Red Teaming de IA
- **Microsoft PyRIT** – https://github.com/Azure/PyRIT
- **OpenAI Evals (framework)** – https://github.com/openai/evals
- **AI Red Teaming Resources (NIST)**  
  https://airc.nist.gov/

---

### 🔐 Data & Pipeline Security
- **MLflow** – https://mlflow.org/
- **Great Expectations (Data Quality)** – https://greatexpectations.io/
- **OpenLineage** – https://openlineage.io/

---

## 🧪 Labs Práticos (AI Security)

> Segurança de IA **se aprende explorando modelos reais**.

### Labs e Ambientes
- **OWASP LLM Security Labs**  
  https://github.com/OWASP/www-project-top-10-for-large-language-model-applications

- **Prompt Injection Playground**  
  https://github.com/evilrobot01/prompt-injection-playground

- **TryHackMe – AI & LLM Rooms (em evolução)**  
  https://tryhackme.com/

- **HuggingFace Spaces (model testing)**  
  https://huggingface.co/spaces

---

## 🔁 Integração com DevSecOps e GRC

### DevSecOps
- Segurança desde o design
- Pipelines de ML seguros
- Versionamento de modelos
- Monitoramento contínuo de inferência
- Integração com CI/CD

---

### GRC & Conformidade
- Avaliação de risco de IA
- Políticas de uso aceitável de IA
- Governança de modelos
- LGPD / GDPR e dados usados em IA
- Preparação para regulações de IA (EU AI Act)

---

## 👥 Carreiras em Segurança de IA

### Papéis Técnicos
- AI Security Engineer
- AppSec com foco em IA
- ML Engineer com foco em segurança
- AI Red Team / AI Blue Team

### Papéis de Governança
- AI Risk Analyst
- AI Governance Specialist
- Security Architect (AI-enabled systems)
- CISO responsável por IA

---

## 🎓 Cursos e Capacitação

### Cursos Oficiais
- **NIST AI RMF Training**  
  https://www.nist.gov/itl/ai-risk-management-framework

- **OWASP LLM Security Workshops**  
  https://owasp.org/

- **Microsoft – Secure Generative AI**  
  https://learn.microsoft.com/security/engineering/secure-ai

- **Google – Responsible AI**  
  https://ai.google/responsibility/

---

## 🎓 Certificações (Estado Atual do Mercado)

> Ainda **não existe certificação única e madura** de AI Security.

Recomenda-se combinar:
- **AppSec (OSWE, CSSLP)**
- **Cloud Security (CCSP, AWS Security)**
- **GRC / Risk (CISSP, CRISC)**
- **Privacidade (CDPSE, ISO 27701)**

Certificações emergentes devem ser avaliadas com cautela.

---

## 📌 Princípios-Chave de Segurança de IA

- IA é software + dados + infra
- Prompt é superfície de ataque
- Modelo sem governança vira risco
- Automação amplia impacto do erro
- Segurança de IA é contínua, não projeto

---
