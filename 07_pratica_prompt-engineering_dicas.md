---
title: "Dicas, Convenções e Boas Práticas em Engenharia de Prompt"
description: "Recomendações práticas, convenções de mercado e checklist para criação de prompts eficazes."
author: "Equipe GenAI"
created_date: "2024-06-10"
updated_date: "2024-06-10"
version: "1.0"
status: "draft"
confidence: "high"
tags:
  - dicas
  - boas-praticas
  - engenharia-de-prompt
categories:
  - Tutorial
  - Prática
language: "pt-BR"
related_docs: []
knowledge_graph:
  concepts:
    - id: "CONCEPT_PROMPT_ENG"
      name: "Engenharia de Prompt"
  relationships: []
---

<!-- SEMANTIC_ID: DICAS_PROMPT_ENG_07 -->
<!-- KNOWLEDGE_DOMAIN: IA/LLM/Prompt Engineering/Prática -->
<!-- SEMANTIC_CONFIDENCE: HIGH -->

# 📝 Dicas, Convenções e Boas Práticas

<!-- summary:start -->
> Recomendações práticas, convenções de mercado e checklist para criar prompts claros, robustos e eficazes, baseados em papers e experiência de mercado.
<!-- summary:end -->

## 💡 Dicas Práticas

- Seja explícito: detalhe o que espera do modelo
- Use exemplos (few-shot) para orientar o padrão de resposta
- Defina formato e restrições quando necessário
- Teste variações e compare resultados
- Prefira prompts curtos e objetivos, mas com contexto suficiente
- Use linguagem clara e sem ambiguidade

## 📏 Convenções de Mercado

- Inicie prompts complexos com "Vamos pensar passo a passo"
- Para tarefas de classificação, peça respostas em formato estruturado (ex: JSON)
- Para sumarização, defina limite de palavras ou tópicos
- Use "Aja como..." para simular papéis

## ☑️ Checklist de Qualidade

<quality-checklist>
- [ ] O prompt é claro e objetivo?
- [ ] O formato da resposta está definido?
- [ ] Há exemplos suficientes (few-shot) se necessário?
- [ ] O contexto é suficiente para a tarefa?
- [ ] O prompt evita ambiguidade?
- [ ] O resultado foi testado e validado?
</quality-checklist>

## 📚 Referências {#referencias}

- [Referências Oficiais e Papers](08_referencias_prompt-engineering.md) 