# 🚀 Otimização de Instruções e Estratégias Avançadas

<!-- summary:start -->
> Esta seção apresenta técnicas para otimizar prompts e estratégias avançadas, como Role Prompting, Reflexion, Automatic Prompt Engineer (APE), Constrained Prompting, Directional Stimulus e ART, com exemplos e aplicações.
<!-- summary:end -->

## 🧑‍💼 Role Prompting

**Como funciona:**
Atribui um papel específico ao modelo, como "Aja como um especialista em...", para direcionar o estilo e o conteúdo da resposta. O modelo assume o papel e responde de acordo com o contexto solicitado.

**Quando usar:**
- Quando se deseja simular especialistas ou personas
- Para adaptar o tom e o nível de detalhe da resposta
- Em tarefas de simulação, atendimento ou ensino

**Exemplos de prompts:**
> Aja como um engenheiro de software sênior e explique o conceito de microserviços.
>
> Finja ser um professor de matemática e ensine como resolver uma equação do 2º grau.
>
> Você é um consultor de carreira. Dê dicas para quem quer migrar para a área de dados.

**Exemplos aplicados a projetos de tecnologia:**
> Aja como um arquiteto de soluções e proponha uma arquitetura escalável para um sistema de e-commerce.
>
> Finja ser um engenheiro de dados e explique como construir um pipeline de ingestão em tempo real.
>
> Você é um especialista em segurança. Liste os principais riscos ao expor APIs públicas.
>
> Aja como um gerente de projetos ágeis e descreva como organizar sprints para uma equipe de desenvolvimento distribuída.
>
> Finja ser um DevOps e explique como implementar CI/CD em um ambiente multi-cloud.

## 🔍 Reflexion

**Como funciona:**
Encoraja o modelo a refletir sobre tentativas anteriores e incorporar lições aprendidas, promovendo melhoria contínua. O modelo revisa respostas passadas e sugere aprimoramentos.

**Quando usar:**
- Para tarefas iterativas de escrita, código ou análise
- Quando se deseja aprendizado incremental
- Em contextos de revisão e autocrítica

**Exemplos de prompts:**
> Resolva o problema abaixo, depois reflita sobre sua resposta e sugira melhorias: Como otimizar um algoritmo de busca?
>
> Escreva um texto sobre sustentabilidade, revise e explique o que poderia ser melhorado.
>
> Gere um código para ordenar uma lista e, em seguida, analise possíveis falhas ou melhorias.

**Exemplos aplicados a projetos de tecnologia:**
> Implemente uma função de login, revise o código e sugira melhorias de segurança.
>
> Escreva um script de automação para deploy, reflita sobre possíveis falhas e otimize o processo.
>
> Gere um modelo de dados para um sistema de CRM, revise e proponha ajustes para escalabilidade.
>
> Crie um relatório de análise de logs, revise e sugira formas de automatizar a coleta de métricas.
>
> Implemente um teste unitário, revise e explique como aumentar a cobertura de testes.

## 🤖 Automatic Prompt Engineer (APE)

**Como funciona:**
Utiliza um modelo para gerar e otimizar prompts para outro modelo, automatizando o processo de engenharia de prompt. O APE propõe, testa e refina prompts para maximizar resultados.

**Quando usar:**
- Para automação de experimentos com prompts
- Em projetos de pesquisa e desenvolvimento de IA
- Quando se busca otimizar desempenho de LLMs em tarefas específicas

**Exemplos de prompts:**
> Gere 3 variações de prompt para extrair resumos de artigos científicos.
>
> Crie e teste diferentes instruções para classificar sentimentos em avaliações de produtos.
>
> Proponha prompts alternativos para melhorar a extração de entidades em textos jurídicos.

**Exemplos aplicados a projetos de tecnologia:**
> Gere variações de prompts para identificar anomalias em logs de aplicações distribuídas.
>
> Crie e teste instruções para extrair KPIs de relatórios financeiros em PDF.
>
> Proponha prompts alternativos para melhorar a classificação de tickets de suporte técnico.
>
> Gere diferentes instruções para sumarizar atas de reuniões técnicas.
>
> Crie prompts para extrair requisitos funcionais de documentos de especificação de software.

## 🛑 Constrained Prompting

**Como funciona:**
Define restrições específicas (formato, extensão, estilo) que o modelo deve seguir ao responder. O modelo é instruído a respeitar limites claros.

**Quando usar:**
- Quando o formato da resposta é crítico (ex: JSON, XML)
- Para tarefas de geração de código, relatórios ou resumos
- Em contextos regulatórios ou de padronização

**Exemplos de prompts:**
> Responda apenas em formato JSON: {"resposta": ...}
>
> Gere um resumo do texto abaixo em até 50 palavras.
>
> Escreva um e-mail formal de agradecimento com no máximo 3 parágrafos.

**Exemplos aplicados a projetos de tecnologia:**
> Gere um manifesto Kubernetes válido em YAML para um serviço web.
>
> Responda apenas com um script Bash para automatizar backup de arquivos.
>
> Escreva um relatório de status de projeto em até 100 palavras.
>
> Gere um payload de requisição HTTP em formato JSON para uma API REST.
>
> Crie um template de documentação de endpoint seguindo o padrão OpenAPI.

## ➡️ Directional Stimulus Prompting

**Como funciona:**
Orienta o modelo em uma direção específica para obter determinado tipo de resposta. O prompt sugere o foco, o estilo ou o objetivo desejado.

**Quando usar:**
- Para guiar o modelo em tarefas criativas ou abertas
- Quando se deseja controlar o viés ou o tom da resposta
- Em contextos de brainstorming ou geração de ideias

**Exemplos de prompts:**
> Foque nos benefícios ambientais ao responder sobre carros elétricos.
>
> Responda como se estivesse explicando para uma criança de 8 anos.
>
> Gere ideias inovadoras para um aplicativo de saúde mental.

**Exemplos aplicados a projetos de tecnologia:**
> Foque nos aspectos de segurança ao sugerir melhorias para uma arquitetura de microserviços.
>
> Responda como se estivesse apresentando para um CTO.
>
> Gere ideias para novos recursos em uma plataforma de análise de dados.
>
> Explique a importância de testes automatizados para uma equipe de desenvolvedores iniciantes.
>
> Sugira melhorias para um sistema legado com foco em escalabilidade.

## 🛠️ Automatic Reasoning and Tool-use (ART)

**Como funciona:**
Equipa o modelo com ferramentas externas e capacidade de raciocínio para utilizá-las eficientemente. O modelo pode planejar, executar e combinar recursos para resolver tarefas complexas.

**Quando usar:**
- Para tarefas que exigem uso de APIs, cálculos ou buscas externas
- Em fluxos de automação e integração
- Quando a tarefa envolve múltiplos passos e recursos

**Exemplos de prompts:**
> Use uma calculadora para resolver: Qual é a raiz quadrada de 225?
>
> Consulte uma API de clima e informe a previsão para amanhã em São Paulo.
>
> Combine busca na web e análise de texto para resumir as principais notícias do dia.

**Exemplos aplicados a projetos de tecnologia:**
> Use uma API de monitoramento para coletar métricas de um cluster Kubernetes e gere um relatório.
>
> Combine busca em banco de dados e análise de logs para identificar falhas em um sistema distribuído.
>
> Planeje e execute a integração de dados entre dois sistemas usando ferramentas ETL.
>
> Utilize uma calculadora de custos em nuvem para estimar o orçamento de um novo projeto.
>
> Integre resultados de diferentes APIs para compor um dashboard de indicadores de negócio.

## 📚 Referências

- [Referências Oficiais e Papers](08_referencias_prompt-engineering.md)
- [Reflexion: Language Agents with Verbal Reinforcement Learning (paper)](https://arxiv.org/abs/2303.11366)
- [Automatic Prompt Engineer (APE) (paper)](https://arxiv.org/abs/2211.01910)
- [Constrained Decoding for Text Generation (artigo)](https://huggingface.co/blog/constrained_decoding)
- [Awesome Prompt Engineering (repositório)](https://github.com/promptslab/Awesome-Prompt-Engineering) 