# 🚀 PageCloudv1 - Plataforma xCloud

![GitHub Enterprise](https://img.shields.io/badge/GitHub-Enterprise-blue)
![Security](https://img.shields.io/badge/Security-Advanced-green)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automated-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

## 🎯 Visão Geral

Este repositório contém a documentação completa e as configurações para a **xCloud Platform**, uma plataforma de computação em nuvem moderna e escalável. A documentação foi padronizada para facilitar o acesso, a contribuição e o desenvolvimento contínuo.

---

## 📖 Estrutura da Documentação

Navegue pelas seções principais da nossa documentação para encontrar o que precisa.

### **🔧 Setup & Configuração**
- **[Ambiente de Desenvolvimento](docs/setup/development/guia-do-desenvolvedor.md)**: Configure seu ambiente local para começar a desenvolver.
- **[Configuração de Secrets](docs/setup/github-secrets/configuracao-github-secrets.md)**: Guia completo para gerenciar segredos da organização.
- **[Workflows de CI/CD](docs/setup/workflows/setup-completo-actions.md)**: Detalhes sobre o setup de GitHub Actions e automação.

### **🏗️ Arquitetura**
- **[Arquitetura da Plataforma](docs/architecture/arquitetura.md)**: Visão geral da arquitetura do sistema xCloud.
- **[Estrutura de Projeto](docs/architecture/estrutura-do-projeto.md)**: Detalhes sobre a organização de pastas e arquivos.
- **[Arquitetura de Componentes](docs/architecture/arquitetura-de-componentes.md)**: Como os componentes e templates são estruturados.

### **📖 Guias Essenciais**
- **[Como Contribuir](docs/setup/development/como-contribuir.md)**: Diretrizes para contribuir com o projeto.
- **[Testes Locais de Workflows](docs/guides/testing/teste-workflows-local.md)**: Como testar GitHub Actions localmente com `act`.
- **[Migração do CLI para Go](docs/guides/migration/migracao-cli-go.md)**: Documentação sobre a migração do xCloud CLI.

### **📋 Referência**
- **[Política de Segurança](docs/reference/seguranca.md)**: Nossas políticas e procedimentos de segurança.
- **[Registro de Alterações](docs/reference/changelog.md)**: Histórico de todas as mudanças no projeto.
- **[Contribuidores](docs/reference/contribuidores.md)**: Lista de todas as pessoas que ajudaram a construir o projeto.
- **[Licença](docs/reference/licenca.md)**: Informações sobre a licença do projeto.

---

## 🎯 Repositórios da xCloud Platform

| Repositório | Descrição | Status |
|-------------|-----------|---------|
| **[xCloud-platform](https://github.com/PageCloudv1/xcloud-platform)** | Core da plataforma | ✅ Ativo |
| **[xCloud-cli](https://github.com/PageCloudv1/xcloud-cli)** | CLI em Go | ✅ Migrado |
| **[xCloud-dashboard](https://github.com/PageCloudv1/xcloud-dashboard)** | Dashboard React | ✅ Ativo |
| **[xCloud-runtime](https://github.com/PageCloudv1/xcloud-runtime)** | Runtime multi-linguagem | ✅ Ativo |
| **[xCloud-docs](https://github.com/PageCloudv1/xcloud-docs)** | Documentação | ✅ Ativo |
| **[xCloud-templates](https://github.com/PageCloudv1/xcloud-templates)** | Templates de projeto | ✅ Ativo |
| **[xCloud-components](https://github.com/PageCloudv1/xcloud-components)** | Componentes UI | ✅ Ativo |
| **[xCloud-examples](https://github.com/PageCloudv1/xcloud-examples)** | Exemplos e demos | ✅ Ativo |

---

## 🤖 Automações Ativas

- **CI/CD completo** em todos os 8 repositórios.
- **Testes automatizados** multi-plataforma (Windows/Linux).
- **Deploy automático** para Netlify e GitHub Pages.
- **Publicação de containers** com Podman no GHCR.
- **Reviews de Pull Requests** com Gemini AI.
- **Scans de vulnerabilidades** com Snyk e CodeQL.

---

##  Sprint de Tarefas

<details>
<summary>Clique para expandir e ver as tarefas</summary>

# 📋 TASKS - PageCloudv1 Organization Management

![Status](https://img.shields.io/badge/Status-Active-success)
![Priority](https://img.shields.io/badge/Priority-High-red)
![Team](https://img.shields.io/badge/Team-DevOps-blue)

## 📖 Visão Geral

Este documento organiza todas as tarefas necessárias para implementar e gerenciar a organização PageCloudv1 no GitHub Enterprise, divididas por fases, prioridades e responsabilidades.

---

## 🎯 Estrutura de Prioridades

### 🔴 **CRÍTICO** (P0) - Fazer Primeiro

- Segurança e acesso
- Configurações básicas da organização
- Estrutura de teams

### 🟠 **ALTO** (P1) - Próximas 2 Semanas

- Repositórios e templates
- CI/CD básico
- Branch protection

### 🟡 **MÉDIO** (P2) - Próximo Mês

- Automação avançada
- Documentação
- Monitoramento

### 🟢 **BAIXO** (P3) - Quando Possível

- Otimizações
- Features extras
- Treinamentos avançados

---

## 🏗️ FASE 1: CONFIGURAÇÃO INICIAL (Semana 1)

### 🔐 Segurança e Autenticação (P0)

- [ ] **SEC-001** Configurar autenticação 2FA obrigatória para toda organização
  - Responsável: Security Team
  - Prazo: 2 dias
  - Status: 🔴 Pendente
  
- [ ] **SEC-002** Configurar SAML SSO
  - Responsável: DevOps Team
  - Prazo: 3 dias
  - Dependencies: SEC-001
  - Status: 🔴 Pendente
  
- [ ] **SEC-003** Definir políticas de senha e acesso
  - Responsável: Security Team
  - Prazo: 1 dia
  - Status: 🔴 Pendente

### 🏢 Estrutura Organizacional (P0)

- [ ] **ORG-001** Criar organização PageCloudv1
  - Responsável: Admin Team
  - Prazo: 1 dia
  - Status: 🔴 Pendente
  
- [ ] **ORG-002** Criar estrutura inicial de teams
  - Core Developers
  - Frontend Team  
  - Backend Team
  - DevOps Team
  - Security Team
  - QA Team
  - Responsável: Admin Team
  - Prazo: 2 dias
  - Dependencies: ORG-001
  - Status: 🔴 Pendente
  
- [ ] **ORG-003** Definir hierarquia e permissões de teams
  - Responsável: Admin Team
  - Prazo: 2 dias
  - Dependencies: ORG-002
  - Status: 🔴 Pendente

### 💰 Billing e Limites (P0)

- [ ] **BILL-001** Configurar billing para GitHub Enterprise
  - Responsável: Admin Team
  - Prazo: 1 dia
  - Status: 🔴 Pendente
  
- [ ] **BILL-002** Definir spending limits
  - Responsável: Admin Team
  - Prazo: 1 dia
  - Dependencies: BILL-001
  - Status: 🔴 Pendente

---

## 🏗️ FASE 2: REPOSITÓRIOS E TEMPLATES (Semana 2)

### 📦 Repository Templates (P1)

- [x] **TEMP-001** Criar template padrão com estrutura básica
  - .github/workflows/ci.yml
  - .github/CODEOWNERS
  - .github/dependabot.yml
  - .gitignore
  - README.md
  - SECURITY.md
  - LICENSE
  - Responsável: DevOps Team
  - Prazo: 3 dias
  - Status: ✅ Completo (PR #6 merged)
  
- [ ] **TEMP-002** Criar templates específicos
  - Frontend (React/Next.js)
  - Backend (Node.js/Python)
  - Full-stack
  - Mobile (React Native)
  - Responsável: Development Teams
  - Prazo: 5 dias
  - Dependencies: TEMP-001
  - Status: 🟠 Pendente

### 🔒 Proteção de Branches (P1)

- [ ] **BRANCH-001** Configurar branch protection para main
  - Required status checks
  - Require PR reviews (2 approvals)
  - Dismiss stale reviews
  - Require code owner reviews
  - Require up-to-date branches
  - Responsável: Security Team
  - Prazo: 2 dias
  - Status: 🟠 Pendente
  
- [ ] **BRANCH-002** Configurar branch protection para develop
  - Similar ao main mas menos restritivo
  - Responsável: Security Team
  - Prazo: 1 dia
  - Dependencies: BRANCH-001
  - Status: 🟠 Pendente

### 📁 CODEOWNERS (P1)

- [ ] **CODE-001** Criar arquivos CODEOWNERS para repositórios críticos
  - ChartSpire
  - ChartSpire-backend
  - Infrastructure repos
  - Responsável: Development Teams
  - Prazo: 3 dias
  - Status: 🟠 Pendente

### 🤖 CLI Enhancements (P2)

- [ ] **CLI-001** Implementar melhorias de segurança do PR #6
  - Rate limiting no config file discovery
  - Regex validation mais robusto para nomes
  - Input sanitization aprimorado
  - Responsável: Security Team
  - Prazo: 3 dias
  - Status: 🟡 Pendente
  
- [ ] **CLI-002** Adicionar telemetria e observabilidade
  - Metrics collection para uso de comandos
  - Performance tracking
  - Error tracking structured
  - Responsável: DevOps Team
  - Prazo: 5 dias
  - Dependencies: CLI-001
  - Status: 🟡 Pendente
  
- [ ] **CLI-003** Melhorar documentação e testes
  - Integration tests para workflows completos
  - API documentation enhancement
  - Usage examples e tutorials
  - Responsável: Development Teams
  - Prazo: 7 days
  - Status: 🟡 Pendente

### 🔐 Dependabot (P1)

- [ ] **DEP-001** Configurar Dependabot para todos os repositórios
  - Security updates
  - Version updates
  - PR limits e schedule
  - Responsável: Security Team
  - Prazo: 2 dias
  - Status: 🟠 Pendente

---

## 🏗️ FASE 3: CI/CD E AUTOMAÇÃO (Semana 3-4)

### ⚙️ GitHub Actions Workflows (P1)

- [ ] **CI-001** Criar workflow básico de CI
  - Code quality check
  - Linting (ESLint, Prettier)
  - Testing (Unit, Integration)
  - Responsável: DevOps Team
  - Prazo: 3 dias
  - Status: 🟠 Pendente
  
- [ ] **CI-002** Criar workflow de segurança
  - CodeQL analysis
  - Dependency scanning
  - Secret scanning
  - Container scanning
  - Responsável: Security Team
  - Prazo: 5 dias
  - Dependencies: CI-001
  - Status: 🟠 Pendente
  
- [ ] **CI-003** Criar workflow de deployment
  - Staging environment
  - Production environment
  - Rollback capability
  - Responsável: DevOps Team
  - Prazo: 5 days
  - Dependencies: CI-001
  - Status: 🟠 Pendente

### 🏃‍♂️ Self-hosted Runners (P2)

- [ ] **RUN-001** Configurar self-hosted runners
  - Linux runners (Ubuntu 22.04)
  - Windows runners
  - Podman support
  - Responsável: DevOps Team
  - Prazo: 7 dias
  - Status: 🟡 Pendente
  
- [ ] **RUN-002** Configurar auto-scaling para runners
  - AWS/Azure integration
  - Cost optimization
  - Responsável: DevOps Team
  - Prazo: 7 dias
  - Dependencies: RUN-001
  - Status: 🟡 Pendente

### 🔐 Secrets Management (P1)

- [ ] **SEC-101** Configurar environments
  - Development
  - Staging  
  - Production
  - Responsável: DevOps Team
  - Prazo: 2 dias
  - Status: 🟠 Pendente
  
- [ ] **SEC-102** Configurar secrets para cada environment
  - Database credentials
  - API keys
  - Service tokens
  - Responsável: Security Team
  - Prazo: 3 days
  - Dependencies: SEC-101
  - Status: 🟠 Pendente

---

## 🏗️ FASE 4: SEGURANÇA AVANÇADA (Mês 2)

### 🛡️ GitHub Advanced Security (P1)

- [ ] **ADV-001** Ativar GitHub Advanced Security
  - Code scanning
  - Secret scanning
  - Dependency review
  - Responsável: Security Team
  - Prazo: 1 dia
  - Status: 🟠 Pendente
  
- [ ] **ADV-002** Configurar CodeQL para todas as linguagens
  - JavaScript/TypeScript
  - Python
  - Java
  - C#
  - Responsável: Security Team
  - Prazo: 5 dias
  - Dependencies: ADV-001
  - Status: 🟠 Pendente

### 🔍 Vulnerability Scanning (P1)

- [ ] **VULN-001** Configurar Snyk integration
  - Dependency scanning
  - Container scanning
  - IaC scanning
  - Responsável: Security Team
  - Prazo: 3 dias
  - Status: 🟠 Pendente
  
- [ ] **VULN-002** Configurar Trivy scanning
  - File system scanning
  - Repository scanning
  - Responsável: Security Team
  - Prazo: 2 days
  - Status: 🟠 Pendente

### 📋 Security Policies (P1)

- [ ] **POL-001** Criar SECURITY.md para todos os repositórios
  - Vulnerability reporting process
  - Supported versions
  - Security best practices
  - Responsável: Security Team
  - Prazo: 3 dias
  - Status: 🟠 Pendente
  
- [ ] **POL-002** Implementar security scorecards
  - Automated security assessment
  - Compliance tracking
  - Responsável: Security Team
  - Prazo: 5 dias
  - Dependencies: POL-001
  - Status: 🟠 Pendente

---

## 🏗️ FASE 5: DOCUMENTAÇÃO E WIKI (Mês 2)

### 📖 GitHub Pages (P2)

- [ ] **PAGES-001** Configurar GitHub Pages para documentação
  - Setup custom domain
  - SSL certificate
  - CDN configuration
  - Responsável: DevOps Team
  - Prazo: 3 dias
  - Status: 🟡 Pendente
  
- [ ] **PAGES-002** Criar estrutura de documentação
  - API Reference
  - User Guides
  - Developer Docs
  - Tutorials
  - Responsável: Technical Writing Team
  - Prazo: 10 dias
  - Dependencies: PAGES-001
  - Status: 🟡 Pendente

### 📚 Wiki Management (P2)

- [ ] **WIKI-001** Configurar Wiki automático
  - Sync README to Wiki
  - Auto-generate from OpenAPI
  - Template structure
  - Responsável: DevOps Team
  - Prazo: 5 dias
  - Status: 🟡 Pendente
  
- [ ] **WIKI-002** Criar conteúdo da Wiki
  - Architecture documentation
  - Development processes
  - Deployment guides
  - Troubleshooting
  - Responsável: Development Teams
  - Prazo: 15 days
  - Dependencies: WIKI-001
  - Status: 🟡 Pendente

### 💬 GitHub Discussions (P2)

- [ ] **DISC-001** Configurar categorias de discussões
  - Announcements
  - Ideas
  - Bug Reports
  - Q&A
  - Tutorials
  - Development
  - Showcase
  - Responsável: Community Team
  - Prazo: 2 dias
  - Status: 🟡 Pendente
  
- [ ] **DISC-002** Criar discussion bot
  - Auto-labeling
  - Welcome messages
  - Team notifications
  - Responsável: DevOps Team
  - Prazo: 7 days
  - Dependencies: DISC-001
  - Status: 🟡 Pendente

---

## 🏗️ FASE 6: MONITORAMENTO E MÉTRICAS (Mês 3)

### 📊 Audit Logs (P1)

- [ ] **AUDIT-001** Configurar audit log streaming
  - Splunk integration
  - Log retention policies
  - Alert rules
  - Responsável: Security Team
  - Prazo: 5 days
  - Status: 🟠 Pendente
  
- [ ] **AUDIT-002** Criar dashboards de auditoria
  - Security events
  - Access patterns
  - Policy violations
  - Responsável: Security Team
  - Prazo: 7 days
  - Dependencies: AUDIT-001
  - Status: 🟠 Pendente

### 📈 Métricas e Analytics (P2)

- [ ] **METRICS-001** Configurar GitHub Insights
  - Development velocity
  - Code review metrics
  - Security metrics
  - Responsável: DevOps Team
  - Prazo: 3 dias
  - Status: 🟡 Pendente
  
- [ ] **METRICS-002** Criar dashboards customizados
  - Repository health scores
  - Team performance
  - Security posture
  - Responsável: DevOps Team
  - Prazo: 10 days
  - Dependencies: METRICS-001
  - Status: 🟡 Pendente

### 🚨 Alertas e Notificações (P1)

- [ ] **ALERT-001** Configurar alertas críticos
  - Security incidents
  - Build failures
  - Deployment issues
  - Responsável: DevOps Team
  - Prazo: 3 dias
  - Status: 🟠 Pendente
  
- [ ] **ALERT-002** Integrar com Slack/Teams
  - Channel routing
  - Escalation rules
  - On-call rotations
  - Responsável: DevOps Team
  - Prazo: 5 days
  - Dependencies: ALERT-001
  - Status: 🟠 Pendente

### ⚕️ Health Checks (P2)

- [ ] **HEALTH-001** Implementar repository health checks
  - Documentation coverage
  - Security compliance
  - Code quality metrics
  - Responsável: DevOps Team
  - Prazo: 7 dias
  - Status: 🟡 Pendente
  
- [ ] **HEALTH-002** Automated health reports
  - Weekly reports
  - Trend analysis
  - Action recommendations
  - Responsável: DevOps Team
  - Prazo: 5 days
  - Dependencies: HEALTH-001
  - Status: 🟡 Pendente

---

## 🏗️ FASE 7: TREINAMENTO E PROCESSOS (Contínuo)

### 📚 Treinamento de Equipe (P2)

- [ ] **TRAIN-001** Criar material de onboarding
  - GitHub Enterprise basics
  - Security best practices
  - Development workflows
  - Responsável: HR Team + Tech Leads
  - Prazo: 15 days
  - Status: 🟡 Pendente
  
- [ ] **TRAIN-002** Sessões de treinamento
  - Git workflows
  - Code review process
  - Security awareness
  - CI/CD practices
  - Responsável: Tech Leads
  - Prazo: Ongoing
  - Status: 🟡 Pendente

### 📝 Documentação de Processos (P2)

- [ ] **PROC-001** Documentar workflows de desenvolvimento
  - Feature development
  - Bug fixing
  - Release process
  - Hotfix process
  - Responsável: Tech Leads
  - Prazo: 10 days
  - Status: 🟡 Pendente
  
- [ ] **PROC-002** Criar guias de contribuição
  - Code standards
  - PR templates
  - Issue templates
  - Responsável: Development Teams
  - Prazo: 7 days
  - Status: 🟡 Pendente

### 🎓 Knowledge Base (P3)

- [ ] **KB-001** Criar base de conhecimento
  - FAQ
  - Troubleshooting guides
  - Best practices
  - Responsável: Technical Writing Team
  - Prazo: 20 days
  - Status: 🟢 Pendente
  
- [ ] **KB-002** Setup knowledge management system
  - Search functionality
  - Version control for docs
  - Contribution process
  - Responsável: DevOps Team
  - Prazo: 10 days
  - Dependencies: KB-001
  - Status: 🟢 Pendente

---

## 🚀 TAREFAS ESPECIAIS E OTIMIZAÇÕES

### 🤖 GitHub Apps e Bots (P2)

- [ ] **BOT-001** Criar PageCloudv1 Automation Bot
  - Auto-labeling
  - PR management
  - Issue triage
  - Responsável: DevOps Team
  - Prazo: 10 days
  - Status: 🟡 Pendente
  
- [ ] **BOT-002** Integrar bots de terceiros
  - Dependabot
  - Semantic Release
  - All Contributors
  - Responsável: DevOps Team
  - Prazo: 5 dias
  - Status: 🟡 Pendente

### 🌐 Integrações Externas (P3)

- [ ] **INT-001** Integrar com Jira/Azure DevOps
  - Issue syncing
  - Workflow automation
  - Responsável: DevOps Team
  - Prazo: 15 days
  - Status: 🟢 Pendente
  
- [ ] **INT-002** Integrar com Slack/Teams
  - Notifications
  - Commands
  - Status updates
  - Responsável: DevOps Team
  - Prazo: 7 days
  - Status: 🟢 Pendente

### 📦 Package Management (P2)

- [ ] **PKG-001** Configurar GitHub Packages
  - npm registry
  - Container registry
  - Maven repository
  - Responsável: DevOps Team
  - Prazo: 7 dias
  - Status: 🟡 Pendente
  
- [ ] **PKG-002** Setup package security scanning
  - Vulnerability scanning
  - License compliance
  - Responsável: Security Team
  - Prazo: 5 dias
  - Dependencies: PKG-001
  - Status: 🟡 Pendente

---

## 🎯 MILESTONES E DEADLINES

### 🏁 Milestone 1: Foundation (Semana 2)

**Meta**: Organização funcional com teams e segurança básica

- ✅ Todas as tarefas P0 completas
- ✅ SAML SSO configurado
- ✅ Teams estruturados
- ✅ 2FA obrigatório

### 🏁 Milestone 2: Development Ready (Semana 4)

**Meta**: Desenvolvedores podem trabalhar de forma segura e eficiente

- ✅ Templates de repositório criados
- ✅ CI/CD básico funcionando
- ✅ Branch protection ativo
- ✅ Code owners definidos

### 🏁 Milestone 3: Production Ready (Mês 2)

**Meta**: Pipelines completos para produção

- ✅ Deployment automático
- ✅ Security scanning completo
- ✅ Monitoring básico
- ✅ Documentation estruturada

### 🏁 Milestone 4: Enterprise Grade (Mês 3)

**Meta**: Organização madura e otimizada

- ✅ Audit logs configurados
- ✅ Dashboards completos
- ✅ Processes documentados
- ✅ Team treinada

---

## 📊 DASHBOARD DE PROGRESSO

### Por Fase

- **Fase 1**: 🔴 0/8 (0%)
- **Fase 2**: 🟠 1/8 (12.5%) - CLI Core implementado
- **Fase 3**: 🟠 0/9 (0%)
- **Fase 4**: 🟠 0/6 (0%)
- **Fase 5**: 🟡 0/8 (0%)
- **Fase 6**: 🟡 0/8 (0%)
- **Fase 7**: 🟡 0/6 (0%)

### Por Prioridade

- **P0 (Crítico)**: 🔴 0/8 (0%)
- **P1 (Alto)**: 🟠 0/25 (0%)
- **P2 (Médio)**: 🟡 0/20 (0%)
- **P3 (Baixo)**: 🟢 0/4 (0%)

### Por Equipe

- **Admin Team**: 0/5 (0%)
- **Security Team**: 0/15 (0%)
- **DevOps Team**: 0/25 (0%)
- **Development Teams**: 0/8 (0%)
- **QA Team**: 0/0 (0%)

---

## 📋 TEMPLATES DE TAREFAS

### Template para Nova Tarefa

```markdown
- [ ] **[CATEGORIA-NUM]** Título da tarefa
  - Descrição detalhada
  - Critérios de aceitação
  - Responsável: [Team]
  - Prazo: X dias
  - Dependencies: [TASK-IDS]
  - Status: 🔴/🟠/🟡/🟢 [Status]
  - Estimativa: [Story Points]
```

### Códigos de Status

- 🔴 **Crítico/Bloqueado** - Precisa atenção imediata
- 🟠 **Em Progresso** - Sendo trabalhado ativamente
- 🟡 **Planejado** - Próximo na fila
- 🟢 **Futuro** - Planejado para mais tarde
- ✅ **Completo** - Finalizado e validado
- ❌ **Cancelado** - Não será feito
- ⏸️ **Pausado** - Temporariamente parado

---

## 🤝 COMO CONTRIBUIR COM AS TASKS

1. **Atribuir-se a uma tarefa**: Adicione seu nome como responsável
2. **Atualizar status**: Mude o emoji quando começar/terminar
3. **Adicionar detalhes**: Use comentários ou sub-tasks quando necessário
4. **Reportar bloqueios**: Marque como 🔴 e documente o problema
5. **Revisar dependencies**: Verifique se pré-requisitos foram atendidos

### Pull Request para Tasks

Quando uma tarefa for completada:

1. Marque como ✅
2. Adicione data de conclusão
3. Faça PR com evidência (screenshots, links, etc.)
4. Solicite review do tech lead

---

## 📞 CONTATOS E ESCALAÇÃO

### Tech Leads por Área

- **Security**: [@security-lead]
- **DevOps**: [@devops-lead]  
- **Frontend**: [@frontend-lead]
- **Backend**: [@backend-lead]

### Escalação de Bloqueios

1. **Nível 1**: Tech Lead da área
2. **Nível 2**: Engineering Manager
3. **Nível 3**: CTO

### Canal de Comunicação

- **Slack**: #pagecloud-tasks
- **Daily Standup**: 9:00 AM UTC
- **Weekly Review**: Sextas 16:00 UTC

---

**Maintained by**: PageCloudv1 DevOps Team

</details>

---

## 🤝 Como Contribuir

Estamos sempre abertos a contribuições! Para começar, leia nosso **[Guia de Contribuição](docs/setup/development/como-contribuir.md)** e nosso **[Código de Conduta](docs/setup/development/codigo-de-conduta.md)**.

## 📝 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](docs/reference/licenca.md) para mais detalhes.
