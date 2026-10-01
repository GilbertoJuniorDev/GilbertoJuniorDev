## Olá, eu sou Gilberto Júnior! 👋

**Desenvolvedor Full Stack** · React · Next.js · Node.js · NestJS · TypeScript

Desenvolvedor com 4 anos de experiência construindo aplicações web de ponta a ponta, da modelagem do banco ao deploy em produção. Técnico em Informática e cursando Sistemas de Informação no IFBA, com experiência anterior em infraestrutura de redes e observabilidade, o que me ajuda a pensar em como a aplicação roda, e não só em como ela é escrita.

### 🚀 Sobre mim

- 💻 **Software Engineer na SYSTA**, desenvolvendo produtos SaaS full stack com Next.js e NestJS.
- 🌐 **Ex-JFTech**: infraestrutura de redes WAN/LAN e monitoramento com Zabbix e Grafana.
- 🧠 Uso IA no dia a dia de desenvolvimento (Claude Code, Codex, Copilot) e conduzo mentorias sobre o tema.

### 📂 Projetos em destaque

**🏛️ Systa Sindical** · *SaaS de gestão para sindicatos (código privado)*
Sistema multi-tenant com Next.js 16 + React 19 no front e NestJS (monólito modular, TypeORM, PostgreSQL, Redis) na API. Cobre filiados, empresas, diretorias, documentos e um módulo financeiro completo.
- Integração com o gateway **Asaas**: cobranças, subcontas por cliente, **split de pagamentos**, transferências e resgate via PIX
- **Webhooks** com validação de token, idempotência por chave única e **fila de reprocessamento (DLQ)**
- Resiliência: retry com backoff exponencial, job agendado que reemite cobranças com falha e scripts de correção idempotentes
- Segurança: dupla validação para saídas de dinheiro, trilha de auditoria, API keys criptografadas (AES-256-GCM) e permissões por plano
- CI no GitHub Actions, imagens Docker no GHCR e deploy em VPS com health check

**📁 [GED Pro](https://github.com/GilbertoJuniorDev/ged-pro-systa)** · *Gestão Eletrônica de Documentos*
Monorepo **Turborepo + pnpm** com pacotes compartilhados de tipos, UI e banco.
- API em NestJS 11 com TypeORM (PostgreSQL), MongoDB para logs de erro, Redis e documentação Swagger
- Front em Next.js 15 com TanStack Query, Auth.js e React Hook Form + Zod
- Armazenamento de arquivos no **Google Drive**, dossiês, séries documentais, consulta pública de documentos e permissões por departamento
- Testes unitários, de integração e E2E (Jest + Playwright) e CI/CD com deploy via Docker Compose

**🔎 [Systa Prospect](https://github.com/GilbertoJuniorDev/systa-prospect)** · *Consulta e prospecção de empresas por CNPJ*
- Pipeline de ETL que ingere a base pública de CNPJ da Receita Federal no PostgreSQL via **COPY em streaming**, com retomada de progresso e reconexão automática
- API em **Fastify** com Prisma, rate limiting e Helmet, filtros por CNAE e município e exportação para Excel
- Sistema de créditos com pagamento via **Stripe** (webhook com verificação de assinatura) e débito atômico no banco
- Front em Next.js 16 com shadcn/ui, TanStack Query e Zustand ([repo](https://github.com/GilbertoJuniorDev/systa-prospect-web))

### 🛠️ Tech Stack

| Categoria | Tecnologias |
|---|---|
| Frontend | React, Next.js (App Router), TypeScript, Tailwind CSS, shadcn/ui, TanStack Query, React Hook Form, Zod |
| Backend | Node.js, NestJS, Express, Fastify, TypeORM, Prisma |
| Bancos de Dados | PostgreSQL, MySQL, MongoDB, Redis |
| Pagamentos | Asaas (cobranças, split, PIX), Stripe, Webhooks |
| Infra & DevOps | Docker, Docker Compose, GitHub Actions, GHCR, AWS, Nginx, Caddy, Linux |
| Observabilidade | Zabbix, Grafana, The Dude |
| Testes | Jest, Testing Library, Supertest, Playwright |
| IA no desenvolvimento | Claude Code, Codex, GitHub Copilot |

### 📫 Contato

📧 gilbertojuniorcc@gmail.com · 🔗 [LinkedIn](https://linkedin.com/in/gilbertojunior-dev)
