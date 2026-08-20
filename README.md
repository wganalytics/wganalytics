# Wemerson Guilherme de Souza

### Tech Lead & AI Engineer · RAG · Analytics · Fundador GIULIA AI

📍 Serra, ES — Brasil &nbsp;|&nbsp; 📩 wemerson.souza@giulia-ai.com &nbsp;|&nbsp; 🌐 [giulia-ai.com](https://giulia-ai.com) · [academy.giulia-ai.com](https://academy.giulia-ai.com) &nbsp;|&nbsp; 💬 [WhatsApp](https://wa.me/5527997136867) &nbsp;|&nbsp; [![LinkedIn](https://img.shields.io/badge/LinkedIn-wganalytics-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/wganalytics)

---

## 👋 Sobre mim

```python
class WemersonGuilherme:
    role       = "Tech Lead & AI Engineer"
    company    = "GIULIA AI — Fundador"
    location   = "Serra, ES — Brasil 🇧🇷"
    experience = "18+ anos em TI, Dados e IA"
    focus      = ["RAG", "AI Engineering", "Analytics", "EdTech"]
    principle  = "Sistemas que funcionam de verdade, não só em demo."

    def what_i_build(self):
        return [
            "Ecossistemas de IA com governança real",
            "Pipelines ETL/ELT escaláveis",
            "Produtos educacionais com metodologia própria",
            "Agentes autônomos que gerenciam seu próprio ciclo de vida"
        ]
```

---

## 🐍 Contribuições

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wganalytics/wganalytics/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/wganalytics/wganalytics/output/github-contribution-grid-snake.svg"/>
  <img alt="Snake animation" src="https://raw.githubusercontent.com/wganalytics/wganalytics/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

---

## 🚀 RAG

> **9 implementações progressivas de RAG, do zero ao deploy em produção.** 471 testes, nada simulado.

Implementações progressivas  cada uma isolando uma técnica distinta — de um pipeline vanilla até roteamento adaptativo, grafos e orquestração multi-serviço. Framework 100% local, 100% privado, com seletor multi-provider de LLM (Ollama / Gemini / Grok / Groq) e governança automatizada pelo GIULIA AI Engineering Ecosystem.

| # | Projeto | Conceito | Repositório |
|:-:|---------|----------|--------------|
| 01 | **Vanilla RAG** | Baseline RAG | [giulia-rag-vanilla](https://github.com/wganalytics/giulia-rag-vanilla) |
| 02 | **Memory RAG** | RAG + Memória Persistente | [rag-memory-redis-giulia-ai](https://github.com/wganalytics/rag-memory-redis-giulia-ai) |
| 03 | **Agentic RAG** | ReAct + Tool Calling | [rag-agentic-react-giulia-ai](https://github.com/wganalytics/rag-agentic-react-giulia-ai) |
| 04 | **Corrective RAG** | CRAG + Self-Reflection | [rag-corrective-crag-giulia-ai](https://github.com/wganalytics/rag-corrective-crag-giulia-ai) |
| 05 | **Adaptive RAG** | Roteamento Dinâmico | [rag-adaptive-sse-giulia-ai](https://github.com/wganalytics/rag-adaptive-sse-giulia-ai) |
| 06 | **GraphRAG** | Graph RAG + Cypher | [rag-graphrag-giulia-ai](https://github.com/wganalytics/rag-graphrag-giulia-ai) |
| 07 | **Hybrid RAG** | BM25 + Vector + RRF | [rag-hybrid-giulia-ai](https://github.com/wganalytics/rag-hybrid-giulia-ai) |
| 08 | **HyDE RAG** | Hypothetical Doc Embeddings | [rag-hyde-giulia-ai](https://github.com/wganalytics/rag-hyde-giulia-ai) |
| 09 | **Deploy Cloud** | Orquestração Docker | [rag-deploy-cloud-giulia-ai](https://github.com/wganalytics/rag-deploy-cloud-giulia-ai) |

Cada projeto tem seu próprio repositório e roda de forma independente — todos com `requirements.txt` validado do zero (471 testes passando) e seletor multi-provider de LLM (Ollama local / Gemini / Grok / Groq).

<details>
<summary><b>📸 Governança em ação — board GARE no Jira</b></summary>
<br>

| | |
|---|---|
| **Board** — backlog, em progresso e concluído<br><img src="assets/jira/jira-board.png" width="840"/> | **Epic** — Vanilla RAG com suas 7 tasks<br><img src="assets/jira/jira-epic.png" width="840"/> |
| **Task** — subtasks e épico pai visíveis<br><img src="assets/jira/jira-task.png" width="840"/> | **Subtask** — comentário automático do agente ao concluir<br><img src="assets/jira/jira-subtask.png" width="840"/> |

</details>

---

## 🔌 MCP & A2A Series

> **8 servidores de protocolo de agentes em Python.** MCP (tools, resources, prompts) e A2A. 212 testes, nada simulado.

Implementações progressivas  cada uma isolando um conceito do protocolo — do servidor mais simples até orquestração multi-agente real (WhatsApp, Postgres, A2A).

| # | Projeto | Conceito | Repositório |
|:-:|---------|----------|--------------|
| 01 | **Ping Server** | Tools MCP mínimas | [mcp-ping-server-giulia-ai](https://github.com/wganalytics/mcp-ping-server-giulia-ai) |
| 02 | **MCP Client** | Seleção de tool por LLM | [mcp-client-giulia-ai](https://github.com/wganalytics/mcp-client-giulia-ai) |
| 03 | **Resources** | Resources parametrizados | [mcp-resources-giulia-ai](https://github.com/wganalytics/mcp-resources-giulia-ai) |
| 04 | **Prompts + Streamlit** | Prompts MCP + chat multi-provider | [mcp-prompts-streamlit-giulia-ai](https://github.com/wganalytics/mcp-prompts-streamlit-giulia-ai) |
| 05 | **Secure Server** | Autenticação por API key (bcrypt) | [mcp-secure-server-giulia-ai](https://github.com/wganalytics/mcp-secure-server-giulia-ai) |
| 06 | **WhatsApp** | Integração real via Evolution API | [mcp-whatsapp-giulia-ai](https://github.com/wganalytics/mcp-whatsapp-giulia-ai) |
| 07 | **CrewAI Text-to-SQL** | Agente + PostgreSQL somente-leitura | [mcp-crewai-giulia-ai](https://github.com/wganalytics/mcp-crewai-giulia-ai) |
| 08 | **Agent-to-Agent** | Protocolo A2A (servidor + cliente) | [mcp-agent-to-agent-giulia-ai](https://github.com/wganalytics/mcp-agent-to-agent-giulia-ai) |

Também disponível como [repositório único (giulia-mcp-series)](https://github.com/wganalytics/giulia-mcp-series), com os 8 projetos lado a lado e CI rodando os 212 testes a cada push.

<details>
<summary><b>📸 Governança em ação — projeto MCP no Jira</b></summary>
<br>

| | |
|---|---|
| **Lista** — os 8 épicos, todos concluídos<br><img src="assets/jira/mcp-list.png" width="840"/> | **Epic** — Ping Server com suas 4 tasks<br><img src="assets/jira/mcp-epic.png" width="840"/> |

**Task** — relatório de conclusão gerado automaticamente (tempo real, status final)
<img src="assets/jira/mcp-task.png" width="600"/>

</details>

### 📈 Métricas do Ecossistema

| 🐍 Arquivos Python | 📝 Linhas de Código | 🧪 Arquivos de Teste | 📋 SDDs Completos |
|:-----------------:|:------------------:|:-------------------:|:-----------------:|
| 174 | 20.401 | 40 | 8 |

| 📓 Sessões Documentadas | ⚙️ Scripts de Automação | 🔄 Boards Jira | ⏱️ Dias de Dev |
|:----------------------:|:----------------------:|:--------------:|:--------------:|
| 22 | 8 | 3 | 47 |

---

## <img src="assets/giulia-avatar.png" alt="Giulia" width="30" height="30"/> GIULIA AI Engineering Ecosystem

🔗 **Repositório público:** [wganalytics/giulia-ai-engineering-ecosystem](https://github.com/wganalytics/giulia-ai-engineering-ecosystem) — framework de governança e metodologia (RLM, SDD, TDD, automação de ciclo de vida Jira) usado em todos os projetos deste perfil.

O ecossistema não depende de um agente único — a governança está documentada no próprio monorepo, então qualquer CLI de codificação com IA (hoje: **Claude Code**, **Codex**, **Antigravity**, **OpenCode**) segue o mesmo ciclo completo de desenvolvimento ao entrar no projeto:

```
📖 Lê CONTEXTO_RLM          →  Sabe exatamente onde o projeto está
🎯 Cria ideia.md + spec      →  Planeja antes de codificar
🔄 Move cards no Jira        →  Backlog → In Progress → Done (automático)
🧪 Desenvolve com TDD        →  Red → Green → Refactor
✅ Valida o ecossistema       →  6 regras de consistência entre 5 fontes
📝 Documenta tudo            →  walkthrough.md + Diário de Bordo
🚀 Commit semântico + push   →  Entrega rastreável e auditável
```

> *"🚀 Atualização Automática (Agente AI)"* — comentário automático no Jira a cada entrega

---

## 🧠 Padrão RLM — Gerenciamento de Contexto

Inspirado no streaming de mundo aberto do GTA — carrega só a camada necessária pra responder a pergunta de agora, não o projeto inteiro de uma vez. O **RLM (Recursive Language Model)** organiza a documentação do monorepo em 5 camadas, da mais compacta pra mais profunda, para qualquer LLM retomar o projeto do zero sem perder contexto:

```
① CONTEXTO_RLM.md              ←  "Onde estou?" (30 segundos)
② DIARIO_DE_BORDO.md           ←  "O que já fizemos?"
③ MANUAL_DO_ECOSSISTEMA.md     ←  "Quais são as regras?"
④ .contexto_navegacao.md       ←  "Onde encontro X?"
⑤ governance/projects/PRJ-XX/  ←  Spec + plano do projeto ativo
```

A passagem de bastão entre sessões e agentes não fica só na memória — cada handoff de tarefa é gravado em `handoff_trace.jsonl` (um projeto, um arquivo, um evento JSON por linha): timestamp, issue do Jira, skill usada, decisão tomada, justificativa e status. O próximo agente que entrar no projeto lê o porquê da decisão anterior, não só o quê.

---

## 🛠️ Stack Técnica

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45" title="Python"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="45" title="Docker"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="45" title="FastAPI"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neo4j/neo4j-original.svg" width="45" title="Neo4j"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="45" title="Redis"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="45" title="PostgreSQL"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="45" title="GitHub"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="45" title="Linux"/>
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="45" title="VS Code"/>

</div>

<br>

<div align="center">

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLM-000000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-Multi--Provider-1E293B?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A1F?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-000000?style=flat-square)
![A2A](https://img.shields.io/badge/A2A-Agent--to--Agent-4B5563?style=flat-square)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square)

</div>

*Stack verificada nos 17 projetos publicados (9 RAG + 8 MCP/A2A) — Gemini, Grok e Groq entram como providers de LLM plugáveis via LiteLLM/seletor multi-provider, não como serviços hospedados.*

---

## 🎓 GIULIA AI Academy

> Formação executiva em IA aplicada — para quem precisa de método, não só de prompts.

**Curso principal: Auditoria 2.0**

- 📚 40 horas · 5 dias intensivos · 15 entregáveis
- 🧩 Metodologia **CTCF** (Contexto · Tarefa · Critério · Formato)
- 📊 Caso prático financeiro real (Grupo Cavalcanti — 5 empresas, DRE, Balanço, DFC)
- 🎯 Público: auditores, controllers, analistas e gestores

🔗 [academy.giulia-ai.com](https://academy.giulia-ai.com)

---

## 🏛️ Princípios de Engenharia

| Princípio | Aplicação |
|-----------|-----------|
| ✅ **Privacy-First** | Ollama local. Zero chamadas a APIs pagas no pipeline core |
| ✅ **Documentation as Code** | Nenhum projeto inicia sem spec. Nenhum encerra sem walkthrough |
| ✅ **Governance Native** | Governança não é opcional — faz parte da arquitetura |
| ✅ **TDD obrigatório** | Red → Green → Refactor em todos os projetos formais |
| ✅ **Clean Architecture** | Frontend → API → Core. Nunca acoplados diretamente |
| ✅ **Portfolio Native** | Projetos nascem preparados para showcase público |

---

## 📬 Contato

**Aberto a posições remotas de Tech Lead ou Head de IA/Dados**
*onde autonomia técnica e aprendizado contínuo façam parte da cultura.*

<div align="center">

📩 wemerson.souza@giulia-ai.com &nbsp;|&nbsp; 🌐 [giulia-ai.com](https://giulia-ai.com) · [academy.giulia-ai.com](https://academy.giulia-ai.com) &nbsp;|&nbsp; 💬 [WhatsApp](https://wa.me/5527997136867)

</div>

---

<div align="center">

*Construído com engenharia real. Sem vibe coding.*

</div>
