# ☸️ DevSecOps & Kubernetes Security

Esta trilha aborda **segurança integrada ao ciclo de entrega de software e à camada de plataforma**, com foco em **Infrastructure as Code (IaC), containers, Kubernetes, supply chain e runtime security**.

> ⚠️ **Importante**  
> DevSecOps **não é** um cargo isolado nem apenas “rodar SAST no CI”.  
> DevSecOps é a **prática de integrar segurança ao fluxo de engenharia**, enquanto **Platform / Kubernetes Security** trata da **proteção da infraestrutura, do cluster e do runtime**, onde o impacto é real.

---

## 👥 Carreiras

- **DevSecOps Engineer**  
  Atua no **ponto de interseção entre desenvolvimento, infraestrutura e segurança**, integrando controles ao SDLC, pipelines CI/CD, IaC e supply chain.

- **Platform / Kubernetes Security Engineer**  
  Responsável por **garantir que a plataforma seja segura por padrão**, cobrindo clusters, workloads, identidade, rede, políticas e runtime.

---

## 🧠 Domínios Técnicos Essenciais

### 📦 IaC Security (Infrastructure as Code)

> Em cloud e Kubernetes, **infraestrutura é código** — e código inseguro escala rápido.

- Segurança de Terraform, Helm, CloudFormation e ARM
- Validação de configurações **antes do deploy**
- Detecção de misconfiguration replicável
- Enforcement de padrões técnicos (policy as code)
- Prevenção de drift entre código e ambiente real

Ferramentas open source:
- **Checkov** – https://github.com/bridgecrewio/checkov  
- **tfsec** – https://github.com/aquasecurity/tfsec  
- **Terrascan** – https://github.com/accurics/terrascan  
- **KICS** – https://github.com/Checkmarx/kics  

---

### 🐳 Container Image Security

> Uma imagem insegura vira **mil containers inseguros**.

- Scanning de imagens em build e registry
- Vulnerabilidades em SO base e dependências
- Uso de imagens mínimas e imutáveis
- Assinatura, verificação e confiança de imagens
- Controle de origem (base images confiáveis)

Ferramentas open source:
- **Trivy** – https://github.com/aquasecurity/trivy  
- **Grype** – https://github.com/anchore/grype  
- **Syft** – https://github.com/anchore/syft  
- **Docker Scout (community)** – https://docs.docker.com/scout/  

---

### ☸️ Kubernetes Security (Cluster & Workloads)

> Kubernetes **não é seguro por padrão** — ele é flexível por padrão.

- Hardening de cluster (control plane e nodes)
- RBAC, service accounts e identidade
- Network Policies e isolamento de tráfego
- Pod Security Standards
- Segregação de namespaces e ambientes
- Proteção e acesso seguro ao etcd

Ferramentas open source:
- **kube-bench** – https://github.com/aquasecurity/kube-bench  
- **kube-hunter** – https://github.com/aquasecurity/kube-hunter  
- **Kubescape** – https://github.com/kubescape/kubescape  
- **Kyverno** – https://kyverno.io/  
- **OPA Gatekeeper** – https://github.com/open-policy-agent/gatekeeper  

---

### 🧠 Admission Control & Policy as Code

> Segurança declarativa é **controle escalável**.

- Validação de manifests no momento do deploy
- Bloqueio automático de configurações inseguras
- Enforcement técnico (não só guideline)
- Compliance contínuo e versionável
- Redução de erro humano em escala

Ferramentas:
- **OPA / Gatekeeper** – https://www.openpolicyagent.org/  
- **Kyverno** – https://kyverno.io/  

---

### 🧬 Runtime Security

> O pipeline falha. O ataque **acontece em runtime**.

- Detecção de comportamento anômalo
- Monitoramento de syscalls e eventos do kernel
- Detecção de container escape
- Visibilidade de processos e chamadas suspeitas
- Resposta em tempo real

Ferramentas open source:
- **Falco** – https://falco.org/  
- **Tetragon (eBPF)** – https://github.com/cilium/tetragon  
- **Tracee** – https://github.com/aquasecurity/tracee  

---

### 🔗 Supply Chain Security

> O atacante agora entra **antes do deploy**.

- Proteção de pipelines CI/CD
- Integridade de artefatos e builds
- Assinatura e verificação criptográfica
- Proveniência e rastreabilidade (SLSA)
- Redução de dependência não confiável

Ferramentas open source:
- **Sigstore / cosign** – https://www.sigstore.dev/  
- **in-toto** – https://in-toto.io/  
- **SLSA Framework** – https://slsa.dev/  

---

## 🧪 Labs Práticos (Essenciais)

> Essa trilha **não funciona sem laboratório**.

- **Killercoda (Kubernetes Labs)**  
  https://killercoda.com/

- **OWASP Kubernetes Goat**  
  https://github.com/madhuakula/kubernetes-goat

- **Cloud Native Security Labs**  
  https://github.com/aquasecurity/cloud-native-security-labs

- **TryHackMe – DevSecOps & Kubernetes**  
  https://tryhackme.com/

---

## 📘 Cursos Oficiais (Formação)

### Kubernetes & Cloud Native
- Linux Foundation – Kubernetes Security Fundamentals (LFS460)  
  https://training.linuxfoundation.org/training/kubernetes-security-fundamentals-lfs460/

- Kubernetes Docs – Security Concepts  
  https://kubernetes.io/docs/concepts/security/

---

### DevSecOps & Supply Chain
- DevSecOps Foundation (DOFD)  
  https://devopsinstitute.com/certifications/devsecops-foundation/

- Google SLSA & Supply Chain Security  
  https://slsa.dev/

---

## 🏅 Certificações

- **CKA – Certified Kubernetes Administrator**  
- **CKS – Certified Kubernetes Security Specialist**  
- **AWS Security – Specialty**

---

## 📚 Livros Técnicos Essenciais (DevSecOps & Kubernetes)

### Kubernetes Security  
**Autor:** Liz Rice, Michael Hausenblas  
> Referência moderna e prática sobre **segurança real em Kubernetes**.

### Container Security  
**Autor:** Liz Rice  
> Base sólida sobre containers, namespaces, cgroups e runtime.

### Practical Cloud Native Security  
**Autor:** Mark Coleman, Dan Nemeth  
> Segurança aplicada a ambientes cloud native, do build ao runtime.

### Securing DevOps  
**Autor:** Julien Vehent  
> Clássico sobre **segurança em pipelines, automação e cultura DevSecOps**.

### Software Supply Chain Security  
**Autores:** Seth Vargo et al.  
> Base moderna sobre ataques à cadeia de suprimentos e mitigação.

---

## 🔗 Integração com Outras Trilhas

- **AppSec** – segurança de código e pipelines
- **Cloud Security** – identidade, rede e governança
- **SOC / Blue Team** – detecção e resposta em runtime
- **GRC** – políticas, risco e compliance

---

## 📌 Princípios-Chave de DevSecOps & Kubernetes Security

- Segurança começa **antes do deploy**
- Kubernetes amplifica erros
- Policy as Code é controle real
- Runtime é onde o ataque acontece
- Supply chain é o novo alvo
