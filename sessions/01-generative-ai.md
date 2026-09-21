# Aula 01 — Introdução à Inteligência Artificial Generativa

> **AI at Work Labs — Como usar AI no trabalho: Prompts e Copilot na prática**

---

## 🎯 Objetivos da aula

Ao final desta aula, você deverá ser capaz de:

* Entender o que é Inteligência Artificial Generativa;
* Diferenciar IA tradicional de IA generativa;
* Entender, em termos simples, como ferramentas como ChatGPT e Copilot funcionam;
* Conhecer as principais capacidades da IA generativa;
* Reconhecer suas principais limitações;
* Identificar oportunidades de uso da IA no trabalho;
* Criar seus primeiros prompts;
* Avaliar criticamente uma resposta gerada por IA.

---

# 1. Antes de começar...

Vamos começar com uma pergunta:

> **Qual é a tarefa mais repetitiva, chata ou demorada que você realiza toda semana no trabalho?**

Pense em algo que:

* consome bastante tempo;
* você faz várias vezes;
* segue um padrão;
* envolve leitura ou escrita;
* exige organizar informações;
* poderia ser parcialmente automatizado.

### Exemplos

* Escrever e-mails;
* Fazer atas de reunião;
* Criar relatórios;
* Resumir documentos;
* Organizar informações;
* Criar apresentações;
* Analisar planilhas;
* Pesquisar informações;
* Preparar reuniões;
* Criar documentação.

**Guarde essa tarefa.**

Vamos voltar a ela no decorrer do workshop.

---

# 2. O que é Inteligência Artificial?

De forma simplificada:

> **Inteligência Artificial é um conjunto de técnicas que permite que sistemas computacionais realizem tarefas que normalmente associamos à inteligência humana.**

Entre essas tarefas estão:

* reconhecer padrões;
* interpretar linguagem;
* classificar informações;
* fazer previsões;
* recomendar conteúdos;
* identificar objetos em imagens;
* compreender comandos;
* gerar conteúdo.

A IA não é uma tecnologia única.

É um campo amplo que inclui diferentes técnicas e abordagens.

---

# 3. IA tradicional x IA Generativa

Uma forma simples de entender a diferença:

### IA tradicional

Normalmente é utilizada para:

> **analisar, classificar, prever ou decidir.**

Exemplos:

* detectar fraude;
* identificar spam;
* prever demanda;
* recomendar produtos;
* classificar documentos;
* detectar objetos em imagens.

### IA Generativa

É utilizada para:

> **gerar conteúdo novo a partir de instruções e informações fornecidas.**

Pode gerar:

* texto;
* imagens;
* código;
* áudio;
* vídeo;
* apresentações;
* resumos;
* ideias;
* análises.

---

# 4. O que significa "Generativa"?

A palavra **generativa** vem justamente da capacidade de **gerar conteúdo**.

Por exemplo, podemos pedir:

```text
Crie um e-mail profissional informando que uma reunião
precisará ser reagendada.
```

A IA pode gerar uma resposta completamente nova baseada nessa instrução.

Podemos então pedir:

```text
Agora deixe o texto mais informal e amigável.
```

E depois:

```text
Reduza para no máximo 80 palavras.
```

Estamos utilizando a IA como uma ferramenta de geração e transformação de conteúdo.

---

# 5. O que é um Large Language Model?

Ferramentas como ChatGPT e muitos recursos de Copilot utilizam modelos de linguagem de grande escala, conhecidos como **LLMs — Large Language Models**.

De forma simplificada, um LLM aprende padrões existentes em grandes quantidades de dados e utiliza esses padrões para produzir respostas.

Uma forma simples de pensar:

```text
Seu pedido
    ↓
Modelo de IA
    ↓
Processamento do contexto
    ↓
Geração da resposta
```

É importante entender que isso **não significa que a IA "pensa" exatamente como uma pessoa**.

Ela trabalha com modelos matemáticos extremamente complexos capazes de identificar e produzir padrões na linguagem e em outros tipos de dados.

---

# 6. Tokens

Modelos de linguagem não trabalham exatamente com palavras da mesma forma que nós.

O texto é dividido em unidades chamadas **tokens**.

Por exemplo:

```text
Inteligência Artificial
```

pode ser representado internamente por vários tokens.

Isso é importante porque:

* modelos possuem limites de contexto;
* o tamanho das entradas influencia o processamento;
* o tamanho das respostas também importa;
* diferentes modelos possuem diferentes capacidades de contexto.

Não precisamos dominar tokens para utilizar IA.

Mas é importante saber que existe uma representação interna diferente daquela que enxergamos como usuários.

---

# 7. O que a IA Generativa consegue fazer?

Uma das características mais interessantes da IA generativa é sua versatilidade.

## ✍️ Criar

```text
Crie uma descrição para uma vaga de desenvolvedor .NET.
```

## 🔄 Transformar

```text
Transforme este texto em um e-mail profissional.
```

## 📝 Resumir

```text
Resuma este documento em cinco pontos principais.
```

## 🔎 Analisar

```text
Analise estas informações e identifique os principais riscos.
```

## 💡 Criar ideias

```text
Sugira dez ideias para melhorar a comunicação interna da empresa.
```

## 🧠 Explicar

```text
Explique este conceito para alguém sem conhecimento técnico.
```

## 🌎 Traduzir

```text
Traduza este texto para inglês.
```

## 💻 Ajudar com código

```text
Explique o que este código C# está fazendo.
```

---

# 8. Multimodalidade

As ferramentas modernas de IA não trabalham apenas com texto.

Dependendo da ferramenta e do modelo, podemos trabalhar com:

* texto;
* imagens;
* documentos;
* planilhas;
* áudio;
* vídeo;
* código.

Por exemplo, podemos fornecer uma imagem de um gráfico e perguntar:

```text
Analise este gráfico.

Identifique:
1. as principais tendências;
2. possíveis anomalias;
3. três perguntas que eu deveria investigar.
```

Isso abre possibilidades muito maiores do que simplesmente conversar com um chatbot.

---

# 9. As principais ferramentas

Existem diversas ferramentas de IA generativa disponíveis.

Entre elas:

### ChatGPT

Uma plataforma de IA generativa com capacidades de conversação, análise, geração de conteúdo, código e outras tarefas.

### Microsoft Copilot

Família de soluções de IA integrada ao ecossistema Microsoft, incluindo recursos dentro do Microsoft 365.

### Google Gemini

Família de modelos e ferramentas de IA do Google.

### Claude

Assistente de IA desenvolvido pela Anthropic.

### Outras ferramentas

O mercado está evoluindo rapidamente.

Novos modelos, produtos e funcionalidades aparecem constantemente.

Por isso, o objetivo deste workshop **não é decorar ferramentas**.

O objetivo é aprender conceitos e habilidades que possam ser aplicados em diferentes ferramentas.

---

# 10. IA como copiloto

Uma das melhores formas de pensar na IA no ambiente profissional é:

> **IA como copiloto.**

O copiloto:

* ajuda;
* sugere;
* acelera;
* transforma;
* organiza;
* explica;
* gera alternativas.

Mas quem continua responsável pelo trabalho é o profissional.

### Um exemplo

Imagine que você precisa escrever um relatório.

Sem IA:

```text
Informações
     ↓
Leitura
     ↓
Análise
     ↓
Estrutura
     ↓
Primeira versão
     ↓
Revisão
     ↓
Relatório
```

Com IA:

```text
Informações
     ↓
      IA
     ↓
Resumo / estrutura / alternativas
     ↓
Revisão humana
     ↓
Decisão
     ↓
Relatório
```

A IA pode reduzir o trabalho mecânico.

Mas a decisão continua sendo humana.

---

# 11. Primeira demonstração

Agora vamos experimentar.

Abra uma ferramenta de IA generativa.

Pode ser:

* ChatGPT;
* Microsoft Copilot;
* Gemini;
* Claude.

Digite:

```text
Escreva um e-mail informando a um cliente que uma entrega
será atrasada.
```

Observe o resultado.

Agora faça:

```text
Escreva um e-mail profissional informando a um cliente
empresarial que a entrega do projeto será atrasada em 5 dias.

O motivo é uma dependência externa que ainda não foi resolvida.

Seja transparente, mas não atribua culpa a terceiros.

Explique o impacto, apresente a nova previsão e termine
propondo uma reunião de 15 minutos.

Use um tom profissional e cordial.
```

Compare os dois resultados.

---

# 12. O que mudou?

No primeiro prompt, fornecemos apenas:

```text
Tarefa
```

No segundo, fornecemos:

```text
Contexto
+
Objetivo
+
Instruções
+
Restrições
+
Tom
+
Formato esperado
```

A diferença é enorme.

E isso nos leva ao tema da próxima aula:

> **Como escrever prompts melhores?**

---

# 13. Um prompt é uma forma de delegação

Uma maneira simples de pensar sobre prompting:

> **Escrever um bom prompt é parecido com delegar uma tarefa para outra pessoa.**

Imagine que você peça para um colega:

> "Faça um relatório."

Provavelmente ele perguntaria:

* Relatório sobre o quê?
* Para quem?
* Qual o objetivo?
* Qual o prazo?
* Qual o tamanho?
* Que informações devo usar?
* Como você quer o resultado?

Com IA acontece algo semelhante.

Quanto melhor definirmos a tarefa, maior a possibilidade de obtermos um resultado útil.

---

# 14. O problema dos prompts vagos

Compare:

### Prompt A

```text
Faça uma apresentação sobre segurança.
```

### Prompt B

```text
Crie uma apresentação de 8 slides sobre segurança da informação
para colaboradores de uma empresa que não possuem conhecimento técnico.

O objetivo é ensinar boas práticas no uso de e-mail, senhas,
dispositivos e ferramentas de IA.

Utilize uma linguagem simples.

Para cada slide forneça:
- título;
- objetivo;
- 3 a 5 pontos principais;
- uma sugestão de exemplo prático.
```

O segundo prompt oferece muito mais contexto.

---

# 15. A IA não conhece automaticamente o seu contexto

Uma das maiores mudanças de mentalidade é entender:

> **A IA não conhece aquilo que você não forneceu.**

Se você disser:

```text
Analise este projeto.
```

A IA precisa saber:

* qual projeto;
* qual objetivo;
* quem é o público;
* quais informações devem ser consideradas;
* o que significa "analisar";
* qual resultado você espera.

Quanto melhor o contexto, mais específica pode ser a resposta.

---

# 16. Mas existe um limite

Mais contexto **não significa necessariamente melhor contexto**.

Não precisamos escrever um romance para cada prompt.

O objetivo é fornecer:

> **informação relevante para a tarefa.**

Evite:

* informações desnecessárias;
* instruções contraditórias;
* objetivos vagos;
* excesso de regras;
* contexto irrelevante.

A pergunta deve ser:

> **"O que a IA realmente precisa saber para executar esta tarefa?"**

---

# 17. A IA pode estar errada

Uma das regras mais importantes deste workshop:

> ⚠️ **Nunca confunda uma resposta convincente com uma resposta correta.**

A IA pode:

* inventar informações;
* interpretar algo incorretamente;
* apresentar fatos incorretos;
* gerar referências inexistentes;
* cometer erros matemáticos;
* interpretar mal o contexto;
* produzir código com problemas.

E pode fazer tudo isso utilizando uma linguagem extremamente convincente.

---

# 18. Hallucination — Alucinação

Chamamos de **alucinação** situações em que um modelo gera informações que parecem plausíveis, mas não correspondem aos fatos.

Exemplo:

```text
Quem foi o autor deste documento?
```

A IA pode fornecer uma resposta mesmo quando não possui informação suficiente para determinar a resposta corretamente.

Por isso:

> **IA não é uma fonte automática de verdade.**

A resposta precisa ser avaliada de acordo com o contexto e o risco da tarefa.

---

# 19. Human in the Loop

Uma abordagem importante para o uso profissional da IA é:

```text
Humano
   ↓
Define objetivo
   ↓
IA
   ↓
Gera resultado
   ↓
Humano
   ↓
Valida
   ↓
Decide
   ↓
Utiliza
```

O profissional continua sendo responsável pelo resultado final.

Quanto maior o impacto da tarefa, maior deve ser o nível de validação.

---

# 20. Exercício — Seu primeiro prompt

Agora escolha uma tarefa real do seu trabalho.

Pode ser:

* escrever um e-mail;
* preparar uma reunião;
* criar um relatório;
* resumir um documento;
* analisar informações;
* criar uma apresentação;
* organizar tarefas;
* gerar ideias.

Comece com um prompt simples.

### Versão 1

```text
[Escreva aqui seu primeiro prompt]
```

Execute.

Observe o resultado.

---

## 🔄 Versão 2

Agora melhore o prompt adicionando:

### Contexto

```text
O que a IA precisa saber?
```

### Objetivo

```text
O que quero conseguir?
```

### Instruções

```text
Como quero que a tarefa seja executada?
```

### Formato

```text
Como quero receber a resposta?
```

Execute novamente.

---

# 21. Compare os resultados

Pergunte:

* O segundo resultado ficou melhor?
* O que mudou?
* Qual informação fez mais diferença?
* A IA entendeu corretamente a tarefa?
* O resultado ainda precisa de revisão?
* O que poderia ser melhorado?

---

# 22. Desafio

Escolha uma tarefa que você realiza regularmente no trabalho.

Crie três versões do mesmo prompt:

### 🥉 Prompt básico

Peça simplesmente o que deseja.

### 🥈 Prompt contextualizado

Adicione contexto e objetivo.

### 🥇 Prompt estruturado

Adicione:

* contexto;
* objetivo;
* instruções;
* restrições;
* formato;
* critérios de qualidade.

Compare os resultados.

---

# 23. Checklist rápido

Antes de enviar um prompt, pergunte:

* [ ] Expliquei o contexto?
* [ ] Deixei claro o objetivo?
* [ ] Expliquei o que preciso que a IA faça?
* [ ] Defini o formato do resultado?
* [ ] Informei restrições importantes?
* [ ] Forneci os dados necessários?
* [ ] Evitei informações desnecessárias?
* [ ] Evitei informações confidenciais?
* [ ] Sei como vou validar a resposta?

---

# 24. O que aprendemos?

Nesta aula vimos que:

* IA é um campo amplo;
* IA Generativa consegue criar e transformar diferentes tipos de conteúdo;
* LLMs são uma das tecnologias por trás de ferramentas modernas de IA;
* diferentes ferramentas possuem diferentes capacidades;
* ChatGPT, Copilot, Gemini e Claude são ferramentas, não o objetivo final;
* prompts são uma forma de comunicação com a IA;
* contexto influencia o resultado;
* IA pode produzir respostas incorretas;
* respostas geradas precisam ser avaliadas;
* o profissional continua responsável pelo resultado.

---

# 🚀 Próxima aula

Na próxima sessão vamos aprofundar o tema de **Prompt Engineering**.

Vamos sair de:

```text
"Faça isso."
```

para:

```text
"Faça isso,
considerando este contexto,
seguindo estas regras,
e entregue o resultado neste formato."
```

### Próxima aula

**02 — Engenharia de Prompts na Prática**

Vamos explorar técnicas para criar prompts mais claros, previsíveis e úteis para situações reais de trabalho.

---

## 💡 Regra para levar desta aula

> **Não peça apenas uma resposta para a IA. Explique o trabalho que você precisa realizar.**
