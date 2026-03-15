# Tópicos do Exame — Claude Certified Architect (Foundations)

> Este documento lista os principais tópicos abordados na certificação *Claude Certified Architect – Foundations* da Anthropic, com base em fontes públicas disponíveis.

> **Aviso:** Este documento é uma compilação comunitária e pode não refletir com precisão o conteúdo oficial do exame. Sempre consulte a documentação oficial da Anthropic.

---

## 1. Fundamentos de LLMs

- Arquitetura de modelos de linguagem (Transformers)
- Processo de treinamento: pré-treinamento e fine-tuning
- Reinforcement Learning from Human Feedback (RLHF)
- Tokens e tokenização
- Janela de contexto e gerenciamento de contexto
- Parâmetros de inferência: temperatura, top-p, top-k, max_tokens

---

## 2. Engenharia de Prompts

- Estrutura de mensagens na API do Claude (system, user, assistant)
- Técnicas de prompting: zero-shot, few-shot, chain-of-thought
- Prompting para controle de formato de saída
- Estratégias para respostas consistentes e determinísticas
- Mitigação de alucinações via instrução
- Boas práticas de redação de prompts para o Claude

---

## 3. Uso de Ferramentas (Tool Use)

- Declaração e definição de ferramentas na API
- Ciclo de execução tool_use / tool_result
- Ferramentas paralelas e encadeadas
- Tratamento de erros em chamadas de ferramentas
- Padrões de design para integração de ferramentas externas

---

## 4. Arquitetura de Agentes

- Definição de agente de IA e seus componentes
- Padrões de raciocínio: ReAct, Plan-and-Execute, Reflexion
- Memória em agentes: contexto de curto prazo, armazenamento externo
- Sistemas multi-agente: orquestração e comunicação entre agentes
- Avaliação e controle de loops de agentes
- Considerações de segurança em sistemas agênticos

---

## 5. Retrieval-Augmented Generation (RAG)

- Motivação para RAG: limitações de contexto e conhecimento estático
- Componentes de um pipeline RAG: indexação, recuperação, geração
- Modelos de embedding e busca vetorial
- Estratégias de chunking de documentos
- Técnicas de reranking e filtro de contexto
- Avaliação de pipelines RAG
- Comparação RAG vs. fine-tuning

---

## 6. Segurança e Governança de IA

- Princípios de IA responsável da Anthropic
- Constitutional AI: harmlessness from AI feedback
- Política de uso aceitável (Acceptable Use Policy)
- Ataques adversariais: prompt injection, jailbreaking
- Defesas e mitigações de ataques
- Privacidade e gestão de dados sensíveis
- Auditabilidade e rastreabilidade de sistemas de IA
- Riscos de sistemas agênticos autônomos

---

## 7. Observabilidade de Sistemas LLM

- Rastreamento e logging de chamadas à API
- Monitoramento de latência e custo
- Métricas de qualidade de respostas
- Ferramentas de observabilidade (LangSmith, Langfuse, Helicone, Arize)
- Estratégias de avaliação (LLM-as-a-judge, avaliação humana)
- Detecção de degradação de qualidade em produção

---

## 📌 Como Usar Este Documento

Use este arquivo como guia para organizar seus estudos. Marque os tópicos à medida que se sentir confortável com cada um. Contribuições para enriquecer ou corrigir este documento são bem-vindas — veja [`/contributions/how-to-contribute.md`](../contributions/how-to-contribute.md).
