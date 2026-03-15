# Plano de Estudos — Claude Certified Architect (Foundations)

> Roteiro de 4 semanas para preparação para a certificação *Claude Certified Architect – Foundations* da Anthropic.

---

## 📅 Semana 1 — Fundamentos de LLMs e Engenharia de Prompts

### Objetivos
- Compreender como os grandes modelos de linguagem (LLMs) funcionam
- Aprender as técnicas fundamentais de engenharia de prompts
- Entender as capacidades e limitações do Claude

### Tópicos

**Fundamentos de LLMs**
- Arquitetura Transformer e mecanismo de atenção
- Pré-treinamento, fine-tuning e RLHF
- Tokens, contexto e janela de contexto
- Temperaturas, top-p e outros parâmetros de inferência

**Engenharia de Prompts**
- Estrutura de um prompt eficaz
- Técnicas: zero-shot, few-shot, chain-of-thought (CoT)
- Prompts de sistema vs. prompts de usuário
- Controle de formato de saída (JSON, Markdown, etc.)
- Boas práticas com o Claude (clareza, contexto, instruções explícitas)

### Recursos Recomendados
- Documentação oficial do Claude (Anthropic Docs)
- Guia de engenharia de prompts da Anthropic
- Artigo original "Attention Is All You Need"

---

## 📅 Semana 2 — Uso de Ferramentas (Tool Use) e Arquitetura de Agentes

### Objetivos
- Entender como o Claude utiliza ferramentas externas
- Compreender a arquitetura de agentes baseados em LLMs
- Implementar e testar fluxos de agentes simples

### Tópicos

**Uso de Ferramentas (Tool Use)**
- Definição e declaração de ferramentas (`tool_use`)
- Ciclo de chamada: modelo → ferramenta → modelo
- Tratamento de erros e resultados de ferramentas
- Ferramentas em paralelo e em sequência

**Arquitetura de Agentes**
- O que é um agente de IA
- Loops de raciocínio: ReAct, Plan-and-Execute, etc.
- Memória de curto e longo prazo em agentes
- Orquestração de múltiplos agentes (multi-agent)
- Considerações de segurança em sistemas agênticos

### Recursos Recomendados
- Documentação de Tool Use do Claude
- Artigo "ReAct: Synergizing Reasoning and Acting in Language Models"
- Exemplos de agentes na Anthropic Cookbook

---

## 📅 Semana 3 — Recuperação Aumentada por Geração (RAG) e Observabilidade

### Objetivos
- Implementar pipelines de RAG com o Claude
- Compreender como monitorar e observar sistemas baseados em LLMs
- Entender métricas e avaliação de qualidade de respostas

### Tópicos

**Retrieval-Augmented Generation (RAG)**
- Por que usar RAG: limitações da janela de contexto
- Arquitetura de um pipeline RAG
- Embeddings e busca por similaridade (vetorial)
- Estratégias de chunking e indexação
- Reranking e filtragem de contexto
- RAG vs. fine-tuning: quando usar cada abordagem

**Observabilidade de Sistemas LLM**
- Rastreamento de chamadas e latência
- Monitoramento de custos e uso de tokens
- Avaliação de qualidade: precisão, coerência, relevância
- Ferramentas: LangSmith, Langfuse, Helicone, Arize
- Detecção de alucinações e respostas fora do escopo

### Recursos Recomendados
- Artigo "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks"
- Documentação do LlamaIndex e LangChain
- Guias de observabilidade da Anthropic

---

## 📅 Semana 4 — Segurança, Governança e Revisão Geral

### Objetivos
- Compreender os princípios de segurança e governança de IA
- Revisar todos os tópicos anteriores
- Simular questões de exame e consolidar conhecimentos

### Tópicos

**Segurança e Governança de IA**
- Princípios de IA responsável (responsible AI)
- Política de uso aceitável (AUP) da Anthropic
- Constitutional AI e RLHF
- Prompt injection e defesas contra ataques adversariais
- Gestão de dados sensíveis em pipelines de LLM
- Conformidade, auditabilidade e rastreabilidade
- Riscos sistêmicos em sistemas agênticos autônomos

**Revisão Geral**
- Revisão de fundamentos de LLMs e prompting
- Revisão de tool use e agentes
- Revisão de RAG e observabilidade
- Revisão de segurança e governança
- Simulado de questões do exame

### Recursos Recomendados
- Política de Uso da Anthropic (Acceptable Use Policy)
- Artigo "Constitutional AI: Harmlessness from AI Feedback"
- Guia de segurança para sistemas agênticos

---

## 📌 Notas do Plano

- Este plano é um ponto de partida e pode ser ajustado conforme o progresso do grupo.
- Cada semana corresponde a aproximadamente **2 sessões de estudo** (terças e quintas).
- Ao final de cada semana, o grupo atualiza este repositório com novos materiais e aprendizados.
- Contribuições para aprimorar este plano são bem-vindas. Consulte [`/contributions/how-to-contribute.md`](../contributions/how-to-contribute.md).
