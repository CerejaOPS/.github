<div align="center">
  <h1>🍒 CerejaOPS</h1>
  <p><b>A real-time, gamified task manager with native Discord integration.</b></p>
</div>

---

## 🎯 O que é o Cereja Kanban?
O Cereja Kanban é um ecossistema ágil de gestão de tarefas em tempo real. Muito além de um simples quadro no estilo Trello, a plataforma foi arquitetada para alavancar a produtividade de times de desenvolvimento através de duas verticais principais: **Gamificação** (experiência, níveis e conquistas) e **Integração Nativa com o Discord** (autenticação, notificações push e webhooks).

## 🚀 Nossa Missão
Nossa missão com a **CerejaOPS** é dupla:
1. **Produto:** Entregar uma ferramenta de gestão imersiva, focada na retenção de engajamento do time através de recompensas visuais.
2. **Engenharia (The Academy):** Servir como um laboratório corporativo de altíssimo nível. O projeto é o terreno onde aplicamos, na prática, os padrões mais rígidos da indústria de software (Clean Architecture, Feature-Sliced Design e CI/CD), transformando estudantes e desenvolvedores juniores em engenheiros de software de elite.

## 🏗️ Arquitetura e Repositórios
O ecossistema é quebrado em microsserviços/repositórios especializados:

* **[cereja-kanban-api](https://github.com/CerejaOPS/cereja-kanban-api)**: O motor de regras de negócio. Construído puramente sobre os princípios de **Clean Architecture**, garantindo que o Domínio seja independente do framework (Spring Boot) e do Banco de Dados (PostgreSQL). Fornece comunicação assíncrona com o frontend via *Server-Sent Events (SSE)*.
* **[cereja-kanban-frontend](https://github.com/CerejaOPS/cereja-kanban-frontend)**: A interface do usuário. Aplicação React (TypeScript) arquitetada sob o padrão **Feature-Sliced Design (FSD)**, utilizando TailwindCSS e Shadcn UI para entregar uma experiência fluida e dark-themed.
* *(Em breve)* **cereja-discord-bot**: O serviço de mensageria que escuta os webhooks da API principal e interage diretamente nos servidores do Discord.

## ⚙️ Stack Tecnológica
- **Backend:** Java 17, Spring Boot, Spring Data JPA, PostgreSQL.
- **Frontend:** React, TypeScript, TailwindCSS, Shadcn UI, Vite.
- **DevOps & Qualidade:** Conventional Commits, Husky, Commitlint, GitHub Actions.

## 🤝 O Time (A Estrutura)
Não acreditamos em donos de área. Operamos sob um fluxo **Ágil Rotativo**, onde a hierarquia dá espaço à colaboração extrema:
- **1 Product Manager:** Focado na visão do produto, gestão do Backlog (Jira) e aprovação de PRs estratégicos.
- **4 Engenheiros Full-Stack:** Desenvolvem de ponta a ponta, sem silos. Qualquer desenvolvedor tem autonomia para assumir qualquer task de qualquer camada do software.
- **Liderança Mensal:** A cada mês, um desenvolvedor assume o papel de documentar e contar a história das entregas, garantindo que o conhecimento nunca fique centralizado.

---
<div align="center">
  <i>Construído com disciplina, código limpo e muita transpiração.</i>
</div>
