<h1 align="center">Thiago Heckler</h1>
<p align="center"><em>Integrações que fazem a diferença</em></p>

```json
{
  "stack": ["Java 25 · Spring Boot 4", "PHP 8.4 · Laravel 12", "Python 3.12 · FastAPI"],
  "domínio": "fiscal",
  "estudando": ["Engenharia com IA", "Next.js · NestJS", "Go"],
  "foco": integracoes()
}
```

### Sobre

Desenvolvedor backend e estudante de Ciência da Computação na UNOESC (São Miguel do Oeste, SC), na reta final do curso: formatura em dezembro de 2026. Trabalho num escritório de contabilidade, e é daí que vem meu diferencial: além de escrever código, entendo a fundo o lado fiscal brasileiro (NF-e, SPED, ICMS-ST, PIS/COFINS). Quando esses dois mundos se juntam, dá pra construir integração que a maioria dos devs não consegue tocar sem um contador do lado.

O que eu mais gosto de fazer é justamente isso: conectar sistemas que dão trabalho de conectar, como SEFAZ, meios de pagamento (PIX, Mercado Pago) e WhatsApp, e deixar tudo rodando redondo. Ultimamente tenho levado IA pra esse mesmo terreno, sempre na periferia: a regra fiscal continua determinística e auditável, e o LLM entra pra explicar, classificar e citar a fonte.

### Stack

**Backend**
![Java](https://img.shields.io/badge/Java_25-0D1B2A?style=for-the-badge&logo=openjdk&logoColor=F4A81D)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-0D1B2A?style=for-the-badge&logo=springboot&logoColor=F4A81D)
![PHP](https://img.shields.io/badge/PHP_8.4-0D1B2A?style=for-the-badge&logo=php&logoColor=F4A81D)
![Laravel](https://img.shields.io/badge/Laravel_12-0D1B2A?style=for-the-badge&logo=laravel&logoColor=F4A81D)
![Python](https://img.shields.io/badge/Python-0D1B2A?style=for-the-badge&logo=python&logoColor=F4A81D)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1B2A?style=for-the-badge&logo=fastapi&logoColor=F4A81D)

**Front & Dados**
![React](https://img.shields.io/badge/React-0D1B2A?style=for-the-badge&logo=react&logoColor=2DD4BF)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1B2A?style=for-the-badge&logo=typescript&logoColor=2DD4BF)
![Tailwind](https://img.shields.io/badge/Tailwind-0D1B2A?style=for-the-badge&logo=tailwindcss&logoColor=2DD4BF)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1B2A?style=for-the-badge&logo=postgresql&logoColor=2DD4BF)
![MySQL](https://img.shields.io/badge/MySQL-0D1B2A?style=for-the-badge&logo=mysql&logoColor=2DD4BF)
![Redis](https://img.shields.io/badge/Redis-0D1B2A?style=for-the-badge&logo=redis&logoColor=2DD4BF)

**IA**
![LangChain](https://img.shields.io/badge/LangChain-0D1B2A?style=for-the-badge&logo=langchain&logoColor=A78BFA)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1B2A?style=for-the-badge&logo=langgraph&logoColor=A78BFA)
![pgvector](https://img.shields.io/badge/pgvector_·_RAG-0D1B2A?style=for-the-badge&logo=postgresql&logoColor=A78BFA)
![Claude Code](https://img.shields.io/badge/Claude_Code-0D1B2A?style=for-the-badge&logo=claude&logoColor=A78BFA)

**Infra**
![Docker](https://img.shields.io/badge/Docker-0D1B2A?style=for-the-badge&logo=docker&logoColor=EAF0F6)
![n8n](https://img.shields.io/badge/n8n-0D1B2A?style=for-the-badge&logo=n8n&logoColor=EAF0F6)
![Linux](https://img.shields.io/badge/Linux-0D1B2A?style=for-the-badge&logo=linux&logoColor=EAF0F6)
![AWS](https://img.shields.io/badge/AWS_S3_·_SQS-0D1B2A?style=for-the-badge&logo=amazonwebservices&logoColor=EAF0F6)
![Git](https://img.shields.io/badge/Git-0D1B2A?style=for-the-badge&logo=git&logoColor=EAF0F6)

### Estudando agora

- **Engenharia com IA aplicada**: pós-graduação (UNIPDS) a partir de jan/2027, com orquestração de LLM, RAG, arquitetura assíncrona e decisões registradas em ADR.
- **Next.js · Node.js · NestJS · Prisma**: no [DevDiary](https://devdiary.cloud), meu diário de estudos.
- **Go**: API do Auditor NF-e (`net/http`, `pgx`, `sqlc`).
- **MongoDB**: persistência poliglota nos projetos de portfólio.
- **Arquitetura de software**: outbox transacional, multi-tenant com RLS, event-driven.

### Domínio fiscal

`NF-e` · `NFC-e` · `SPED` · `ICMS-ST` · `PIS/COFINS` · `DIFAL` · `NCM` · `CFOP` · `RICMS-SC` · integração com `SEFAZ`

### Projetos em destaque

| Projeto | O que é |
|---|---|
| **[OKM Cobranças](https://okmcobrancas.com.br)** | Meu TCC, no ar. SaaS multi-tenant de cobrança com PIX (QR Code), automação e análise de logs com IA. Isolamento por tenant com RLS no PostgreSQL. FastAPI · PostgreSQL · React 19 · Docker. |
| **[Auditor NF-e](https://github.com/ThiagoHeckler/auditor-nfe)** | Recebe XMLs de NF-e, aplica regras fiscais (DV da chave, CFOP × destino, CFOP × tipo...) e, nos casos ambíguos, um LLM orquestrado com LangGraph explica o que o contador deve conferir. Go · Python · LangGraph · S3/SQS (LocalStack) · PostgreSQL. |
| **[RAG Fiscal](https://github.com/ThiagoHeckler/rag-fiscal)** | Assistente que responde sobre RICMS-SC, NCM e CFOP citando a fonte de cada afirmação, e diz "não encontrei" em vez de inventar. Busca híbrida + rerank, citações validadas no código. Python · LangChain · FastAPI · pgvector. |
| **Girô** | Marketplace + estoque com reposição automática: dois serviços Spring Boot conversando por outbox transacional, expedição FEFO e classificação de produtos com LLM. Java 25 · Spring Boot 4 · PostgreSQL · Testcontainers · React. |
| **BaseFit (Mais Músculo)** | Nasceu como sistema sob encomenda para a academia Mais Músculo e virou produto para personal trainers, no ar. Alunos, fichas de treino montadas a partir de um catálogo de exercícios, envio ao aluno pelo WhatsApp com link assinado, avaliação física com cálculos automáticos e gráficos de evolução, PDFs. Laravel 12 · Livewire 3 · Pest · Tailwind 4 · MySQL · Docker. |
| **Automação Fiscal** | Automação do dia a dia de um escritório de contabilidade (39 empresas, 90+ com filiais). O n8n orquestra os fluxos: organiza os XMLs que chegam por e-mail e pela API do SIEG, faz a conferência das notas da SEFAZ-MT e alimenta um painel multiusuário com o passo a passo de cada empresa, as pendências de SPED e o histórico do que foi feito. Também inclui um scraper da SEFAZ-MT com login por certificado A1. n8n · Laravel 12 · Livewire · Python · Playwright · Docker. |

> Os demais repositórios estão fixados no meu perfil.

### Estatísticas
<div align="center">
  <a href="https://github.com/thiagoheckler">
    <img src="https://medeiro-stats.vercel.app/api/stats?user=thiagoheckler" alt="GitHub Stats" />
  </a>
</div>

### Contato

[![Site](https://img.shields.io/badge/Site-thiagoheckler.com.br-F4A81D?style=for-the-badge&logoColor=0D1B2A)](https://thiagoheckler.com.br/)
[![DevDiary](https://img.shields.io/badge/DevDiary-devdiary.cloud-2DD4BF?style=for-the-badge&logoColor=0D1B2A)](https://devdiary.cloud/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1B2A?style=for-the-badge&logo=linkedin&logoColor=EAF0F6)](https://www.linkedin.com/in/thiago-heckler/)
[![Email](https://img.shields.io/badge/Email-0D1B2A?style=for-the-badge&logo=gmail&logoColor=EAF0F6)](mailto:thiagoecheckler@gmail.com)
