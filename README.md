# Engenharia de Software Assistida por Inteligência Artificial

**Do desenvolvedor codificador ao orquestrador de agentes — prompt, contexto e harness como novas disciplinas de engenharia**

> Monografia apresentada ao Curso de Pós-Graduação Lato Sensu (MBA) em Engenharia de Software — 2026

**Autor:** Luis Cláudio Silveira

---

## Sobre

Esta monografia sistematiza, em chave de engenharia, os conceitos, técnicas e arquiteturas que sustentam o desenvolvimento de software assistido por IA. O trabalho organiza esse conjunto em **três disciplinas emergentes e complementares**, relacionando-as com os fundamentos consolidados da área, que permanecem necessários.

---

## Problema de Pesquisa

A consolidação dos Modelos de Linguagem de Grande Porte (LLMs) como ferramentas cotidianas de desenvolvimento provocou um deslocamento estrutural na prática da engenharia de software: **a complexidade migra da escrita de código para a especificação, a governança e a orquestração de sistemas que escrevem código**.

Diante disso, surge a pergunta: quais conceitos, técnicas e arquiteturas o engenheiro de software precisa dominar para atuar com eficácia nesse novo paradigma?

---

## As Três Disciplinas Propostas

### 1. Engenharia de Prompt (*Prompt Engineering*)
Arte e técnica de instruir modelos de linguagem de forma eficaz. Abrange:
- **Zero-shot prompting** — instruções diretas sem exemplos
- **Few-shot prompting** — exemplos no contexto guiam o modelo
- **Chain-of-Thought (CoT)** — indução de raciocínio passo a passo
- **ReAct** — ciclos de raciocínio e ação intercalados
- Critérios de seleção de técnica e o papel do parâmetro de temperatura

### 2. Engenharia de Contexto (*Context Engineering*)
Gestão disciplinada da janela de contexto como recurso finito e crítico. Abrange:
- Tokens, embeddings e limites da janela de contexto
- Degradação de desempenho e alucinação com contextos saturados
- Persistência de estado entre sessões
- **Model Context Protocol (MCP)** como mecanismo de extensão
- **Skills** como forma de modularizar e estender o conhecimento do agente
- Validação assistida por ferramentas

### 3. Engenharia de Ambiente Operacional (*Harness Engineering*)
Projeto do ambiente que governa o comportamento dos agentes em produção. Abrange:
- **Spec-Driven Development (SDD)** — desenvolvimento orientado a especificações
- Paralelização com árvores de trabalho do Git (*Git worktrees*)
- Agentes de revisão e fluxos de revisão automatizada
- Arquiteturas de agente único e multiagente
- **RAG (Retrieval-Augmented Generation)** — geração aumentada por recuperação

---

## Principais Conclusões

- A IA não substitui fundamentos de engenharia de software — ela **intensifica** a exigência deles
- O papel do desenvolvedor desloca-se de **codificador** para **coautor e orquestrador**
- As três disciplinas (prompt, contexto, harness) constituem um arcabouço útil para formação profissional e condução disciplinada de projetos
- O domínio técnico de LLMs exige novas competências de especificação, governança e arquitetura de agentes

---

## Estrutura da Monografia

| Capítulo | Tema |
|---|---|
| 1 | Introdução — contextualização, problema, objetivos e metodologia |
| 2 | O Novo Paradigma do Desenvolvimento de Software |
| 3 | Engenharia de Prompt |
| 4 | Engenharia de Contexto |
| 5 | Engenharia de Ambiente Operacional (Harness) |
| 6 | Conclusão |

---

## Palavras-chave

Engenharia de software · Inteligência artificial · Modelos de linguagem · Engenharia de contexto · Agentes de IA

---

## Download

O arquivo completo da monografia está disponível neste repositório: [`monografia.pdf`](./monografia.pdf)
