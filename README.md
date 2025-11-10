PROJETO INTEGRADOR II - GRUPO 004 - EIXO COMPUTAÇÃO - UNIVESP - 2025

Arquitetura:

A aplicação seguirá o padrão Full-Stack: a mesma base de código conterá o front-end e o back-end, facilitando o versionamento e o deploy contínuo.

* Front-End: React + Tailwind
* Back-end: Next.js + TypeScript
* Banco de Dados + Autenticação: Supabase e PostgreSQL
* Hospedagem e Deploy: Vercel
* Versionamento: Git + GitHub

ESTRUTURA DO PROJETO:
/
├── .github/                    # Configurações GitHub (workflows, templates)
├── public/                     # Arquivos estáticos
│   ├── favicon.ico
│   ├── placeholder.svg
│   └── robots.txt
├── src/                        # Código-fonte da aplicação
│   ├── components/             # Componentes React reutilizáveis
│   │   ├── Header.tsx
│   │   └── ui/                 # Componentes UI shadcn
│   ├── contexts/               # Contextos React (Auth)
│   ├── hooks/                  # Custom hooks
│   ├── integrations/           # Integrações externas
│   ├── lib/                    # Utilitários
│   ├── pages/                  # Páginas da aplicação
│   │   ├── Auth.tsx
│   │   ├── Dashboard.tsx
│   │   ├── TaskForm.tsx
│   │   ├── TaskDetail.tsx
│   │   ├── OsPrintPage.tsx
│   │   ├── Clients.tsx
│   │   └── Store.tsx
│   ├── types/                  # Definições TypeScript
│   ├── App.tsx                 # Componente raiz + rotas
│   ├── main.tsx                # Entry point
│   └── index.css               # Estilos globais
├── supabase/                   # Configurações backend (Supabase)
│   ├── config.toml             # Config auto-gerenciado
│   └── migrations/             # Migrações do banco de dados
├── .env                        # Variáveis de ambiente (NÃO comitar)
├── .gitignore                  # Arquivos ignorados pelo Git
├── package.json                # Dependências e scripts
├── react.config.ts              # Configuração React
├── tailwind.config.ts          # Configuração Tailwind CSS
├── tsconfig.json               # Configuração TypeScript
├── VERSION_CONTROL.md          # Este arquivo
├── CHANGELOG.md                # Histórico de mudanças
└── README.md                   # Documentação principal
