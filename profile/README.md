# Bluehut

A **Bluehut** é uma organização de tecnologia focada no desenvolvimento de soluções digitais, automações, integrações e sistemas sob medida para empresas.

Nosso objetivo é transformar processos complexos em soluções simples, escaláveis e bem estruturadas.

---

## Áreas de atuação

- Desenvolvimento de sistemas web
- APIs e integrações entre plataformas
- Automações de processos
- Dashboards, relatórios e soluções de BI
- Arquitetura backend e frontend
- Projetos internos, MVPs e laboratórios de inovação

---

## Organização dos repositórios

Para manter os projetos limpos e bem classificados, utilizamos uma convenção baseada em **prefixos por cliente, produto ou domínio de negócio**.

### Prefixos por cliente ou projeto

| Prefixo | Uso |
|---|---|
| `mushard-*` | Repositórios relacionados ao ecossistema MuShard |
| `zkx-*` | Repositórios relacionados ao cliente/projeto ZKX |
| `bluehut-*` | Projetos internos, institucionais ou administrativos da Bluehut |
| `lab-*` | Provas de conceito, MVPs, estudos e experimentos |
| `infra-*` | Infraestrutura, deploy, Docker, CI/CD, scripts e automações técnicas |
| `legacy-*` | Projetos antigos, pausados, descontinuados ou mantidos apenas por histórico |

---

## Padrão recomendado de nomes

Dentro de cada cliente ou projeto, os repositórios seguem uma nomenclatura funcional:

| Sufixo | Uso |
|---|---|
| `*-api` | Backend, APIs e serviços principais |
| `*-web` | Frontend web |
| `*-admin` | Painel administrativo |
| `*-mobile` | Aplicações mobile |
| `*-bff` | Backend for Frontend |
| `*-gateway` | API Gateway ou camada de entrada |
| `*-worker` | Jobs, filas, consumers e processamentos assíncronos |
| `*-docs` | Documentação técnica ou funcional |
| `*-infra` | Arquivos de infraestrutura específicos do projeto |

### Projetos
---

## MuShard

Repositórios relacionados ao ecossistema **MuShard**, incluindo portal, loja, autenticação, gateway, serviços backend e aplicações auxiliares.

| Repositório | Responsabilidade |
|---|---|
| [mushard-client](https://github.com/BluehutTech/mushard-client) | Cliente/aplicação principal do ecossistema MuShard |
| [mushard-shop-api](https://github.com/BluehutTech/mushard-shop-api) | API responsável pela loja e regras de compra |
| [mushard-shop-web](https://github.com/BluehutTech/mushard-shop-web) | Frontend web da loja |
| [mushard-server-info-api](https://github.com/BluehutTech/mushard-server-info-api) | API de informações do servidor |
| [mushard-news-api](https://github.com/BluehutTech/mushard-news-api) | API de notícias e comunicados |
| [mushard-updater](https://github.com/BluehutTech/mushard-updater) | Atualizador/launcher do cliente MuShard |
| [mushard-auth-api](https://github.com/BluehutTech/mushard-auth-api) | API de autenticação e identidade |
| [mushard-portal-bff](https://github.com/BluehutTech/mushard-portal-bff) | Backend for Frontend do portal |
| [mushard-orchestrator-gateway](https://github.com/BluehutTech/mushard-orchestrator-gateway) | Gateway/orquestrador de entrada dos serviços |
