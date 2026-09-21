# Aula 02 — Engenharia de Prompts na Prática

> **AI at Work Labs — Como usar AI no trabalho: Prompts e Copilot na prática**

---

## 🎯 Objetivos da aula

Ao final desta aula, você deverá ser capaz de:

* Entender o que é Prompt Engineering;
* Estruturar prompts de forma mais eficiente;
* Fornecer contexto relevante para a IA;
* Definir claramente o objetivo de uma tarefa;
* Especificar instruções e restrições;
* Controlar o formato da resposta;
* Utilizar exemplos para orientar a IA;
* Melhorar respostas através de iteração;
* Identificar problemas em prompts;
* Criar prompts reutilizáveis para tarefas profissionais.

---

# 1. O que é Prompt Engineering?

**Prompt Engineering** é o processo de criar e aperfeiçoar instruções para obter resultados mais úteis, consistentes e adequados de um modelo de IA.

Em termos simples:

> **É aprender a pedir melhor.**

Não se trata de encontrar uma "palavra mágica".

Também não significa escrever prompts gigantes.

O objetivo é fornecer à IA as informações necessárias para que ela compreenda:

* o que está acontecendo;
* o que você quer;
* como deve executar a tarefa;
* quais são as restrições;
* como você espera receber o resultado.

---

# 2. Prompt não é comando mágico

Um erro comum é imaginar que existe um prompt perfeito:

```text
"Você é um especialista em..."
```

e que isso automaticamente produzirá uma excelente resposta.

Na realidade, prompting é um processo iterativo.

```text
Prompt
   ↓
Resposta
   ↓
Avaliação
   ↓
Feedback
   ↓
Novo prompt
   ↓
Nova resposta
   ↓
Avaliação
```

A qualidade surge muitas vezes através da **interação**, e não de uma única mensagem.

---

# 3. Prompt básico x Prompt estruturado

Considere:

```text
Crie um relatório sobre vendas.
```

Esse prompt possui um problema:

> **A IA não sabe exatamente o que você espera.**

Agora:

```text
Analise os dados de vendas do primeiro semestre.

Identifique:
- os produtos com maior crescimento;
- os produtos com queda de vendas;
- as principais variações mensais;
- possíveis anomalias.

Apresente os resultados em uma tabela.

Depois, escreva um resumo executivo de no máximo 200 palavras
destinado à direção comercial.
```

Agora temos:

* contexto;
* tarefa;
* critérios;
* formato;
* público;
* limite.

---

# 4. O modelo C.R.O.F.

Durante este workshop vamos utilizar um modelo simples para estruturar prompts:

```text
C — Contexto
R — Resultado
O — Orientações
F — Formato
```

---

## C — Contexto

> **O que a IA precisa saber para entender a situação?**

Exemplo:

```text
Sou responsável por uma equipe de desenvolvimento de software
com 8 pessoas.

A equipe trabalha em um sistema financeiro crítico.

Precisamos preparar uma reunião semanal de acompanhamento.
```

O contexto estabelece o cenário.

---

## R — Resultado

> **O que você quer obter?**

Exemplo:

```text
Quero preparar uma agenda para a reunião semanal.
```

Ou:

```text
Quero identificar os principais riscos do projeto.
```

Ou:

```text
Quero transformar estas informações em um relatório executivo.
```

---

## O — Orientações

> **Como a tarefa deve ser executada?**

Exemplo:

```text
Considere apenas os problemas que podem afetar o prazo,
o orçamento ou a qualidade da entrega.

Não faça suposições sobre informações que não foram fornecidas.
```

As orientações ajudam a delimitar o comportamento esperado.

---

## F — Formato

> **Como você quer receber a resposta?**

Exemplo:

```text
Apresente uma tabela com as colunas:

Risco | Impacto | Probabilidade | Ação recomendada
```

Ou:

```text
Organize a resposta em:

1. Resumo executivo
2. Principais riscos
3. Recomendações
4. Próximos passos
```

---

# 5. Exemplo completo

Juntando tudo:

```text
CONTEXTO

Sou responsável por uma equipe de desenvolvimento de software
com 8 pessoas. A equipe trabalha em um sistema financeiro crítico.

RESULTADO

Quero preparar uma agenda para nossa reunião semanal.

ORIENTAÇÕES

A reunião deve durar no máximo 45 minutos.

Devemos priorizar:
- bloqueios;
- riscos;
- decisões pendentes;
- próximos passos.

Evite incluir discussões puramente técnicas que não tenham
impacto no projeto.

FORMATO

Crie uma agenda dividida por tempo.

Para cada tópico informe:
- duração;
- objetivo;
- perguntas que devem ser respondidas.
```

Esse é um prompt muito mais fácil de executar.

---

# 6. Contexto é rei

Uma das formas mais simples de melhorar um prompt é fornecer contexto relevante.

Compare:

### Sem contexto

```text
Escreva um email sobre atraso.
```

### Com contexto

```text
Preciso informar um cliente empresarial que a entrega do projeto
será atrasada em cinco dias.

O atraso aconteceu devido a uma dependência externa.

O cliente está preocupado com o impacto no lançamento.
```

A segunda versão permite uma resposta muito mais adequada.

---

# 7. Mas cuidado com excesso de contexto

Mais informação não significa necessariamente melhor resultado.

Imagine:

```text
Eu trabalho em uma empresa desde 2018.
A empresa começou como uma startup.
Temos três escritórios.
Meu gestor entrou em 2021.
O projeto começou em janeiro.
O cliente é alemão.
A equipe tem 14 pessoas.
Eu gosto de trabalhar de manhã.
O projeto usa .NET.
A reunião é na quinta-feira.
...
```

Nem toda essa informação é relevante.

Pergunte:

> **"Essa informação ajuda a IA a executar a tarefa?"**

Se não ajudar, provavelmente não precisa estar no prompt.

---

# 8. Seja específico sobre o objetivo

Um dos problemas mais comuns:

```text
Analise este documento.
```

Mas o que significa "analisar"?

Pode significar:

* resumir;
* encontrar erros;
* identificar riscos;
* encontrar inconsistências;
* extrair informações;
* comparar versões;
* explicar conceitos;
* gerar recomendações.

Melhor:

```text
Analise este documento e identifique:

1. inconsistências;
2. informações ausentes;
3. riscos;
4. decisões pendentes.

Não faça alterações no documento.
```

Agora o objetivo está definido.

---

# 9. Defina o público

A mesma informação pode precisar de formatos completamente diferentes dependendo do público.

Compare:

```text
Explique o problema para um desenvolvedor.
```

com:

```text
Explique o problema para um diretor não técnico.
```

ou:

```text
Explique o problema para um cliente que não possui conhecimento técnico.
```

O conteúdo pode ser semelhante.

A comunicação não.

---

# 10. Defina o nível de conhecimento

Você pode especificar:

```text
Explique para alguém sem conhecimento técnico.
```

ou:

```text
Explique para um profissional de TI com conhecimento intermediário.
```

ou:

```text
Explique para um arquiteto de software experiente.
```

Isso ajuda a ajustar:

* vocabulário;
* profundidade;
* exemplos;
* quantidade de contexto;
* nível técnico.

---

# 11. Defina o formato

Uma das formas mais simples de controlar uma resposta é especificar o formato.

### Lista

```text
Apresente cinco recomendações em uma lista numerada.
```

### Tabela

```text
Apresente os resultados em uma tabela com:

Problema | Impacto | Prioridade | Recomendação
```

### JSON

```text
Retorne exclusivamente JSON válido.
```

### Email

```text
Escreva um email profissional com:

- assunto;
- saudação;
- corpo;
- encerramento.
```

### Apresentação

```text
Crie uma estrutura de 8 slides.

Para cada slide informe:
- título;
- objetivo;
- conteúdo;
- sugestão visual.
```

---

# 12. Defina restrições

Restrições são regras que limitam a resposta.

Exemplos:

```text
Use no máximo 150 palavras.
```

```text
Não utilize linguagem técnica.
```

```text
Não invente informações.
```

```text
Utilize apenas os dados fornecidos.
```

```text
Não altere os nomes das empresas.
```

```text
Não atribua culpa a nenhuma pessoa ou equipe.
```

Restrições podem aumentar significativamente a utilidade da resposta.

---

# 13. Diga também o que NÃO fazer

Às vezes é útil explicar o que deve ser evitado.

Exemplo:

```text
Analise o documento.

Não faça suposições sobre informações ausentes.

Se uma informação não estiver disponível,
indique explicitamente "informação não disponível".
```

Isso é especialmente importante quando trabalhamos com:

* documentos;
* dados;
* análises;
* relatórios;
* informações empresariais.

---

# 14. Exemplos — Few-shot prompting

Uma técnica poderosa é fornecer exemplos.

Imagine que você quer classificar solicitações de clientes.

Você pode dizer:

```text
Classifique cada solicitação como:

URGENTE
NORMAL
BAIXA

Exemplos:

"Não consigo acessar minha conta e tenho um pagamento
vencendo hoje." → URGENTE

"Gostaria de alterar meu endereço." → NORMAL

"Gostaria de saber se existe uma versão mobile." → BAIXA
```

Depois:

```text
Classifique:

"Não consigo acessar o sistema desde ontem."
```

Os exemplos ajudam a demonstrar o padrão esperado.

---

# 15. Zero-shot, One-shot e Few-shot

### Zero-shot

Nenhum exemplo.

```text
Classifique esta solicitação como urgente ou normal.
```

### One-shot

Um exemplo.

```text
"Não consigo acessar minha conta." → URGENTE

Classifique:
"Preciso alterar meu endereço." 
```

### Few-shot

Vários exemplos.

```text
Exemplo 1 → resultado
Exemplo 2 → resultado
Exemplo 3 → resultado

Agora classifique:
...
```

Os exemplos podem ajudar quando a tarefa possui regras específicas.

---

# 16. Peça para a IA fazer perguntas

Nem sempre precisamos fornecer todas as informações antecipadamente.

Podemos instruir:

```text
Antes de responder, faça até cinco perguntas
caso faltem informações importantes para executar a tarefa.
```

Isso transforma a interação em um processo mais próximo de uma conversa.

---

# 17. Prompt interativo

Imagine que queremos criar uma apresentação.

Em vez de:

```text
Crie uma apresentação sobre IA.
```

podemos fazer:

```text
Quero criar uma apresentação sobre Inteligência Artificial
Generativa para colaboradores de uma empresa.

Antes de criar a apresentação, faça perguntas para entender:

- público;
- duração;
- objetivo;
- nível de conhecimento;
- ferramentas que serão utilizadas;
- formato desejado.

Faça uma pergunta por vez.
```

Agora a IA ajuda a construir o próprio contexto.

---

# 18. Iteração

Uma das habilidades mais importantes no uso de IA:

> **Não aceite necessariamente a primeira resposta.**

Imagine:

```text
Prompt
  ↓
Resposta
```

Muitas vezes podemos fazer:

```text
Prompt
  ↓
Resposta
  ↓
Feedback
  ↓
Melhoria
  ↓
Resposta
  ↓
Feedback
  ↓
Resultado final
```

---

# 19. Feedback ruim x feedback bom

### Feedback ruim

```text
Não gostei. Faça melhor.
```

A IA não sabe exatamente o que você não gostou.

### Feedback melhor

```text
O conteúdo está correto, mas está muito técnico.

Reescreva para uma audiência não técnica.

Mantenha os exemplos e reduza o texto em aproximadamente 30%.
```

Agora existe uma direção clara.

---

# 20. Use a IA para melhorar o próprio prompt

Uma técnica extremamente útil:

```text
Este é o prompt que estou utilizando:

[cole seu prompt]

Analise o prompt e sugira melhorias.

Identifique:
- ambiguidades;
- informações ausentes;
- instruções contraditórias;
- oportunidades de melhorar o formato da resposta.

Depois apresente uma versão revisada.
```

A IA pode atuar como **revisora do seu prompt**.

---

# 21. Meta-prompting

Podemos ir um passo além.

Um **meta-prompt** é uma instrução que pede à IA para trabalhar sobre outra instrução ou sobre o próprio processo de geração.

Exemplo:

```text
Atue como um especialista em criação de prompts.

Vou fornecer um prompt abaixo.

Sua tarefa é:
1. identificar problemas;
2. explicar por que são problemas;
3. sugerir melhorias;
4. apresentar uma versão otimizada.

Prompt:
[SEU PROMPT]
```

---

# 22. Prompting não é sobre escrever mais

Compare:

### Prompt longo

```text
[500 palavras de contexto irrelevante]
...
...
...
Faça um email.
```

### Prompt eficiente

```text
Contexto:
[informação relevante]

Objetivo:
[resultado esperado]

Restrições:
[regras importantes]

Formato:
[resultado esperado]
```

O objetivo não é:

> **Escrever o maior prompt possível.**

O objetivo é:

> **Fornecer as informações certas.**

---

# 23. Prompting como especificação

Para tarefas mais complexas, pense no prompt como uma **especificação de trabalho**.

Uma boa especificação responde:

```text
O que?
Por quê?
Para quem?
Com quais dados?
Com quais regras?
Com quais restrições?
Em qual formato?
```

Essa forma de pensar é especialmente útil no ambiente profissional.

---

# 24. Exercício 1 — Melhorando um prompt

### Prompt original

```text
Crie um email para um cliente.
```

### Tarefa

Melhore o prompt utilizando:

* contexto;
* objetivo;
* público;
* tom;
* restrições;
* formato.

### Sua versão

```text
[Escreva seu prompt aqui]
```

---

# 25. Exercício 2 — Transformando informação

Você recebeu o seguinte texto:

```text
A reunião de projeto aconteceu na terça-feira.
Participaram João, Maria, Carlos e Ana.

Foi decidido que o lançamento será adiado para 15 de outubro.

Carlos ficará responsável pelos testes.

Maria precisa atualizar a documentação.

João irá comunicar o cliente.

Ana vai preparar o relatório de impacto.

A próxima reunião será na sexta-feira.
```

Crie um prompt que transforme essas informações em uma tabela:

| Decisão / Ação | Responsável | Prazo |
| -------------- | ----------- | ----- |
|                |             |       |

---

# 26. Exercício 3 — Mudando o público

Utilize a mesma informação do exercício anterior.

Crie três prompts:

### Público 1 — Equipe técnica

Explique os detalhes necessários para a equipe executar as ações.

### Público 2 — Gestão

Crie um resumo executivo.

### Público 3 — Cliente

Crie uma comunicação profissional sobre o adiamento.

Observe como:

> **A mesma informação pode gerar diferentes resultados dependendo do público.**

---

# 27. Exercício 4 — Few-shot prompting

Imagine que você trabalha no suporte ao cliente.

Classifique as mensagens como:

* **URGENTE**
* **NORMAL**
* **BAIXA**

Utilize estes exemplos:

```text
"Minha conta está bloqueada e tenho um pagamento vencendo hoje."
→ URGENTE

"Quero alterar meu número de telefone."
→ NORMAL

"Vocês possuem uma aplicação para celular?"
→ BAIXA
```

Agora peça:

```text
"Estou sem acesso à minha conta desde ontem e preciso
realizar uma transferência hoje."
```

Observe como os exemplos influenciam a classificação.

---

# 28. Exercício 5 — Iteração

Comece com:

```text
Crie uma apresentação sobre Inteligência Artificial.
```

Depois melhore progressivamente.

### Iteração 1

Adicione o público.

### Iteração 2

Adicione o objetivo.

### Iteração 3

Adicione o número de slides.

### Iteração 4

Defina o formato.

### Iteração 5

Adicione restrições.

Compare cada resultado.

---

# 29. Exercício 6 — Prompt para uma tarefa real

Agora volte para a tarefa que você identificou no início da primeira aula.

Pergunte:

> **"Como eu poderia delegar esta tarefa para um colega?"**

Escreva a resposta.

Depois transforme essa delegação em um prompt.

Utilize:

```text
CONTEXTO

[contexto]

RESULTADO

[o que quero obter]

ORIENTAÇÕES

[como deve ser feito]

FORMATO

[como quero receber]
```

Execute o prompt.

Avalie o resultado.

Melhore.

Execute novamente.

---

# 30. O ciclo de melhoria

Um bom processo de prompting pode ser representado assim:

```text
┌──────────────────┐
│  Definir tarefa  │
└────────┬─────────┘
         ↓
┌──────────────────┐
│ Criar o prompt   │
└────────┬─────────┘
         ↓
┌──────────────────┐
│ Executar         │
└────────┬─────────┘
         ↓
┌──────────────────┐
│ Avaliar resultado│
└────────┬─────────┘
         ↓
┌──────────────────┐
│ Dar feedback     │
└────────┬─────────┘
         ↓
┌──────────────────┐
│ Melhorar prompt  │
└────────┬─────────┘
         │
         └──────────────→ Executar novamente
```

Esse ciclo é muito mais importante do que decorar uma lista de "prompts mágicos".

---

# 31. Erros comuns

## ❌ Ser vago

```text
Faça um relatório.
```

### ✅ Melhor

```text
Analise os dados e produza um relatório executivo
de no máximo 500 palavras.
```

---

## ❌ Não fornecer contexto

```text
Escreva uma resposta.
```

### ✅ Melhor

```text
Responda ao cliente que está reclamando do atraso
na entrega do projeto.
```

---

## ❌ Não definir o público

```text
Explique o problema.
```

### ✅ Melhor

```text
Explique o problema para um diretor não técnico.
```

---

## ❌ Não definir formato

```text
Analise os dados.
```

### ✅ Melhor

```text
Apresente os cinco principais insights em uma tabela.
```

---

## ❌ Aceitar a primeira resposta

```text
Obrigado.
```

### ✅ Melhor

```text
Revise sua resposta e identifique três pontos que poderiam
ser melhorados antes de apresentar a versão final.
```

---

# 32. Uma observação importante sobre "Chain of Thought"

Você pode encontrar na internet técnicas que sugerem pedir:

> "Mostre seu raciocínio passo a passo."

Para aplicações profissionais, normalmente é mais útil pedir **uma explicação, justificativa, critérios ou resumo das razões relevantes**, em vez de exigir a exposição de todo o raciocínio interno do modelo.

Por exemplo:

```text
Explique quais critérios você utilizou para chegar à conclusão.
```

é mais útil do que:

```text
Mostre todo o seu raciocínio interno.
```

---

# 33. Quando um prompt complexo é necessário?

Nem toda tarefa precisa de um prompt elaborado.

### Tarefa simples

```text
Traduza este texto para inglês.
```

É suficiente.

### Tarefa complexa

```text
Analise estes dados, identifique anomalias,
compare com o período anterior, apresente os principais riscos
e prepare um resumo executivo para a direção.
```

Aqui faz sentido estruturar melhor o pedido.

> **Use a quantidade de estrutura necessária para a complexidade da tarefa.**

---

# 34. Prompt reutilizável

Quando uma tarefa acontece frequentemente, transforme o prompt em um **template**.

Exemplo:

```text
Analise o seguinte [TIPO DE CONTEÚDO]:

[CONTEÚDO]

Contexto:
[CONTEXTO]

Objetivo:
[OBJETIVO]

Identifique:
- [CRITÉRIO 1]
- [CRITÉRIO 2]
- [CRITÉRIO 3]

Apresente o resultado em:
[FORMATO]
```

Agora podemos reutilizar o mesmo padrão.

---

# 35. Criando uma biblioteca de prompts

Uma organização pode criar uma biblioteca de prompts para tarefas recorrentes.

Exemplos:

```text
prompts/
├── email/
│   ├── summarize-email.md
│   ├── reply-to-client.md
│   └── improve-email.md
│
├── meetings/
│   ├── meeting-summary.md
│   └── meeting-agenda.md
│
├── documents/
│   ├── summarize-document.md
│   └── analyze-document.md
│
├── presentations/
│   └── create-presentation.md
│
└── analysis/
    └── analyze-data.md
```

O objetivo não é criar uma coleção de prompts mágicos.

É criar **padrões reutilizáveis para tarefas recorrentes**.

---

# 36. Prompt Engineering ≠ Prompt Magic

Não existe garantia de que um determinado prompt produzirá sempre exatamente o mesmo resultado.

Modelos, configurações, contexto e ferramentas podem influenciar o resultado.

Por isso:

> **Prompt Engineering é uma disciplina de comunicação e experimentação, não uma fórmula matemática.**

---

# 37. Checklist de um bom prompt

Antes de executar:

### Contexto

* [ ] A IA sabe o que está acontecendo?

### Objetivo

* [ ] Está claro o que quero obter?

### Orientações

* [ ] Expliquei como a tarefa deve ser executada?

### Público

* [ ] A IA sabe para quem é o resultado?

### Restrições

* [ ] Defini limites importantes?

### Dados

* [ ] Forneci as informações necessárias?

### Formato

* [ ] Expliquei como quero receber a resposta?

### Validação

* [ ] Sei como verificar se a resposta está correta?

---

# 38. O que aprendemos?

Nesta aula aprendemos que:

* Prompt Engineering é mais do que escrever comandos;
* contexto é fundamental;
* objetivos devem ser claros;
* o público influencia o resultado;
* formatos podem ser especificados;
* restrições ajudam a controlar a resposta;
* exemplos podem orientar o comportamento;
* perguntas podem ser usadas para completar o contexto;
* prompts podem ser melhorados iterativamente;
* prompts podem ser transformados em templates reutilizáveis;
* nem toda tarefa precisa de um prompt complexo.

---

# 🚀 Próxima aula

Na próxima sessão vamos sair da conversa com uma IA e entrar no ambiente onde o trabalho realmente acontece.

Vamos explorar:

> **Microsoft Copilot aplicado ao trabalho diário.**

Veremos como a IA pode ser utilizada diretamente em ferramentas como:

* Word;
* Outlook;
* Excel;
* PowerPoint;
* Teams.

A pergunta deixa de ser apenas:

> **"Como conversar com uma IA?"**

e passa a ser:

> **"Como colocar IA dentro do meu fluxo de trabalho?"**

---

## 💡 Regra para levar desta aula

> **Um bom prompt não é necessariamente um prompt longo. É um prompt que fornece o contexto, o objetivo e as instruções necessárias para realizar a tarefa.**
