<div align="center">

# Nathan Ferreira de Lima

### Mechatronics · Electrical Systems · Embedded Systems · Software · AI

**Building systems where hardware, electrical engineering and software meet.**

Brazil 🇧🇷

[Português](#português)

</div>

---

> From electrical signals and microcontrollers to APIs, databases and AI agents — I like working exactly where the physical and digital worlds meet.

I'm a **Mechatronics Technician** working at the intersection of **electrical systems, industrial automation, embedded electronics and software development**.

Most of my projects start with a real engineering problem: a test instrument, a protection system, an industrial process or an operational workflow. From there, I build the hardware/software bridge needed to measure, control, automate and improve it.

## What I'm building now

My current work is centered around three connected fronts:

### E&S Platform

A new **multi-tenant operational platform** for engineering and field-service companies, built as a modular monolith with **FastAPI, Next.js and PostgreSQL**.

Recent work includes:

- multi-tenant customer, contact and quotation domains
- migration and synchronization with a legacy Streamlit/SQLite ERP
- a canonical Messaging Core for business conversations
- real SMTP outbound and incremental IMAP inbound
- e-mail threading and conversation reconstruction
- deterministic commercial follow-up with persisted attempts and idempotency
- explicit proposal-recipient/contact handling across legacy and new platform
- auditability, retry safety and progressive replacement of legacy workflows
- preparation for AI-assisted inbound handling through **Volt**, an agent designed to operate on top of the same messaging and domain services used by humans

The main architectural idea is to replace the legacy system gradually without losing the business rules already validated in production.

### Electrical test equipment & embedded instrumentation

I continue developing and modernizing electrical test equipment involving **PIC and STM32 microcontrollers**, PC software and power electronics.

Current work includes:

- modernization of a current-injection/test suitcase with PC control and parallel HMI
- external TRIAC controllers and phase-angle control
- UART communication and bootloader workflows
- migration toward newer PIC architectures
- acquisition and control firmware for electrical measurements
- STM32-based instrumentation for circuit-breaker testing
- hardware/software protocols designed for repeatable commissioning and protection tests

### Operational automation & integrations

I also work on automating real business processes around engineering services, including:

- quotation approval and sales synchronization with Conta Azul
- customer/contact data quality and import/export workflows
- automatic commercial follow-up
- e-mail-driven workflows
- AI-assisted scope generation and operational support
- progressive integration between engineering, commercial and administrative systems

---

## What I work on

### ⚡ Electrical & Industrial Systems

- Medium- and low-voltage electrical systems
- Protection relays and protection studies
- Commissioning and electrical testing
- Preventive and corrective maintenance
- Electrical diagnostics and instrumentation
- Industrial automation

### 🔬 Embedded Systems

I work with embedded hardware and firmware involving:

- PIC and STM32 microcontrollers
- UART and USB HID communication
- Bootloaders and firmware update flows
- ADC acquisition and calibration
- TRIAC phase control
- Human-machine interfaces
- PC ↔ embedded-device protocols
- Test and measurement equipment

A recurring theme in my work is **modernizing legacy electrical test equipment without losing behavior already validated in the field**.

### 💻 Software Engineering

My engineering projects increasingly evolve into complete software products.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" alt="Linux" />
</p>

Areas I have been working with:

- REST APIs and backend services
- PostgreSQL and database migrations
- Modular monoliths and multi-tenant systems
- PWAs and responsive web applications
- Desktop applications with PySide6 / Qt
- Automated testing and CI
- Messaging systems, e-mail ingestion and outbound delivery
- Idempotent background workflows and follow-up automation
- Legacy-system modernization
- Engineering software for electrical test systems

### 🏢 ERP & Business Systems

I also have hands-on experience designing and evolving **ERP and internal management systems** for service-oriented operations.

This includes work on:

- customer, location and contact management
- quotations, costing and pricing workflows
- services, resources and labor management
- work orders and scheduling
- fleet, mileage and field-operation workflows
- logistics and operational costs
- roles, permissions and auditability
- multi-tenant architecture
- migration from legacy SQLite systems to PostgreSQL
- progressive replacement of legacy applications while preserving business rules and historical data
- integrations and synchronization with external business platforms
- e-mail messaging and automated commercial follow-up

What interests me most in ERP development is not just building screens, but translating real operational rules into software without losing the knowledge already embedded in the business.

### 🤖 Artificial Intelligence

I'm especially interested in AI as an **engineering tool**, not just a chat interface.

My current work includes:

- AI-assisted software development
- Autonomous development agents
- Tool-calling LLMs
- Agent workflows over business systems
- Human-in-the-loop AI for commercial conversations
- Local and cloud model infrastructure
- Deterministic validation around AI systems
- Natural-language interfaces over structured data
- AI-assisted legacy modernization

---

## Featured project

### [AI Sales Agent](https://github.com/nathanflima99/ai-sales-agent-challenge)

An AI agent that answers natural-language questions over a dataset with more than **200,000 sales records**.

The architecture separates language reasoning from numerical computation:

> **The LLM interprets and explains. DuckDB calculates.**

Instead of trusting the model to invent or calculate business numbers, queries are executed directly against the dataset and the generated SQL remains visible and auditable.

Technologies include **Python, FastAPI, DuckDB, Docker, LLM tool calling, OpenAI/Ollama integration and automated tests**.

---

## How I think about engineering

```text
Understand the physical system
            ↓
Measure what actually happens
            ↓
Model the behavior
            ↓
Automate what is repeatable
            ↓
Build the software around reality
```

I believe good engineering is less about choosing the newest technology and more about understanding **where reality can prove our assumptions wrong**.

---

## Currently exploring

- Industrial AI and AI agents connected to real operational systems
- Messaging automation and human-in-the-loop agents
- Embedded instrumentation for electrical testing
- Protection-relay and circuit-breaker test systems
- Modern PIC and STM32 firmware architectures
- Hardware/software integration for measurement and control
- Multi-tenant ERP architecture
- Legacy modernization with progressive migration
- AI-assisted software engineering

---

<div align="center">

**Hardware deserves good software. Software deserves contact with reality.**

</div>

---

# Português

<details>
<summary><strong>🇧🇷 Ver versão em Português</strong></summary>

<br>

## Nathan Ferreira de Lima

### Mecatrônica · Sistemas Elétricos · Sistemas Embarcados · Software · IA

**Construindo sistemas onde hardware, engenharia elétrica e software se encontram.**

> De sinais elétricos e microcontroladores a APIs, bancos de dados e agentes de IA — gosto de trabalhar exatamente onde o mundo físico encontra o digital.

Sou **Técnico em Mecatrônica** e atuo na interseção entre **sistemas elétricos, automação industrial, eletrônica embarcada e desenvolvimento de software**.

Grande parte dos meus projetos começa com um problema real de engenharia: um equipamento de ensaio, um sistema de proteção, um processo industrial ou um fluxo operacional. A partir daí, desenvolvo a ponte entre hardware e software necessária para medir, controlar, automatizar e melhorar esse processo.

### O que estou construindo agora

Meu trabalho atual está concentrado em três frentes que acabam se conectando.

#### E&S Platform

Uma nova **plataforma operacional multi-tenant** para empresas de engenharia e serviços de campo, construída como monólito modular com **FastAPI, Next.js e PostgreSQL**.

Os avanços mais recentes incluem:

- domínios multi-tenant de clientes, contatos e propostas
- migração e sincronização com ERP legado em Streamlit/SQLite
- Messaging Core canônico para conversas comerciais
- envio real por SMTP e recebimento incremental por IMAP
- threading de e-mails e reconstrução de conversas
- follow-up comercial determinístico com tentativas persistidas e idempotência
- definição explícita do contato destinatário da proposta entre legado e nova plataforma
- auditoria, retry seguro e substituição progressiva dos fluxos legados
- preparação do **Volt**, agente de IA para mensagens inbound construído sobre os mesmos serviços de domínio e mensageria utilizados pelos usuários humanos

A ideia arquitetural principal é substituir o sistema legado gradualmente, sem perder regras de negócio que já foram validadas em produção.

#### Equipamentos de ensaio & instrumentação embarcada

Continuo desenvolvendo e modernizando equipamentos de ensaio elétrico envolvendo **microcontroladores PIC e STM32**, software para PC e eletrônica de potência.

O trabalho atual inclui:

- modernização de mala de injeção/ensaio de corrente com controle por PC e IHM paralela
- controladores externos com TRIAC e controle por ângulo de fase
- comunicação UART e fluxos de bootloader
- migração para arquiteturas PIC mais novas
- firmware de aquisição e controle para grandezas elétricas
- instrumentação baseada em STM32 para ensaios de disjuntores
- protocolos hardware/software voltados a comissionamento e ensaios de proteção repetíveis

#### Automação operacional & integrações

Também trabalho na automação de processos reais ligados à prestação de serviços de engenharia, incluindo:

- aprovação de propostas e sincronização de vendas com o Conta Azul
- qualidade cadastral de clientes/contatos e fluxos de importação/exportação
- follow-up comercial automático
- workflows baseados em e-mail
- geração de escopos assistida por IA e suporte operacional
- integração progressiva entre engenharia, comercial e administrativo

### ⚡ Sistemas Elétricos & Industriais

- Sistemas elétricos de média e baixa tensão
- Relés de proteção e estudos de proteção
- Comissionamento e ensaios elétricos
- Manutenção preventiva e corretiva
- Diagnóstico elétrico e instrumentação
- Automação industrial

### 🔬 Sistemas Embarcados

Trabalho com hardware e firmware envolvendo:

- Microcontroladores PIC e STM32
- Comunicação UART e USB HID
- Bootloaders e atualização de firmware
- Aquisição e calibração por ADC
- Controle de fase com TRIAC
- Interfaces homem-máquina
- Protocolos entre PC e dispositivos embarcados
- Equipamentos de teste e medição

Um tema recorrente nos meus projetos é a **modernização de equipamentos elétricos legados sem perder comportamentos já validados em campo**.

### 💻 Engenharia de Software

Meus projetos de engenharia vêm evoluindo cada vez mais para produtos de software completos.

Áreas em que venho trabalhando:

- APIs REST e serviços backend
- PostgreSQL e migrações de banco de dados
- Monólitos modulares e sistemas multi-tenant
- PWAs e aplicações web responsivas
- Aplicações desktop com PySide6 / Qt
- Testes automatizados e CI
- Sistemas de mensageria, ingestão e envio de e-mails
- Workflows idempotentes e automação de follow-up
- Modernização de sistemas legados
- Software de engenharia para sistemas de ensaio elétrico

### 🏢 ERP & Sistemas de Gestão

Também tenho experiência prática no desenvolvimento e evolução de **ERPs e sistemas internos de gestão** voltados a operações de prestação de serviços.

Esse trabalho envolve:

- gestão de clientes, unidades e contatos
- orçamentos, custos e formação de preços
- serviços, recursos e mão de obra
- ordens de serviço e agendamentos
- frota, quilometragem e operações de campo
- logística e custos operacionais
- perfis, permissões e auditoria
- arquitetura multi-tenant
- migração de sistemas legados em SQLite para PostgreSQL
- substituição progressiva de aplicações legadas preservando regras de negócio e histórico
- integrações e sincronização com plataformas externas de gestão
- mensageria por e-mail e follow-up comercial automático

O que mais me interessa em ERP não é apenas construir telas, mas **transformar regras operacionais reais em software sem perder o conhecimento que já existe dentro do negócio**.

### 🤖 Inteligência Artificial

Tenho interesse especial em IA como **ferramenta de engenharia**, e não apenas como interface de conversa.

Atualmente venho trabalhando com:

- Desenvolvimento de software assistido por IA
- Agentes autônomos de desenvolvimento
- LLMs com tool calling
- Workflows de agentes sobre sistemas de negócio
- IA human-in-the-loop para conversas comerciais
- Infraestrutura para modelos locais e em nuvem
- Validação determinística ao redor de sistemas de IA
- Interfaces em linguagem natural para dados estruturados
- Modernização de sistemas legados assistida por IA

### Projeto em destaque

#### [AI Sales Agent](https://github.com/nathanflima99/ai-sales-agent-challenge)

Agente de IA capaz de responder perguntas em linguagem natural sobre um conjunto com mais de **200 mil registros de vendas**.

A arquitetura separa o raciocínio linguístico do cálculo numérico:

> **O LLM interpreta e explica. O DuckDB calcula.**

Em vez de confiar ao modelo a geração de números de negócio, as consultas são executadas diretamente sobre os dados, mantendo o SQL gerado visível e auditável.

### Como eu penso engenharia

```text
Entender o sistema físico
          ↓
Medir o que realmente acontece
          ↓
Modelar o comportamento
          ↓
Automatizar o que é repetível
          ↓
Construir o software ao redor da realidade
```

Acredito que boa engenharia tem menos a ver com escolher a tecnologia mais nova e mais a ver com entender **onde a realidade pode provar que nossas suposições estavam erradas**.

### Atualmente explorando

- IA industrial e agentes conectados a sistemas operacionais reais
- Automação de mensageria e agentes human-in-the-loop
- Instrumentação embarcada para ensaios elétricos
- Sistemas de ensaio de relés de proteção e disjuntores
- Arquiteturas modernas de firmware PIC e STM32
- Integração hardware/software para medição e controle
- Arquitetura de ERP multi-tenant
- Modernização de legado com migração progressiva
- Engenharia de software assistida por IA

<div align="center">

**Hardware merece bom software. Software merece contato com a realidade.**

</div>

</details>
