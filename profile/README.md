<div align="center">

  # 🍒 Cereja
  ### *The Anti-Jira: Lightning-fast, gamified, and built for the next generation of builders.*

  <p align="center">
    <b>A plataforma ágil que transforma o caos de projetos acadêmicos e squads em ritmo e engajamento.</b>
  </p>

</div>

---

## ⚡ O Manifesto: Por que estamos construindo isso?

As ferramentas tradicionais de gestão foram desenhadas em 2005 para a burocracia de grandes corporações. Elas são **lentas, intimidadoras, caras e frias**. 

Por outro lado, o ambiente educacional e universitário ficou preso a sistemas arcaicos que funcionam apenas como depósitos de PDFs com prazos de entrega.

O **Cereja** nasce para fechar esse abismo:
> Uma experiência de gestão com a **velocidade do Linear**, a **gamificação do Discord** e a **simplicidade que a educação sempre mereceu**.

---

## 🕹️ O Motor Duplo: Duas experiências em uma única tela

Diferente de gerenciadores genéricos que só servem quando você tem reunião, o Cereja é o **painel central da rotina do usuário**:

| 🎯 Visão Individual (Painel Pessoal) | 🚀 Squads & Projetos (Fluxo Coletivo) |
| :--- | :--- |
| • **Rotina de Estudos:** Gestor diário para matérias, provas e exercícios | • **Fluxo Ágil:** Colunas Kanban com regras rígidas de transição |
| • **Prazos & Checklists:** Acompanhamento de entregas individuais | • **Indicadores Visuais:** Cores dinâmicas de prioridade e alerta de urgência 🔥 |
| • **Constância Diária:** Hábitos de foco para combater a procrastinação | • **Auditoria & Histórico:** Registro de quem moveu cada tarefa |

> 🎮 **Camada Unificada de Gamificação & Comunidade:**  
> *XP por entrega • Níveis de evolução • Insígnias de conquista • Integração direta com o Discord*

---

## 💎 Os 3 Grandes Diferenciais

### 1. 🎮 Gamificação Real (O Fim da Procrastinação)
O ato de concluir uma tarefa não deve ser burocrático, deve ser recompensador. Cada entrega gera **XP, progressão de nível e medalhas**, sincronizadas diretamente onde a comunidade já se comunica (**Discord**).

### 2. 🔌 Filosofia Plug-and-Play (Zero Resistência)
Não exigimos que universidades ou plataformas EAD substituam seus sistemas de ensino. O Cereja foi arquitetado para **rodar embutido dentro de portais acadêmicos (via LTI e APIs abertas)**. Você não migra nada; você apenas adiciona um motor ágil e moderno ao seu portal.

### 3. 👁️ Telemetria Pedagógica para Docentes
O professor deixa de ser um "cobrador de prazos no escuro" para se tornar um mentor: ele visualiza em tempo real a velocidade de cada equipe, os gargalos e quem realmente está colocando a mão na massa no projeto.

---

## 🏛️ Engenharia de Elite (The Academy)

Este repositório é também um **laboratório de engenharia de software de alto nível**. Não construímos protótipos frágeis; aplicamos os padrões mais sólidos da indústria desde a primeira linha de código:

* **Clean Architecture no Backend:** O domínio de regras de negócio é 100% puro e agnóstico de frameworks, blindado contra acoplamento.
* **Frontend Reativo e Sem Inchaço:** React 19 com **CSS Modules**, eliminando classes globais poluídas e priorizando **UI otimista** (respostas visuais instantâneas).
* **Guardiões de Qualidade:** Pipelines com **ArchUnit** para impedir violações arquiteturais e **Commitlint** garantindo rastreabilidade histórica.
* **Cultura Sem Silos:** Engenheiros full-stack com autonomia de ponta a ponta (Controller ➔ Service ➔ Banco ➔ Interface), com ciclos rotativos de liderança técnica.

---

## 🗺️ Mapa de Repositórios

| Repositório | Papel | Stack Principal |
| :--- | :--- | :--- |
| **[`cereja-kanban-api`](https://github.com/CerejaOPS/cereja-kanban-api)** | Motor de Negócios e Persistência | Java 21, Spring Boot, JPA, PostgreSQL, Docker |
| **[`cereja-kanban-frontend`](https://github.com/CerejaOPS/cereja-kanban-frontend)** | Interface do Usuário e Interações | React 19, TypeScript, Vite, CSS Modules, dnd-kit |
| *(Em breve)* **`cereja-discord-bot`** | Gateway de Mensageria e Recompensas | TypeScript, Discord.js, Webhooks |

---

## ⚡ Quickstart (Ambiente Completo em 2 Minutos)

```bash
# 1. Clone o projeto e acesse o diretório
git clone https://github.com/CerejaOPS/cereja-kanban-api.git
cd cereja-kanban-api

# 2. Suba o PostgreSQL de produção
docker compose up db -d

# 3. Inicie o Backend Spring Boot
./mvnw spring-boot:run
# -> API ativa em: http://localhost:8080/api/health

# 4. Em outro terminal, inicie o Frontend
cd ../cereja-kanban-frontend
npm install && npm run dev
# -> Interface ativa em: http://localhost:5173
```

---

<div align="center">
  <sub>Construído com obsessão por velocidade, código limpo e disciplina de engenharia.</sub><br>
  <b>CerejaOPS • 2026</b>
</div>
