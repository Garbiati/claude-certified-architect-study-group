# Plano de Estudos – Claude Certified Architect: Foundations

Este documento apresenta o roadmap de 4 semanas do grupo de estudos para a certificação **Claude Certified Architect – Foundations** da Anthropic.

> O plano é uma sugestão de progressão e pode ser adaptado conforme o andamento das sessões e as necessidades da comunidade.

---

## 📅 Semana 1 – Fundamentos de LLMs e Engenharia de Prompts

**Objetivo:** Estabelecer uma base sólida sobre como os grandes modelos de linguagem funcionam e como se comunicar com eles de forma eficaz.

### Tópicos

- **Fundamentos de LLMs**
  - Como os modelos de linguagem são treinados (pré-treinamento e fine-tuning)
  - Arquitetura Transformer (visão geral)
  - Tokens, contexto e janelas de contexto
  - Temperatura, top-p e outros parâmetros de geração
  - Capacidades e limitações dos LLMs

- **Engenharia de Prompts**
  - Princípios de um bom prompt
  - Técnicas: zero-shot, few-shot, chain-of-thought (CoT)
  - Estrutura de prompts para Claude (system prompt, human, assistant)
  - Prompt injection e como mitigá-lo
  - Boas práticas de prompting para tarefas técnicas

### Materiais Sugeridos

- Documentação oficial da Anthropic (docs.anthropic.com)
- Guia de Prompt Engineering da Anthropic
- Artigo "Attention Is All You Need" (visão geral)

---

## 📅 Semana 2 – Uso de Ferramentas (Tool Use) e Arquitetura de Agentes

**Objetivo:** Entender como os LLMs podem interagir com ferramentas externas e como projetar sistemas agênticos.

### Tópicos

- **Tool Use (Function Calling)**
  - O que é tool use e por que é importante
  - Como definir ferramentas para o Claude (schemas JSON)
  - Ciclo de chamada de ferramenta: invocação → execução → retorno
  - Tratamento de erros em chamadas de ferramentas
  - Casos de uso: busca na web, execução de código, APIs externas

- **Arquitetura de Agentes**
  - O que é um agente de IA
  - Padrões de agentes: ReAct, Plan-and-Execute, reflexão
  - Agentes single-step vs. multi-step
  - Memória em agentes: in-context, externa (vector store, DB)
  - Orquestração de múltiplos agentes (multi-agent systems)
  - Casos de uso práticos de agentes com Claude

### Materiais Sugeridos

- Documentação de Tool Use da Anthropic
- Exemplos de agentes no Anthropic Cookbook
- Artigo "ReAct: Synergizing Reasoning and Acting in Language Models"

---

## 📅 Semana 3 – RAG e Segurança / Governança em IA

**Objetivo:** Aprender a enriquecer modelos com conhecimento externo e entender as responsabilidades éticas e de segurança em sistemas de IA.

### Tópicos

- **Retrieval-Augmented Generation (RAG)**
  - O que é RAG e por que é necessário
  - Arquitetura de um sistema RAG: indexação, recuperação e geração
  - Embeddings: o que são e como funcionam
  - Vector stores: Pinecone, Weaviate, pgvector etc.
  - Técnicas avançadas: re-ranking, RAG híbrido, HyDE
  - Avaliação da qualidade de um sistema RAG

- **Segurança e Governança em IA**
  - Princípios de IA responsável da Anthropic
  - Constitutional AI e RLHF
  - Riscos em sistemas baseados em LLMs: alucinações, viés, injeção de prompt
  - Políticas de uso aceitável
  - Avaliação de risco e mitigação em produtos de IA
  - Regulamentação e compliance (visão geral)

### Materiais Sugeridos

- Artigo "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks"
- Documentação de segurança da Anthropic
- Responsible Scaling Policy da Anthropic

---

## 📅 Semana 4 – Observabilidade de Sistemas LLM e Revisão Geral

**Objetivo:** Aprender a monitorar, depurar e otimizar sistemas baseados em LLMs, e consolidar todo o conhecimento adquirido nas semanas anteriores.

### Tópicos

- **Observabilidade de Sistemas LLM**
  - Por que observabilidade é crítica em sistemas de IA
  - Métricas principais: latência, throughput, custo por token, taxa de erro
  - Logging de prompts e respostas (privacidade e compliance)
  - Rastreamento de chamadas em sistemas agênticos (tracing)
  - Ferramentas: LangSmith, Langfuse, Helicone, OpenTelemetry
  - Estratégias de cache para redução de custo e latência
  - Avaliação contínua (evals) de qualidade de respostas

- **Revisão Geral e Simulado**
  - Revisão dos tópicos das semanas 1 a 3
  - Discussão de casos práticos e arquiteturas reais
  - Simulado de questões da certificação
  - Dúvidas e pontos de melhoria individuais

### Materiais Sugeridos

- Documentação do LangSmith e Langfuse
- Guia de Evals da Anthropic
- Revisão do conteúdo acumulado no repositório

---

## 🗓️ Cronograma das Sessões

| Semana | Terça-feira | Quinta-feira |
|--------|-------------|--------------|
| 1 | Fundamentos de LLMs | Engenharia de Prompts |
| 2 | Tool Use | Arquitetura de Agentes |
| 3 | RAG | Segurança e Governança em IA |
| 4 | Observabilidade | Revisão Geral e Simulado |

---

## 📝 Notas

- O plano pode ser ajustado conforme o progresso do grupo.
- Resumos das sessões serão publicados em [`/sessions`](../sessions/README.md).
- Sugestões de melhoria são bem-vindas via pull request ou issue.
