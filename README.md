# 📚 Miniguia de Estudos com NotebookLM: Problemas P, NP e NP-Completo

## 📖 Contexto e Objetivos

### Tema Escolhido

Problemas P, NP e NP-Completo na Teoria da Complexidade Computacional.

### Objetivo do Projeto

Este projeto foi desenvolvido como parte do desafio de utilização do NotebookLM como ferramenta de aprendizagem ativa. O objetivo principal foi estudar e consolidar conhecimentos sobre Complexidade Computacional, utilizando Inteligência Artificial para auxiliar na organização, compreensão e revisão dos conteúdos.

Ao final deste estudo, espera-se:

* Compreender as classes P, NP e NP-Completo;
* Diferenciar resolução e verificação de problemas computacionais;
* Entender o conceito de redução polinomial;
* Identificar problemas clássicos NP-Completos;
* Criar material de revisão para futuras consultas acadêmicas.

---

# 📚 Curadoria de Fontes

As seguintes fontes foram selecionadas e utilizadas no NotebookLM para construção do caderno temático:

## 1. MIT OpenCourseWare – Theory of Computation

https://ocw.mit.edu

Material acadêmico sobre Teoria da Computação e Complexidade Computacional.

## 2. Computational Complexity Notes (MIT)

https://ocw.mit.edu

Notas de estudo voltadas para classes de complexidade e problemas computacionais.

## 3. Stanford Encyclopedia of Philosophy – Computational Complexity Theory

https://plato.stanford.edu/entries/computational-complexity/

Referência conceitual sobre a teoria da complexidade computacional.

## 4. Algorithms – Jeff Erickson

https://jeffe.cs.illinois.edu/teaching/algorithms/

Livro gratuito contendo diversos tópicos relacionados a algoritmos e complexidade.

## 5. NP-Completeness (Wikipedia)

https://en.wikipedia.org/wiki/NP-completeness

Material complementar para consulta rápida e revisão.

---

# 🤖 Engenharia de Prompts

Durante a utilização do NotebookLM foram realizados diversos testes para identificar quais tipos de prompts geravam respostas mais claras e úteis para o aprendizado.

## Prompt 1

**Pergunta:**

> Explique a diferença entre as classes P e NP utilizando exemplos simples.

### Resultado

A resposta destacou que:

* P representa problemas resolvidos em tempo polinomial.
* NP representa problemas cuja solução pode ser verificada em tempo polinomial.

### Aprendizado

Foi possível compreender que NP não significa "Não Polinomial", um erro bastante comum entre estudantes.

---

## Prompt 2

**Pergunta:**

> Explique a diferença entre resolver e verificar uma solução.

### Resultado

Foi utilizado o exemplo do Problema do Caminho Hamiltoniano para demonstrar que:

* Resolver significa encontrar uma solução.
* Verificar significa confirmar se uma solução proposta é válida.

### Ajuste Realizado

Quando a resposta ficou muito técnica, foi utilizado:

> Explique usando uma analogia do cotidiano.

O resultado tornou a explicação muito mais intuitiva.

---

## Prompt 3

**Pergunta:**

> Explique redução polinomial passo a passo.

### Resultado

A IA apresentou o conceito de transformação de problemas e sua importância para demonstrações de NP-Completude.

---

## Prompt 4

**Pergunta:**

> Como provar que um problema é NP-Completo?

### Resultado

Foi apresentado o procedimento clássico:

1. Demonstrar que o problema pertence a NP;
2. Escolher um problema NP-Completo conhecido;
3. Construir uma redução polinomial;
4. Concluir a prova de NP-Completude.

---

## Prompt 5

**Pergunta:**

> Compare SAT, 3-SAT e SUBSET-SUM.

### Resultado

A resposta mostrou como diferentes problemas NP-Completos estão relacionados por meio de reduções.

---

# 🔧 Troubleshooting e Lições Aprendidas

## Dificuldade 1

As respostas iniciais apresentavam excesso de formalismo matemático.

### Solução

Foi utilizado o prompt:

> Explique como para um estudante de graduação vendo este assunto pela primeira vez.

---

## Dificuldade 2

Compreender o conceito de redução polinomial.

### Solução

Foi utilizado:

> Mostre um exemplo visual de redução entre problemas.

---

## Dificuldade 3

Diferenciar NP e NP-Completo.

### Solução

Foi solicitado:

> Crie uma tabela comparando P, NP e NP-Completo.

---

# 📘 Miniguia de Estudo

## O que é Complexidade Computacional?

A Complexidade Computacional é a área da Ciência da Computação responsável por estudar os recursos necessários para resolver problemas computacionais.

Os recursos mais analisados são:

* Tempo de execução;
* Uso de memória.

---

## Classe P

A classe P contém problemas que podem ser resolvidos por algoritmos de tempo polinomial.

### Exemplos

* Busca Binária;
* Ordenação;
* Caminho Mínimo em grafos.

---

## Classe NP

A classe NP contém problemas cujas soluções podem ser verificadas em tempo polinomial.

### Exemplos

* Sudoku;
* SAT;
* SUBSET-SUM.

### Observação Importante

Todo problema pertencente a P também pertence a NP.

---

## Classe NP-Completo

Um problema é NP-Completo quando:

1. Pertence à classe NP;
2. É pelo menos tão difícil quanto qualquer outro problema de NP.

### Exemplos

* SAT;
* 3-SAT;
* CLIQUE;
* VERTEX COVER;
* SUBSET-SUM.

---

## Relação Entre as Classes

```text
NP
┌──────────────────────────────┐
│                              │
│      Classe P                │
│                              │
│      NP-Completo             │
│                              │
└──────────────────────────────┘
```

Atualmente não se sabe se:

```text
P = NP
```

ou

```text
P ≠ NP
```

Esse é um dos maiores problemas em aberto da Computação.

---

## Como Demonstrar que um Problema é NP-Completo

### Passo 1

Demonstrar que o problema pertence à classe NP.

### Passo 2

Selecionar um problema NP-Completo já conhecido.

### Passo 3

Construir uma redução polinomial do problema conhecido para o problema analisado.

### Passo 4

Concluir que o problema é NP-Completo.

---

# 📖 Glossário

| Conceito         | Definição                                         |
| ---------------- | ------------------------------------------------- |
| Algoritmo        | Sequência de passos para resolver um problema     |
| Complexidade     | Medida de recursos computacionais necessários     |
| Tempo Polinomial | Complexidade do tipo O(nᵏ)                        |
| Certificado      | Evidência que comprova uma solução                |
| Verificação      | Processo de validar uma solução proposta          |
| Redução          | Transformação de um problema em outro             |
| Classe P         | Problemas resolvidos em tempo polinomial          |
| Classe NP        | Problemas verificáveis em tempo polinomial        |
| NP-Completo      | Problemas mais difíceis dentro de NP              |
| NP-Difícil       | Problemas pelo menos tão difíceis quanto os de NP |
| SAT              | Problema da satisfatibilidade booleana            |
| SUBSET-SUM       | Problema da soma de subconjuntos                  |

---

# 📝 Prompts Reutilizáveis para Revisão

### Explicação de Conceitos

> Explique [conceito] como para um estudante de Ciência da Computação.

### Comparações

> Compare [conceito A] e [conceito B] em formato de tabela.

### Exercícios

> Crie 10 questões de prova sobre [tema].

### Aprendizagem Visual

> Explique utilizando diagramas textuais e exemplos visuais.

### Revisão Rápida

> Resuma este assunto em uma página.

### Correção de Dúvidas

> Quais são os erros mais comuns que estudantes cometem ao estudar este tema?

### Preparação para Provas

> Crie um simulado com questões fáceis, médias e difíceis.

---

# 🎯 Conclusão

O NotebookLM demonstrou ser uma ferramenta eficiente para organizar conteúdos, sintetizar informações provenientes de múltiplas fontes e auxiliar na construção de materiais de revisão. A experiência permitiu aprofundar conhecimentos sobre Problemas P, NP e NP-Completo, além de explorar técnicas de engenharia de prompts para melhorar a qualidade das respostas geradas por IA.
