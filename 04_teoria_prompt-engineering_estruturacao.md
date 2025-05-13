# 🏗️ Estruturação e Refinamento de Prompts

<!-- summary:start -->
> Esta seção apresenta técnicas para estruturar e refinar prompts, como Least-to-Most Prompting, Generated Knowledge, ReAct, Self-Refine e Maieutic Prompting, com exemplos e aplicações.
<!-- summary:end -->

## 🪜 Least-to-Most Prompting

**Como funciona:**
Divide problemas complexos em subproblemas mais simples, resolvendo-os em ordem crescente de dificuldade. O modelo é guiado a abordar etapas menores antes de atacar o problema maior.

**Quando usar:**
- Problemas que podem ser decompostos em etapas
- Questões de lógica, matemática ou programação
- Situações em que o modelo se perde em problemas muito grandes

**Exemplos de prompts:**
> Primeiro, identifique as partes do problema. Depois, resolva cada parte em ordem de dificuldade crescente: Como calcular a média ponderada de três notas?
>
> Divida o seguinte desafio em etapas menores e resolva cada uma: Como construir um pipeline de dados do zero?
>
> Liste os subproblemas para organizar um evento corporativo e resolva-os do mais simples ao mais complexo.

**Exemplos aplicados a projetos de tecnologia:**
> Divida o processo de deploy contínuo em etapas menores e resolva cada uma, do setup do repositório até a automação dos testes.
>
> Liste os subproblemas para implementar autenticação multifator em um sistema web e resolva-os do mais simples ao mais complexo.
>
> Separe em etapas a criação de um data warehouse, começando pela modelagem até a integração de fontes externas.
>
> Quebre o desafio de migrar um sistema legado para a nuvem em subproblemas e resolva-os em ordem de dificuldade.
>
> Divida a tarefa de monitorar performance de microserviços em etapas e explique como resolver cada uma.

## 🧠 Generated Knowledge Prompting

**Como funciona:**
Solicita ao modelo que gere conhecimentos relevantes antes de resolver o problema principal. O modelo "prepara o terreno" trazendo fatos, conceitos ou dados úteis para a solução.

**Quando usar:**
- Tarefas que dependem de contexto ou conhecimento prévio
- Resolução de problemas abertos ou de pesquisa
- Quando o modelo pode se beneficiar de brainstorming antes da resposta

**Exemplos de prompts:**
> Antes de responder, liste fatos importantes sobre a fotossíntese. Agora, explique por que ela é essencial para as plantas.
>
> Gere conhecimentos relevantes sobre segurança em APIs REST antes de sugerir boas práticas.
>
> Quais conceitos matemáticos são necessários para resolver uma equação de segundo grau? Agora, resolva x² - 5x + 6 = 0.

**Exemplos aplicados a projetos de tecnologia:**
> Liste conhecimentos essenciais sobre arquitetura de microsserviços antes de propor uma solução para escalabilidade.
>
> Gere fatos relevantes sobre bancos de dados NoSQL antes de recomendar um para um sistema de alta disponibilidade.
>
> Quais práticas de segurança são importantes ao expor APIs públicas? Agora, sugira como proteger endpoints sensíveis.
>
> Liste conceitos de machine learning necessários para implementar um sistema de recomendação e, em seguida, proponha um modelo.
>
> Gere informações sobre técnicas de ETL antes de sugerir uma arquitetura para integração de dados.

## 🤖 ReAct (Reasoning + Acting)

**Como funciona:**
Alterna entre raciocínio e ações, permitindo que o modelo planeje, execute e observe resultados iterativamente. O modelo pode, por exemplo, raciocinar, buscar informações e depois agir novamente.

**Quando usar:**
- Tarefas que envolvem busca, execução de comandos ou múltiplas etapas
- Problemas que exigem interação com ferramentas externas
- Processos iterativos de análise e ação

**Exemplos de prompts:**
> Pesquise sobre a história da internet, explique seu raciocínio e mostre as etapas da busca.
>
> Analise um texto, destaque palavras-chave e depois resuma o conteúdo.
>
> Planeje uma consulta SQL, execute mentalmente e explique o resultado obtido.

**Exemplos aplicados a projetos de tecnologia:**
> Analise logs de erro, identifique padrões e proponha ações corretivas para um sistema distribuído.
>
> Busque informações sobre frameworks de frontend, compare-os e sugira o mais adequado para um projeto de alta performance.
>
> Planeje a criação de um script de automação, execute mentalmente cada etapa e explique os resultados esperados.
>
> Investigue possíveis causas para lentidão em um banco de dados, proponha hipóteses e ações de teste.
>
> Analise requisitos de um sistema, proponha uma arquitetura e revise a proposta após simular cenários de uso.

## 🔄 Self-Refine

**Como funciona:**
Processo iterativo onde o modelo avalia e melhora suas próprias respostas, promovendo autocrítica e refinamento. O modelo revisa, corrige e aprimora a resposta inicial.

**Quando usar:**
- Quando a qualidade da resposta é crítica
- Para tarefas de escrita, revisão ou geração de código
- Em contextos de melhoria contínua

**Exemplos de prompts:**
> Gere uma resposta para a pergunta abaixo, depois revise e melhore sua própria resposta: O que é machine learning?
>
> Escreva um parágrafo sobre sustentabilidade e, em seguida, refine para torná-lo mais claro e objetivo.
>
> Crie um código Python para inverter uma string e depois otimize o código gerado.

**Exemplos aplicados a projetos de tecnologia:**
> Escreva um script para backup de banco de dados, revise e otimize para maior eficiência.
>
> Gere um plano de testes para uma API REST, revise e melhore a cobertura dos casos de teste.
>
> Crie um template de documentação técnica, refine para torná-lo mais claro e padronizado.
>
> Implemente uma função de validação de dados em Python, revise e otimize para performance.
>
> Escreva um e-mail de comunicação de incidente, revise para torná-lo mais objetivo e informativo.

## 📚 Referências

- [Referências Oficiais e Papers](08_referencias_prompt-engineering.md)
- [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models (paper)](https://arxiv.org/abs/2210.00720)
- [ReAct: Synergizing Reasoning and Acting in Language Models (paper)](https://arxiv.org/abs/2210.03629)
- [Maieutic Prompting: Logically Consistent Reasoning with Recursive Explanations (paper)](https://arxiv.org/abs/2210.07183)
- [Awesome Prompt Engineering (repositório)](https://github.com/promptslab/Awesome-Prompt-Engineering) 