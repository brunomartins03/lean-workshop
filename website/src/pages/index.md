---
title: Lean Workshop
---

# Workshop: Introdução à formalização de provas matemáticas com Lean 4
> Bruno Martins e Vinícius C. Rispoli

## Dados Gerais

* **Carga Horária:** 4h
* **Período:** Quarta (23/09) e Quinta (24/09), das 14h às 16h
* **Formato:** Presencial *(falta definir qual Lab)*
* **Vagas:** 30 *(depende da capacidade do Lab)*
* **Pré-requisitos:** familiaridade com provas matemáticas e experiência básica com linguagens de programação em geral (e.g. Python, Go, Rust).

## Resumo

Este workshop pretende apresentar uma visão introdutória e geral do atual panorama da formalização matemática mediada por software. Serão ensinadas as bases teóricas da formalização e a linguagem Lean, atualmente na versão 4. Além disso, serão ensinadas as principais construções da linguagem e técnicas comuns utilizadas por matemáticos para conseguir formalizar demonstrações.

* **Palavras-chave:** formalização; Lean 4; assistentes de prova; teoria de tipos

## Objetivos Gerais

Ao final do workshop, espera-se que os participantes sejam capazes de:

1. Compreender o que é formalização matemática e por que ela é relevante (verificação de provas, projetos como o Liquid Tensor Experiment e a formalização do teorema de Fermat-Wiles, etc.).
2. Entender, em linhas gerais, a correspondência de Curry-Howard e a ideia de "provas como programas".
3. Ler e escrever declarações matemáticas simples (definições, teoremas) em sintaxe Lean 4.
4. Utilizar táticas básicas (intro, exact, apply, rw, simp, ring, norm_num) para construir provas simples.
5. Navegar e utilizar, em nível introdutório, a biblioteca Mathlib.
6. Conhecer os próximos passos e recursos para continuar aprendendo Lean de forma autônoma (Natural Number Game, Mathlib docs, comunidade Lean Zulip).

## Programação

### Dia 1 — 14h–16h
 
| Tempo | Duração | Atividade |
|---|---|---|
| 14:00–14:20 | 20min | **Abertura e motivação** — o que é formalização matemática, panorama atual (Lean, Coq/Rocq, Isabelle), exemplos de grandes formalizações recentes |
| 14:20–14:55 | 35min | **Fundamentos teóricos** — teoria de tipos, correspondência Curry-Howard, tática vs. termo, estrutura de um arquivo Lean |
| 14:55–15:10 | 15min | **Setup do ambiente** — acesso ao Lean online, tour pela interface (goal state, mensagens de erro) |
| 15:10–16:00 | 50min | **Prática guiada I** — primeiras provas: lógica proposicional, táticas básicas (`intro`, `exact`, `apply`) |
 
### Dia 2 — 14h–16h
 
| Tempo | Duração | Atividade |
|---|---|---|
| 14:00–14:10 | 10min | **Recapitulação rápida** — revisão do Dia 1, dúvidas pendentes |
| 14:10–15:00 | 50min | **Prática guiada II** — provas com números e igualdades, uso de `rw`, `simp`, `ring`, `norm_num`; introdução breve à Mathlib |
| 15:00–15:10 | 10min | **Pausa** | |
| 15:10–15:50 | 40min | **Exercícios em duplas/individuais** — lista curta de exercícios com apoio dos monitores |
| 15:50–16:00 | 10min | **Encerramento** — recursos para continuar (Natural Number Game, Mathlib, comunidade), Q&A |

## Observações

Será disponibilizado um [ambiente online](https://live.lean-lang.org) para desenvolvimento dos códigos em Lean 4. Portanto, nenhuma instalação local será necessária.

## Links úteis

[1] https://lean-lang.org/theorem_proving_in_lean4/

[2] https://leanprover-community.github.io/mathematics_in_lean/index.html

[3] https://lean-lang.org/doc/reference/latest/

[4] https://www.uv.es/coslloen/Lean4/

[5] https://adam.math.hhu.de

[6] https://live.lean-lang.org/
