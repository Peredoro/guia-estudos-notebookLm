# Guia de Estudo — Pré-Cálculo para UNIVESP

---

#  Sumário

1. [Teoria de Conjuntos e Lógica](#1-teoria-de-conjuntos-e-lógica)
2. [Funções — O Coração do Cálculo](#2-funções--o-coração-do-cálculo)
3. [Trigonometria Elementar](#3-trigonometria-elementar)
4. [Glossário de Conceitos-Chave](#4-glossário-de-conceitos-chave)
5. [Prompts Reutilizáveis para Revisão](#5-prompts-reutilizáveis-para-revisão)

---

# 1. Teoria de Conjuntos e Lógica

##  Fundamentos

Um **conjunto** é uma coleção de objetos chamados **elementos**.

### Relações Básicas

| Relação | Símbolo | Significado |
|---|---|---|
| Pertinência | `∈` | Um elemento pertence a um conjunto |
| Inclusão | `⊂` | Um conjunto está contido em outro |

### Exemplo

```text
A = {1,2,3}

1 ∈ A
A ⊂ B
```

---

## Conjuntos Numéricos

Os conjuntos numéricos são fundamentais no estudo do cálculo.

### Hierarquia dos Conjuntos

```text
Naturais ⊂ Inteiros ⊂ Racionais ⊂ Reais ⊂ Complexos
```

### Principais Conjuntos

| Conjunto | Símbolo | Descrição |
|---|---|---|
| Naturais | `N` | Números positivos inteiros |
| Inteiros | `Z` | Positivos, negativos e zero |
| Racionais | `Q` | Frações e decimais exatos |
| Irracionais | `I` | Decimais infinitos não periódicos |
| Reais | `R` | Racionais + Irracionais |
| Complexos | `C` | Números com parte imaginária |

### Exemplo de Número Complexo

```math
\sqrt{-4} = 2i
```

---

##  Lógica Matemática

### Proposições

São sentenças que podem assumir apenas dois valores:

- Verdadeiro (`V`)
- Falso (`F`)

---

##  Operadores Lógicos

| Operador | Símbolo | Significado |
|---|---|---|
| E | `∧` | Ambas as proposições devem ser verdadeiras |
| OU | `∨` | Pelo menos uma deve ser verdadeira |
| NÃO | `¬` | Inverte o valor lógico |
| SE... ENTÃO | `→` | Implicação lógica |

### Exemplo

```text
p: "2 é par"
q: "5 é primo"

p ∧ q = verdadeiro
```

---

# 2. Funções — O Coração do Cálculo

##  Definição

Uma função associa cada elemento de um conjunto `A`
a um único elemento de um conjunto `B`.

```text
f: A → B
```

---

##  Função Afim (1º Grau)

### Fórmula Geral

```math
f(x)=ax+b
```

### Componentes

| Elemento | Significado |
|---|---|
| `a` | Inclinação da reta |
| `b` | Intercepto no eixo `y` |

### Características

- Gráfico em forma de reta
- Crescente se `a > 0`
- Decrescente se `a < 0`

### Exemplo

```math
f(x)=2x+3
```

---

##  Função Quadrática (2º Grau)

### Fórmula Geral

```math
f(x)=ax^2+bx+c
```

### Características

- Forma uma parábola
- Possui vértice
- Pode ter máximo ou mínimo

### Fórmula de Bhaskara

```math
x=\frac{-b \pm \sqrt{b^2-4ac}}{2a}
```

### Discriminante

```math
\Delta = b^2 - 4ac
```

---

##  Funções Exponenciais

### Fórmula

```math
f(x)=a^x
```

### Aplicações

- Crescimento populacional
- Juros compostos
- Decaimento radioativo

---

##  Logaritmos

### Definição

Logaritmo representa o expoente necessário
para transformar uma base em determinado valor.

```math
\log_a b = x
```

significa:

```math
a^x=b
```

### Exemplo

```math
\log_2 8 = 3
```

pois:

```math
2^3=8
```

---

# 3. Trigonometria Elementar

##  Círculo Trigonométrico

No círculo de raio unitário:

| Função | Representação |
|---|---|
| Seno | Coordenada `y` |
| Cosseno | Coordenada `x` |

---

##  Identidade Fundamental

```math
\sin^2(x)+\cos^2(x)=1
```

Essa relação é essencial para simplificação de expressões trigonométricas.

---

## Período

O período é o intervalo necessário
para que uma função trigonométrica repita seus valores.

| Função | Período |
|---|---|
| `sen(x)` | `2π` |
| `cos(x)` | `2π` |
| `tan(x)` | `π` |

---

# 4. Glossário de Conceitos-Chave

| Termo | Definição |
|---|---|
| Domínio (`D`) | Conjunto dos valores de entrada possíveis |
| Imagem (`Im`) | Valores efetivamente produzidos pela função |
| Módulo | Valor absoluto de um número |
| Raiz (Zero) | Valor que torna `f(x)=0` |
| Logaritmo | Expoente necessário para gerar um valor |
| Período (`T`) | Intervalo de repetição de funções trigonométricas |

---

# 5. Prompts Reutilizáveis para Revisão

##  Para Prática

```text
Gere um quiz de 5 questões sobre [Tópico da Semana UNIVESP]
com foco em exercícios de fixação.
```

---

##  Para Didática (Estilo Equaciona)

```text
Explique o conceito de [Tópico]
usando analogias simples e diretas,
como o Professor Paulo Pereira faria.
```

---

##  Para Revisão de Erros

```text
Analise o passo a passo desta questão de [Tópico]
e me diga onde costumam ocorrer
as falhas de lógica mais comuns.
```

---

##  Para Conexão de Conteúdos

```text
Como o conhecimento de [Tópico A]
será essencial quando eu começar
a estudar Limites e Derivadas?
```

---

#  Objetivo deste Guia

Este material foi estruturado para auxiliar nos estudos de Pré-Cálculo da UNIVESP, organizando os principais conceitos de forma:

- Clara
- Progressiva
- Objetiva
- Fácil para revisão em ciclos de estudo e Pomodoro

---
