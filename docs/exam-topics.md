# Tópicos do Exame – Claude Certified Architect: Foundations

Este documento organiza os principais tópicos cobertos na certificação **Claude Certified Architect – Foundations** da Anthropic, com base em informações públicas disponíveis.

> **⚠️ Aviso:** Este conteúdo é uma compilação da comunidade com base em fontes públicas. Não representa o guia oficial do exame da Anthropic.

---

## 1. Fundamentos de Modelos de Linguagem (LLMs)

- Arquitetura Transformer e mecanismo de atenção
- Processo de treinamento: pré-treinamento e fine-tuning
- Tokenização e janelas de contexto
- Parâmetros de geração: temperatura, top-p, top-k, max tokens
- Capacidades emergentes dos LLMs
- Limitações dos LLMs: alucinações, corte de conhecimento (knowledge cutoff), viés

---

## 2. Engenharia de Prompts

- Estrutura de uma conversa com Claude: `system`, `human`, `assistant`
- Técnicas de prompting:
  - Zero-shot
  - Few-shot
  - Chain-of-Thought (CoT)
  - Tree-of-Thought (ToT)
- Princípios de clareza, especificidade e estrutura
- Controle de formato de saída (JSON, Markdown, listas)
- Prompt injection: definição, riscos e mitigação
- Boas práticas para prompts em produção

---

## 3. Uso de Ferramentas (Tool Use / Function Calling)

- Conceito de tool use em LLMs
- Definição de ferramentas com schemas JSON
- Fluxo de execução: solicitação → chamada de ferramenta → resultado → resposta
- Tratamento de erros e retentativas (retry logic)
- Ferramentas paralelas vs. sequenciais
- Segurança no uso de ferramentas (validação de inputs/outputs)

---

## 4. Arquitetura de Agentes

- Definição e características de um agente de IA
- Padrões arquiteturais:
  - ReAct (Reasoning + Acting)
  - Plan-and-Execute
  - Reflexão e auto-avaliação
- Tipos de memória em agentes:
  - In-context (janela de contexto)
  - Externa (vector stores, bancos de dados)
  - Episódica e semântica
- Sistemas multi-agente: orquestração e comunicação entre agentes
- Casos de uso de agentes em ambientes corporativos

---

## 5. Retrieval-Augmented Generation (RAG)

- Motivação: por que RAG é necessário
- Arquitetura de um pipeline RAG:
  1. Indexação de documentos
  2. Recuperação (retrieval)
  3. Geração aumentada (augmented generation)
- Embeddings: conceito e modelos populares
- Vector stores: Pinecone, Weaviate, pgvector, Chroma, FAISS
- Técnicas avançadas:
  - Re-ranking
  - RAG híbrido (keyword + semantic search)
  - HyDE (Hypothetical Document Embeddings)
  - Chunking strategies
- Métricas de avaliação de RAG: faithfulness, answer relevancy, context recall

---

## 6. Segurança e Governança em IA

- Princípios de IA responsável da Anthropic
- Constitutional AI (CAI) e RLHF
- Tipos de riscos em sistemas de IA:
  - Alucinações e desinformação
  - Viés e discriminação
  - Prompt injection e jailbreaking
  - Exposição de dados sensíveis
- Políticas de uso aceitável da Anthropic
- Responsible Scaling Policy (RSP)
- Avaliação de risco em produtos de IA
- Regulamentação relevante: GDPR, AI Act (EU), LGPD (Brasil)
- Privacidade e proteção de dados em sistemas LLM

---

## 7. Observabilidade de Sistemas LLM

- Por que observabilidade é crítica em IA em produção
- Métricas-chave a monitorar:
  - Latência (TTFT, TPS)
  - Throughput e taxa de erro
  - Custo por token e por requisição
  - Qualidade das respostas
- Logging de prompts e respostas (considerações de privacidade)
- Distributed tracing em sistemas agênticos
- Ferramentas populares: LangSmith, Langfuse, Helicone, Arize, W&B Weave
- Estratégias de cache: prompt caching, semantic caching
- Evals: avaliação automatizada de qualidade de respostas LLM
- Alertas e SLOs para sistemas de IA

---

## 📋 Resumo dos Domínios

| Domínio | Peso Estimado |
|---------|---------------|
| Fundamentos de LLMs | Alto |
| Engenharia de Prompts | Alto |
| Tool Use | Médio |
| Arquitetura de Agentes | Alto |
| RAG | Alto |
| Segurança e Governança | Médio |
| Observabilidade | Médio |

> ⚠️ Os pesos são estimativas da comunidade e não representam a distribuição oficial do exame.

---

## 🔗 Recursos de Estudo

Consulte o arquivo [`resources.md`](resources.md) para uma lista curada de materiais de estudo para cada tópico.
