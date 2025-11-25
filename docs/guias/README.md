# 📚 Biblioteca de Guias | Deploys, Setups & Stacks Modernas

Bem-vindo ao repositório da minha **Biblioteca Técnica de Deploys, Setups e Stacks Modulares**, uma coleção viva e em constante evolução de guias práticos, scripts idempotentes, playbooks, helm charts e documentações voltadas para ambientes modernos de Infraestrutura, DevOps, Observabilidade, Contêineres e Desenvolvimento de Aplicações Inteligentes desenvolvidas por Agentes IA Autônomos em conjunto com MCP Servers.

Este repositório consolida o meu domínio avançado em **Linux (Ubuntu 24.04 LTS)**, **Docker**, **Docker Compose**, **Python**, **Ansible**, **Helm**, **Kubernetes (MicroK8s)**, **React**, **Vite**, **TypeScript**, automações orquestradas e stacks modulares sempre pensadas para ambientes de missão crítica.

Cada guia aqui presente busca seguir padrões elevados de engenharia:

* **Idempotência total**
* **Scripts limpos, reutilizáveis e altamente validados**
* **Comentários detalhados (pt-BR)**
* **Checklists, pré-requisitos e troubleshooting**
* **Arquiteturas visuais + diagramas quando necessário**
* **Foco em continuidade, padronização e modularidade**

Este repositório funcionará como sua referência central de boas práticas, padrões e automações profissionais.

---

## 📁 Estrutura dos Guias

Cada guia possui:

* Um arquivo `README.md` com toda a documentação técnica e procedural
* Scripts auxiliares (Bash / Python)
* Arquivos de automação (`docker-compose.yml`, playbooks Ansible, charts Helm, manifests, etc.)
* Estrutura padronizada e escalável

```bash
/guias/
  bitwarden/
    README.md
    deploy_bitwarden.sh
    docker-compose.yml

  python3/
    README.md
    setup_python_env.sh
    examples/
      script_teste.py

  ansible/
    README.md
    install_ansible.sh
    collections/
      requirements.yml

  docker/
    README.md
    install_docker.sh
    install_compose.sh

  microk8s/
    README.md
    setup_microk8s.sh
    addons/
      ...

  react_vite_typescript/
    README.md
    template/
      src/
      package.json
      vite.config.ts
```

---

## 🚀 Guias Disponíveis (Primeiros Módulos da Biblioteca)

### 1. Deploy do Bitwarden (Self-Hosted)

Guia completo para instalação, configuração, manutenção e boas práticas.
Inclui:

* Script de deploy idempotente
* `docker-compose.yml` modular
* Checklist de segurança
* Boas práticas para produção

---

### 2. Guia de deploy Python3

Inclui:

* Instalação do Python3 + `pip` + `venv`
* Ambiente isolado e idempotente
* Módulos essenciais, `pip-tools`, wheels
* Estrutura recomendada de projetos
* Scripts de validação e testes

---

### 3. Guia de Ansible + Collections + Pip + + VENV + Automação Avançada

Conteúdo:

* Instalação segura e validada
* Configuração global do Ansible
* Collections + Galaxy + dependências via `pip` com VENV.
* Estrutura ideal de playbooks
* Módulos essenciais e padrões modernos

---

### 4. Docker & Docker Compose | Setup e Melhores Práticas

Inclui:

* Instalação idempotente do Docker CE
* Ajustes de kernel + `sysctl` + `cgroups`
* Plugin `docker compose`
* Estrutura ideal de stacks em `/opt/docker/...`
* Scripts de healthcheck e validações

---

### 5. Guia de Kubernetes com MicroK8s

Inclui:

* Instalação limpa em Ubuntu 24.04
* Addons essenciais (`dns`, `storage`, `ingress` etc.)
* RBAC + Namespaces + Profiles
* Deploys simples e avançados
* Integração com Helm Charts

---

### 6. React + Vite + TypeScript

Inclui:

* Setup completo do ambiente
* Estrutura recomendada para apps modernos
* Otimizações para Vercel / CI/CD
* Padrão de componentes e hooks
* Boas práticas de DX (Developer Experience)

---

## 🔧 Filosofia Técnica dos Guias

Todos os conteúdos desta biblioteca seguem princípios sólidos:

### Idempotência Sempre

Scripts e playbooks são escritos para **não modificar estados já existentes**.

### Modularidade e Reutilização

Cada recurso é criado para ser encaixável em outras stacks.

### Logs, validações e segurança

Todos os scripts contam com:

* logs
* validações prévias
* backups automáticos (quando aplicável)
* rollback

### Clareza e Maturidade Técnica

Textos diretos, robustos, sem floreios desnecessários — apenas engenharia aplicada.

---

## 📈 Evolução Contínua

Esta biblioteca cresce continuamente.
Novos módulos planejados:

* Helm Charts estruturados
* Setup Node.js + nvm
* Setup FastAPI, Celery, Redis
* Observabilidade completa: Vector, Jaeger, Prometheus, Opentelemetry, SigNoz...
* Pipelines CI/CD + GitHub Actions
* Deploy de aplicações IA (Gemini / OpenAI / Mistral)
* Automação com n8n + Webhooks + integrações
* Hardening avançado de servidores

---

## 🧠 Sobre a Engenharia por trás deste repositório

Esta biblioteca demonstra e consolida minha experiência em:

* Arquiteturas de Infraestrutura Moderna
* Stacks Modulares em ambientes críticos
* Contêineres e Orquestração
* Desenvolvimento de apps AI-Driven
* Automação e Observabilidade Inteligente
* Cultura DevOps e GitOps
* Engenharia Linux avançada (Ubuntu 24.04 LTS)
* Código limpo, preciso e totalmente validado

Cada linha deste repositório reflete precisão, assertividade e visão.

---

## 📬 Contribuições

Futuramente este repositório poderá aceitar contribuições, mas inicialmente o foco é consolidar uma coleção de guias autorais, estruturados para produção.

