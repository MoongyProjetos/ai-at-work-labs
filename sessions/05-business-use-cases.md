# Aula 05 — Casos de utilização por área de negócio

> **AI at Work Labs — Como usar AI no trabalho: Prompts e Copilot na prática**

---

## 🎯 Objetivos da aula

Ao final desta aula, você deverá ser capaz de:

* Identificar oportunidades de utilização de IA na sua área profissional;
* Adaptar prompts para diferentes funções;
* Utilizar IA para resolver problemas específicos de negócio;
* Identificar tarefas repetitivas que podem ser apoiadas por IA;
* Utilizar IA para análise, comunicação, criação e organização;
* Reconhecer riscos específicos de cada área;
* Avaliar quando a IA deve apenas apoiar e quando é necessária validação humana;
* Criar um caso de utilização de IA aplicável ao próprio trabalho.

---

# 1. IA não é igual para todos

Até agora trabalhamos com exemplos relativamente genéricos.

Mas imagine:

```text
Profissional de RH
        ↓
Profissional financeiro
        ↓
Profissional de marketing
        ↓
Vendedor
        ↓
Gestor
        ↓
Programador
```

Todos podem utilizar IA.

Mas os problemas são diferentes.

Por isso:

> **O valor da IA depende do problema que estamos tentando resolver.**

---

# 2. Comece pelo problema

Uma abordagem ruim:

```text
"Temos ChatGPT.
O que podemos fazer com ele?"
```

Uma abordagem melhor:

```text
"Temos este problema.
A IA pode ajudar?"
```

Exemplo:

### Problema

> A equipe demora duas horas para preparar o relatório semanal.

### Pergunta

> Que partes desse processo podem ser apoiadas por IA?

---

# 3. Framework para encontrar casos de uso

Para cada atividade, faça cinco perguntas:

```text
1. O que fazemos?
       ↓
2. Qual é o problema?
       ↓
3. Que informação utilizamos?
       ↓
4. Onde a IA pode ajudar?
       ↓
5. Como vamos validar o resultado?
```

Esse framework será utilizado durante toda a aula.

---

# 4. Caso de uso #1 — Recursos Humanos

O departamento de RH trabalha diariamente com grandes volumes de informação e comunicação.

Exemplos:

* currículos;
* descrições de vagas;
* emails;
* políticas;
* documentos;
* avaliações;
* treinamentos;
* pesquisas internas;
* FAQs.

---

# 5. RH — Descrição de vagas

Imagine que o RH recebeu esta informação:

```text
Precisamos contratar um desenvolvedor .NET.

Experiência:
- C#
- .NET
- Azure
- APIs
- SQL

Experiência mínima:
3 anos

Modelo:
Híbrido

Local:
Lisboa
```

Podemos pedir:

```text
Crie uma descrição de vaga profissional
a partir destas informações.

Inclua:

- título;
- resumo da posição;
- responsabilidades;
- requisitos;
- qualificações desejáveis;
- modelo de trabalho.

Não invente requisitos que não foram fornecidos.
```

---

# 6. RH — Melhorando uma descrição

Podemos utilizar IA para revisar uma vaga:

```text
Analise esta descrição de vaga.

Identifique:

- requisitos pouco claros;
- informações ausentes;
- linguagem excessivamente técnica;
- possíveis ambiguidades;
- pontos que podem dificultar a compreensão.

Depois proponha uma versão revisada.
```

---

# 7. RH — Triagem de currículos

IA pode ajudar a estruturar informações de currículos.

Por exemplo:

```text
Analise este currículo em relação à descrição da vaga.

Extraia:

- experiência relevante;
- tecnologias;
- anos de experiência;
- certificações;
- localização;
- pontos que precisam ser esclarecidos.
```

Mas existe uma distinção fundamental:

> **Extrair informação é diferente de decidir quem deve ser contratado.**

Decisões de recrutamento podem envolver:

* legislação;
* políticas internas;
* critérios de igualdade;
* vieses;
* informações pessoais.

A IA não deve substituir o processo de avaliação definido pela organização.

---

# 8. RH — Entrevista

A IA pode ajudar a preparar perguntas.

```text
Crie perguntas para entrevistar
um candidato para uma posição de desenvolvedor .NET.

Organize as perguntas em:

- experiência;
- conhecimento técnico;
- resolução de problemas;
- colaboração;
- comunicação.

Para cada pergunta explique
o que ela pretende avaliar.
```

Isso pode ajudar o entrevistador a estruturar melhor a conversa.

---

# 9. RH — Treinamento

Imagine que precisamos preparar uma formação interna.

```text
Crie um programa de treinamento de 4 horas
sobre segurança da informação para novos funcionários.

Inclua:

- objetivos;
- conteúdos;
- exercícios;
- atividades práticas;
- avaliação final.
```

Depois:

```text
Transforme este programa em uma apresentação
de 15 slides.
```

Depois:

```text
Crie cinco perguntas para avaliar
se os participantes compreenderam o conteúdo.
```

Temos:

```text
Programa
 ↓
Slides
 ↓
Exercícios
 ↓
Avaliação
```

---

# 10. Exercício — RH

Escolha uma das situações:

### A

Criar uma descrição de vaga.

### B

Preparar uma entrevista.

### C

Criar um treinamento.

### D

Criar uma FAQ para funcionários.

Use:

```text
Contexto
+
Objetivo
+
Público
+
Restrições
+
Formato
```

---

# 11. Caso de uso #2 — Financeiro

No financeiro encontramos muitas tarefas baseadas em:

* números;
* relatórios;
* documentos;
* transações;
* previsões;
* comunicação;
* análise.

A IA pode ajudar principalmente na **interpretação e organização da informação**.

---

# 12. Financeiro — Resumo de relatório

Imagine um relatório financeiro extenso.

Podemos pedir:

```text
Analise este relatório financeiro.

Crie um resumo executivo contendo:

- principais indicadores;
- variações relevantes;
- pontos positivos;
- pontos de atenção;
- perguntas que precisam ser investigadas.

Não faça inferências que não sejam suportadas pelos dados.
```

---

# 13. Financeiro — Comparação

Imagine:

```text
Receita 2025: €1.200.000
Receita 2026: €1.380.000

Custos 2025: €800.000
Custos 2026: €940.000
```

Podemos perguntar:

```text
Compare os resultados de 2025 e 2026.

Calcule as principais variações percentuais
e explique quais mudanças merecem investigação.
```

A IA pode ajudar na análise inicial.

Mas números importantes devem ser verificados.

---

# 14. Financeiro — Explicando números

Uma análise pode ser apresentada de maneiras diferentes.

### Para um analista

```text
Apresente os indicadores e respectivas variações.
```

### Para um gestor

```text
Explique os três principais pontos
que precisam da atenção da gestão.
```

### Para um público não financeiro

```text
Explique os resultados sem utilizar
jargão financeiro desnecessário.
```

O mesmo dado pode precisar de diferentes formas de comunicação.

---

# 15. Financeiro — Análise de desvios

Um caso comum:

> orçamento versus realizado.

Prompt:

```text
Compare o orçamento com os valores realizados.

Identifique:

- maiores desvios;
- possíveis explicações;
- itens que precisam de investigação;
- perguntas que o responsável financeiro deveria fazer.

Não invente causas.
Diferencie claramente fatos de hipóteses.
```

Essa última instrução é importante.

---

# 16. Financeiro — Comunicação

A IA também pode ajudar a explicar resultados.

```text
Transforme esta análise financeira
em um email de cinco parágrafos
para a direção.

Seja objetivo.

Destaque:
- situação atual;
- principais desvios;
- riscos;
- próximos passos.
```

---

# 17. Exercício — Financeiro

Utilize uma tabela de dados fictícios.

Peça à IA:

1. identificar variações;
2. encontrar anomalias;
3. criar um resumo executivo;
4. criar perguntas para investigação;
5. transformar a análise em um email.

Depois valide manualmente os números.

---

# 18. Caso de uso #3 — Marketing

Marketing trabalha frequentemente com:

* conteúdo;
* campanhas;
* redes sociais;
* pesquisas;
* personas;
* emails;
* anúncios;
* análise de resultados.

É uma área onde IA pode apoiar fortemente a criação de conteúdo.

---

# 19. Marketing — Brainstorming

Imagine que precisamos lançar um produto.

```text
Gere 20 ideias de campanhas
para o lançamento de um novo produto tecnológico.

Para cada ideia informe:

- conceito;
- público;
- canal;
- mensagem principal;
- chamada para ação.
```

---

# 20. Marketing — Persona

Podemos estruturar uma persona:

```text
Crie uma persona para um produto
de software empresarial.

Inclua:

- perfil;
- objetivos;
- desafios;
- necessidades;
- objeções;
- fatores de decisão.

Identifique claramente quais informações
são hipóteses.
```

---

# 21. Marketing — Conteúdo

Uma única ideia pode gerar diferentes formatos:

```text
Ideia
 ↓
Artigo
 ↓
LinkedIn
 ↓
Email
 ↓
Post
 ↓
Apresentação
```

Prompt:

```text
Transforme este artigo em:

1. post para LinkedIn;
2. email;
3. roteiro de vídeo de 60 segundos;
4. resumo executivo.

Mantenha a mesma mensagem central.
```

---

# 22. Marketing — A/B testing

A IA pode ajudar a criar variantes.

```text
Crie cinco versões diferentes
desta mensagem de campanha.

Cada versão deve utilizar
uma abordagem diferente:

1. benefício;
2. problema;
3. curiosidade;
4. prova social;
5. urgência.

Não altere a proposta principal.
```

A IA ajuda a gerar hipóteses.

O desempenho real precisa ser medido através dos resultados da campanha.

---

# 23. Marketing — Pesquisa de feedback

Imagine que temos 500 comentários de clientes.

Podemos pedir:

```text
Analise estes comentários.

Agrupe-os por tema.

Para cada tema informe:

- quantidade de ocorrências;
- principais reclamações;
- principais elogios;
- exemplos representativos;
- possíveis ações.
```

Isso transforma texto não estruturado em informação organizada.

---

# 24. Exercício — Marketing

Crie uma campanha fictícia.

Defina:

* produto;
* público;
* objetivo.

Depois peça à IA:

1. criar três conceitos;
2. desenvolver um deles;
3. criar cinco mensagens;
4. criar um email;
5. criar um post;
6. sugerir métricas para avaliar a campanha.

---

# 25. Caso de uso #4 — Comercial

Vendas é uma área onde IA pode ajudar em:

* preparação de reuniões;
* pesquisa de clientes;
* emails;
* propostas;
* follow-up;
* análise de oportunidades;
* preparação de perguntas.

---

# 26. Comercial — Preparação de reunião

Prompt:

```text
Vou reunir com um potencial cliente.

Contexto:
[informações]

Prepare:

- objetivos da reunião;
- perguntas;
- possíveis necessidades;
- possíveis objeções;
- informações que precisamos descobrir;
- próximos passos possíveis.
```

---

# 27. Comercial — Follow-up

Depois da reunião:

```text
Estas são minhas notas:

[notas]

Crie um email de follow-up.

Inclua:

- agradecimento;
- resumo do que foi discutido;
- próximos passos;
- ações;
- informações que ainda precisamos.

Não invente compromissos.
```

---

# 28. Comercial — Qualificação

A IA pode ajudar a organizar informações sobre oportunidades.

Por exemplo:

```text
Analise estas notas de uma oportunidade comercial.

Extraia:

- necessidade;
- orçamento mencionado;
- prazo;
- decisores;
- concorrentes;
- riscos;
- próximos passos;
- informações ausentes.
```

Isso não significa que a IA conheça a real probabilidade de fechamento.

Ela está apenas organizando as informações disponíveis.

---

# 29. Comercial — Proposta

Podemos transformar informações em uma proposta inicial:

```text
Crie um primeiro rascunho de proposta comercial
a partir das informações abaixo.

Inclua:

- contexto;
- problema;
- solução;
- escopo;
- benefícios;
- próximos passos.

Não invente funcionalidades ou compromissos.
```

---

# 30. Exercício — Comercial

Simule uma reunião com um cliente.

Depois forneça as notas à IA e peça:

1. resumo;
2. necessidades do cliente;
3. objeções;
4. próximos passos;
5. email de follow-up;
6. estrutura de proposta.

Observe quanto trabalho pode ser reaproveitado.

---

# 31. Caso de uso #5 — Gestão

Gestores lidam frequentemente com:

* reuniões;
* decisões;
* relatórios;
* prioridades;
* comunicação;
* planejamento;
* acompanhamento.

IA pode funcionar como uma ferramenta de **síntese e preparação**.

---

# 32. Gestão — Resumo executivo

Imagine que você recebeu:

* três relatórios;
* cinco emails;
* duas atas de reunião;
* uma planilha.

Uma pergunta possível:

```text
Com base nestas informações,
prepare um resumo executivo.

Inclua:

- situação atual;
- principais resultados;
- riscos;
- problemas;
- decisões necessárias;
- próximos passos.

Diferencie fatos de hipóteses.
```

---

# 33. Gestão — Preparação para decisão

Prompt:

```text
Estou analisando este problema:

[problema]

Informações disponíveis:

[dados]

Ajude-me a estruturar a decisão.

Apresente:

- problema;
- opções;
- critérios;
- riscos;
- informações ausentes;
- perguntas que precisam ser respondidas.

Não escolha uma alternativa.
```

Isso mantém o papel da IA como ferramenta de apoio.

---

# 34. Gestão — Comunicação executiva

Uma mesma informação pode precisar de três versões:

```text
Informação
   ↓
Equipe técnica
   ↓
Gestão
   ↓
Direção
```

Prompt:

```text
Transforme esta análise técnica
em um resumo executivo para a direção.

Máximo de 300 palavras.

Destaque:
- impacto;
- risco;
- decisão necessária;
- próximos passos.

Evite detalhes técnicos que não sejam relevantes
para a decisão.
```

---

# 35. Gestão — Planejamento

IA também pode ajudar a estruturar planos.

```text
Crie um plano de execução para este projeto.

Inclua:

- objetivos;
- entregáveis;
- atividades;
- dependências;
- riscos;
- responsáveis;
- marcos.

Identifique quais informações ainda estão faltando.
```

O plano produzido deve ser revisado pelo responsável pelo projeto.

---

# 36. Exercício — Gestão

Escolha um projeto fictício.

Peça à IA para criar:

1. objetivo;
2. entregáveis;
3. plano;
4. riscos;
5. dependências;
6. perguntas em aberto;
7. agenda para uma reunião de kickoff.

Depois revise o resultado.

---

# 37. Caso de uso #6 — Equipas Técnicas

Agora chegamos a uma área onde IA pode apoiar fortemente atividades como:

* programação;
* debugging;
* documentação;
* testes;
* arquitetura;
* análise de logs;
* SQL;
* DevOps;
* troubleshooting.

---

# 38. Equipas técnicas — Explicar código

Podemos fornecer um trecho de código:

```text
[ código ]
```

E pedir:

```text
Explique este código.

Inclua:

- objetivo;
- fluxo;
- dependências;
- possíveis problemas;
- pontos de melhoria.

Não altere o código.
```

---

# 39. Equipas técnicas — Refactoring

Depois:

```text
Analise este código.

Identifique:

- duplicação;
- complexidade;
- problemas de nomenclatura;
- responsabilidades misturadas;
- possíveis violações de princípios de design.

Depois sugira melhorias.
```

Uma etapa importante:

> **Primeiro pedir análise. Depois pedir alteração.**

---

# 40. Equipas técnicas — Gerar código

Podemos pedir:

```text
Implemente uma classe C#
que receba uma lista de pedidos
e valide os seguintes campos:

- Id obrigatório;
- Email obrigatório;
- Data válida.

Utilize boas práticas
e mantenha a implementação simples.
```

Depois:

```text
Crie testes unitários
para os cenários positivos e negativos.
```

E depois:

```text
Revise os testes
e identifique cenários que estão faltando.
```

Temos:

```text
Requisito
 ↓
Código
 ↓
Testes
 ↓
Revisão
```

---

# 41. Equipas técnicas — Debugging

Imagine:

```text
Erro:
System.NullReferenceException
```

Em vez de perguntar apenas:

```text
Como resolvo?
```

Forneça contexto:

```text
Estou recebendo este erro:

[erro]

Código:

[código]

Contexto:

[descrição]

Ambiente:

[ambiente]

O problema ocorre quando:

[condição]

Analise possíveis causas.

Não proponha alterações ainda.
Primeiro explique as hipóteses.
```

Depois:

```text
Agora proponha três formas de corrigir o problema.

Para cada uma explique:

- vantagem;
- desvantagem;
- risco;
- impacto.
```

---

# 42. Equipas técnicas — Logs

Logs podem conter enorme quantidade de informação.

Podemos utilizar IA para ajudar a identificar padrões:

```text
Analise estes logs.

Identifique:

- erros;
- warnings;
- padrões repetitivos;
- timestamps relevantes;
- possíveis correlações;
- informações que faltam.

Não conclua a causa raiz sem evidências.
```

Essa última frase é extremamente importante.

---

# 43. Equipas técnicas — Documentação

Podemos transformar código em documentação:

```text
Analise este código e crie documentação técnica.

Inclua:

- objetivo;
- arquitetura;
- dependências;
- entradas;
- saídas;
- tratamento de erros;
- exemplos de utilização.
```

Depois:

```text
Agora crie uma versão resumida
para um desenvolvedor que acabou
de entrar no projeto.
```

---

# 44. Equipas técnicas — SQL

IA também pode ajudar a:

* explicar queries;
* gerar queries;
* otimizar consultas;
* identificar problemas;
* criar testes;
* documentar SQL.

Exemplo:

```text
Analise esta query SQL.

Explique:

- o que ela faz;
- tabelas utilizadas;
- filtros;
- joins;
- possíveis problemas de performance.

Não altere a query.
```

Depois:

```text
Sugira otimizações.

Para cada sugestão explique
o possível impacto.
```

---

# 45. Equipas técnicas — DevOps

Exemplos de utilização:

* pipelines;
* YAML;
* scripts;
* Dockerfiles;
* troubleshooting;
* documentação;
* infraestrutura como código;
* logs.

Prompt:

```text
Analise este pipeline.

Identifique:

- possíveis falhas;
- etapas redundantes;
- riscos;
- oportunidades de melhoria.

Não altere o pipeline ainda.
```

Depois podemos solicitar uma versão modificada.

---

# 46. Exercício — Equipas Técnicas

Escolha uma tarefa técnica.

Pode ser:

* código;
* SQL;
* logs;
* documentação;
* pipeline.

Faça o processo:

```text
1. Contexto
2. Problema
3. Análise pela IA
4. Hipóteses
5. Soluções
6. Validação
```

Compare com a forma tradicional de realizar a tarefa.

---

# 47. Comparando as áreas

Observe que os prompts são diferentes.

Mas a estrutura continua semelhante:

| Área       | Problema                 | IA ajuda em                        |
| ---------- | ------------------------ | ---------------------------------- |
| RH         | Informação e comunicação | Criar, resumir, estruturar         |
| Financeiro | Análise                  | Comparar, explicar, sintetizar     |
| Marketing  | Conteúdo                 | Criar, adaptar, explorar           |
| Comercial  | Clientes                 | Preparar, resumir, comunicar       |
| Gestão     | Decisões                 | Estruturar, sintetizar, questionar |
| Técnico    | Problemas                | Analisar, criar, explicar, testar  |

O padrão é:

```text
Problema
   ↓
Contexto
   ↓
IA
   ↓
Resultado
   ↓
Validação
```

---

# 48. O mesmo prompt, diferentes áreas

Uma técnica interessante é mudar apenas o contexto.

### Prompt base

```text
Analise as informações abaixo.

Identifique:

- pontos principais;
- riscos;
- ações;
- questões em aberto.

Apresente o resultado em uma tabela.
```

### RH

```text
Analise esta política de RH...
```

### Financeiro

```text
Analise este relatório financeiro...
```

### Marketing

```text
Analise estes comentários de clientes...
```

### Técnico

```text
Analise estes logs...
```

A estrutura permanece.

O contexto muda.

---

# 49. Caso de uso cross-functional

Alguns processos atravessam várias áreas.

Imagine o lançamento de um novo produto:

```text
Marketing
    ↓
Comercial
    ↓
Financeiro
    ↓
Operações
    ↓
Suporte
    ↓
Gestão
```

IA pode ajudar cada área de maneira diferente.

---

# 50. Exercício — Projeto completo

Imagine:

> A empresa vai lançar um novo produto.

Crie uma tarefa para cada área.

### RH

Preparar treinamento para a equipe.

### Financeiro

Criar análise de custos.

### Marketing

Criar campanha.

### Comercial

Preparar argumentação de vendas.

### Gestão

Criar plano de lançamento.

### Técnico

Criar documentação.

Agora pergunte:

> **Como a mesma informação poderia ser utilizada por todas essas áreas?**

---

# 51. O problema dos casos de uso genéricos

Evite exemplos como:

> "Use IA para escrever emails."

Isso é verdadeiro, mas pouco útil.

Um caso de uso melhor:

> "Utilizar IA para transformar notas de uma reunião comercial em um resumo, lista de ações e email de follow-up, reduzindo o trabalho manual de documentação."

Quanto mais específico:

```text
Problema
+
Contexto
+
Processo
+
Resultado
+
Métrica
```

mais fácil medir o valor.

---

# 52. Caso de uso bom vs. ruim

### ❌ Caso de uso genérico

> Usar IA para melhorar produtividade.

### ✅ Caso de uso específico

> Utilizar IA para transformar reuniões em ações estruturadas e reduzir o tempo gasto na preparação da ata.

---

# 53. Caso de uso bom vs. ruim

### ❌

> Usar IA no RH.

### ✅

> Utilizar IA para transformar informações fornecidas pelo RH em descrições de vagas padronizadas, mantendo validação humana antes da publicação.

---

# 54. Caso de uso bom vs. ruim

### ❌

> Usar IA em vendas.

### ✅

> Utilizar IA para transformar notas de reuniões comerciais em emails de follow-up e listas de ações.

---

# 55. O framework USE CASE

Para documentar uma oportunidade:

```text
U — User
Quem utilizará?

S — Situation
Qual é a situação?

E — Expected result
Qual resultado queremos?

C — Constraints
Quais são as restrições?

A — AI contribution
Onde a IA ajuda?

S — Success metric
Como mediremos o sucesso?

E — Evaluation
Como validaremos o resultado?
```

---

# 56. Exemplo completo

## User

Equipe comercial.

## Situation

Após cada reunião, o vendedor precisa preparar manualmente um resumo e email.

## Expected result

Reduzir o tempo gasto na documentação.

## Constraints

Não inventar compromissos ou informações.

## AI contribution

Resumir notas e preparar um rascunho de email.

## Success metric

Tempo médio por follow-up.

## Evaluation

Revisão humana antes do envio.

---

# 57. Workshop — Crie seu próprio caso de uso

Agora escolha uma tarefa real.

Preencha:

```text
USER:
____________________________

SITUATION:
____________________________

EXPECTED RESULT:
____________________________

CONSTRAINTS:
____________________________

AI CONTRIBUTION:
____________________________

SUCCESS METRIC:
____________________________

EVALUATION:
____________________________
```

---

# 58. Transforme o caso de uso em prompt

Agora transforme seu caso de uso em um prompt.

Use:

```text
CONTEXTO
+
OBJETIVO
+
DADOS
+
INSTRUÇÕES
+
RESTRIÇÕES
+
FORMATO
+
CRITÉRIOS DE QUALIDADE
```

Exemplo:

```text
CONTEXTO:
Sou responsável por acompanhar projetos.

OBJETIVO:
Preciso preparar um resumo semanal.

DADOS:
[informações]

INSTRUÇÕES:
Identifique progresso, riscos e ações.

RESTRIÇÕES:
Não invente informações.

FORMATO:
Tabela + resumo executivo.

CRITÉRIOS:
Objetivo, claro e acionável.
```

---

# 59. Agora transforme em workflow

O prompt é apenas uma etapa.

Desenhe:

```text
ENTRADA
   ↓
PREPARAÇÃO
   ↓
IA
   ↓
VALIDAÇÃO
   ↓
AÇÃO
   ↓
MÉTRICA
```

Pergunte:

> Onde exatamente a IA agrega valor?

---

# 60. O papel humano

Em todos os exemplos desta aula existe uma etapa importante:

```text
              IA
               ↓
         Resultado
               ↓
      ┌────────────────┐
      │     Humano     │
      │    valida      │
      └───────┬────────┘
              ↓
            Ação
```

A IA pode:

* acelerar;
* estruturar;
* sugerir;
* resumir;
* gerar;
* analisar.

O profissional:

* interpreta;
* valida;
* decide;
* assume responsabilidade.

---

# 61. Riscos específicos por área

| Área       | Exemplos de riscos                               |
| ---------- | ------------------------------------------------ |
| RH         | Dados pessoais, vieses, decisões automatizadas   |
| Financeiro | Erros numéricos, informação incorreta            |
| Marketing  | Conteúdo incorreto, direitos autorais, reputação |
| Comercial  | Informações inventadas, compromissos incorretos  |
| Gestão     | Decisões baseadas em informação incompleta       |
| Técnico    | Código inseguro, vulnerabilidades, erros         |

O risco depende do contexto.

---

# 62. Regra de ouro

Quanto maior o impacto de uma tarefa:

```text
Maior impacto
     ↓
Maior validação
     ↓
Maior responsabilidade humana
```

Não devemos utilizar o mesmo nível de supervisão para:

> "Crie cinco ideias para um slogan."

e:

> "Analise uma decisão financeira de milhões de euros."

---

# 63. O objetivo final

Não queremos chegar a:

```text
"Minha empresa usa IA."
```

Queremos chegar a:

```text
"Minha empresa identificou problemas específicos
e utiliza IA para melhorar processos específicos,
com métricas e validação."
```

Essa é uma abordagem muito mais madura.

---

# 64. Checklist de um bom caso de uso

Antes de implementar:

* [ ] O problema está claramente definido?
* [ ] A tarefa realmente consome tempo?
* [ ] A IA pode ajudar?
* [ ] Os dados podem ser utilizados?
* [ ] Existem riscos?
* [ ] Existe validação humana?
* [ ] O resultado esperado está definido?
* [ ] Existe uma métrica?
* [ ] O processo pode ser melhorado?
* [ ] O ganho compensa o esforço?

---

# 65. O que aprendemos?

Nesta aula vimos que:

* diferentes áreas possuem diferentes oportunidades de utilização de IA;
* o caso de uso deve começar pelo problema;
* RH pode utilizar IA para conteúdo, treinamento e organização;
* Financeiro pode utilizar IA para análise e comunicação;
* Marketing pode utilizar IA para criação e exploração;
* Comercial pode utilizar IA para preparação e follow-up;
* Gestão pode utilizar IA para síntese e estruturação;
* equipes técnicas podem utilizar IA para código, documentação e troubleshooting;
* o mesmo princípio de prompting pode ser aplicado em diferentes áreas;
* casos de uso específicos são mais úteis que ideias genéricas;
* métricas ajudam a determinar se existe ganho real;
* quanto maior o risco, maior deve ser a validação humana.

---

# 66. Da ferramenta para o caso de uso

A evolução do workshop foi:

```text
Aula 01
O que é IA?
       ↓
Aula 02
Como falar com IA?
       ↓
Aula 03
Como usar IA nas ferramentas?
       ↓
Aula 04
Como redesenhar o trabalho?
       ↓
Aula 05
Onde aplicar na minha área?
```

Agora falta uma questão fundamental:

> **Como utilizar IA de forma responsável?**

---

# 🚀 Próxima aula

## Aula 06 — Boas práticas, segurança e futuro da IA

Na próxima sessão vamos discutir:

* utilização responsável;
* privacidade;
* proteção de dados;
* segurança;
* validação;
* alucinações;
* vieses;
* propriedade intelectual;
* quando confiar;
* quando não confiar;
* políticas de utilização;
* evolução da IA;
* próximos passos.

E vamos terminar o workshop transformando tudo o que aprendemos em um **plano pessoal de utilização de IA no trabalho**.

---

## 💡 Regra para levar desta aula

> **Não comece pela ferramenta. Comece pelo problema.**
>
> **Depois pergunte onde a IA pode realmente criar valor.**
