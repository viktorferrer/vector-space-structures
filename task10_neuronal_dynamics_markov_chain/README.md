# 🧠 Exercise 10 — Neuronal Dynamics as a Markov Chain

## 🇧🇷 Versão em Português

Considere um neurônio cuja dinâmica pode ser descrita, de forma discreta no tempo, por três estados:

- **Repouso (R)**: neurônio em potencial de repouso, com canais de sódio majoritariamente fechados;
- **Ativo (A)**: ocorrência de potencial de ação, associado à abertura de canais de sódio;
- **Refratário (F)**: estado após o disparo, no qual os canais encontram-se inativados e o neurônio não pode disparar imediatamente.

Admita que a evolução desses estados pode ser modelada por uma cadeia de Markov.

As transições são dadas por:

- de (R), o neurônio permanece em (R) com probabilidade (1 - p) ou passa para (A) com probabilidade p;
- de (A), o neurônio passa para (F) com probabilidade 1;
- de (F), o neurônio retorna para (R) com probabilidade q ou permanece em (F) com probabilidade (1 - q).

---

### Tarefas

1. Construa a matriz de transição associada ao sistema, considerando a ordem dos estados (R, A, F).

2.  
   a) Seja x₀ um vetor de distribuição inicial.  
   b) Determine o vetor de estado x₁, x₂ e x₃.  
   c) Escreva a forma geral de xₙ em função de P e x₀.

3. Verifique se existe um vetor estacionário x* tal que  
   x* = x* P  
   com soma das componentes igual a 1.

4. Resolva o sistema linear associado ao item anterior e determine x*, quando existir.

5. Interprete o vetor estacionário obtido no contexto da dinâmica neuronal.

---

## 🇺🇸 English Version

Consider a neuron whose dynamics can be described, in discrete time, by three states:

- **Resting (R)**: neuron at resting potential, with sodium channels mostly closed;
- **Active (A)**: occurrence of an action potential, associated with sodium channel opening;
- **Refractory (F)**: post-spike state in which channels are inactivated and the neuron cannot immediately fire again.

Assume that the evolution of these states follows a Markov chain.

The transitions are defined as follows:

- from (R), the neuron remains in (R) with probability (1 - p) or transitions to (A) with probability p;
- from (A), the neuron transitions to (F) with probability 1;
- from (F), the neuron transitions to (R) with probability q or remains in (F) with probability (1 - q).

---

### Tasks

1. Construct the transition matrix associated with the system, using the state order (R, A, F).

2.  
   a) Let x₀ be an initial probability vector.  
   b) Determine the state vectors x₁, x₂, and x₃.  
   c) Write the general form of xₙ in terms of P and x₀.

3. Verify whether there exists a stationary vector x* such that  
   x* = x* P  
   with components summing to 1.

4. Solve the associated linear system and determine x*, when it exists.

5. Interpret the stationary vector in the context of neuronal dynamics.