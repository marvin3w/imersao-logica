# [02-14] Proposições Compostas (I) — Conjuntiva, Disjuntiva e Condicional

## Por que isso importa?

"Se chover, levo guarda-chuva e cancelo o piquenique." Uma frase, três juízos entrelaçados. Desmontar proposições compostas em simples é pré-requisito para avaliar validade: silogismo clássico exige premissas categóricas ou hipotéticas bem identificadas.

## Conceito Central

Aristóteles, na tradição do *Organon*, ancora este ponto no raciocínio clássico.


**Proposição composta** combina duas ou mais proposições simples por conectivo lógico, formando um juízo único verdadeiro ou falso como um todo.

| Tipo | Conectivo | Estrutura |
|---|---|---|
| **Conjuntiva** | e / mas / porém | p **e** q |
| **Disjuntiva** | ou | p **ou** q |
| **Condicional** | se… então | **se** p, **então** q |

## Conjuntiva

Verdadeira apenas se **ambas** componentes são verdadeiras. "Chove e faz frio" — falsificada se uma parte falhar.

Atenção: "mas" e "porém" são conjuntivas com ênfase contrastiva; logicamente, ainda exigem verdade de p e q.

## Disjuntiva

- **Inclusiva:** p ou q (ou ambos). "Estudo ou trabalho" — pode fazer os dois.
- **Exclusiva:** p ou q (não ambos). "Ou ganhamos ou perdemos" — mutuamente exclusivo.

Contexto decide qual sentido vale; lógica pede explicitação.

## Condicional (hipotética)

"**Se** chove, **então** a rua molha." Não afirma que chove; afirma **dependência**: verdade de p implica verdade de q.

| Condicional é | Condicional não é |
|---|---|
| Juízo sobre conexão | Afirmação de antecedente |
| Falso se p verdadeiro e q falso | Equivalente a "p e q" |

## Aplicação prática

Contrato: "Entrega em 30 dias e pagamento na entrega." Duas obrigações conjuntivas. Descumprimento de uma viola a proposição composta inteira, mesmo que a outra parte cumpra. Identificar estrutura evita disputa sobre "cumprimento parcial".

## Tabela-verdade intuitiva (conjuntiva e condicional)

| p | q | p e q | se p então q |
|---|---|---|---|
| V | V | V | V |
| V | F | F | F |
| F | V | F | V |
| F | F | F | V |

Condicional falso **apenas** quando antecedente verdadeiro e consequente falso ("choveu mas rua seca"). Antecedente falso torna condicional verdadeiro vacuamente — contra-intuitivo, mas necessário para validade lógica formal.

## Condicional vs. causal

"Se chove, a rua molha" sugere causa; logicamente, afirma apenas implicação. Causa reforça condicional, mas condicional pode ser verdadeiro sem causalidade directa ("Se 2+2=4, então Paris é capital da França"). Não confundir implicação lógica com causalidade empírica.

## Conexões

- **Anterior:** [02-13 — Proposição](02-13-Proposicao.md)
- **Próximo:** [02-15 — Proposições Compostas 2](02-15-Proposicoes-Compostas-2.md) (exclusiva, exceptiva, reduplicativa)
- **Adiante:** [M03 — Silogismo hipotético](../Modulo-03-Raciocinio-Dedutivo/)

## Disjuntiva falsa

"Ou você está conosco ou está contra nós" — disjuntiva exclusiva que ignora contrariedades intermediárias. Lógica exige verificar se alternativas são **exaustivas** e **exclusivas** antes de forçar escolha.

## Aplicação prática (fecho)

Contratos com cláusulas "Se A, então B; se não A, então C" exigem verificar se "não A" cobre todos os casos não-A. Condicional mal formulado gera litígio quando evento não previsto ocorre.

## Auto-reflexão

1. "Ou chove ou não chove" — disjuntiva exclusiva ou tautologia?
2. Verdade de "Se 2+2=5, então a lua é queijo"?
3. Separe proposições simples em: "Estudo e, se passo, comemoro."
4. "Ou A ou B" com A e B compatíveis — que tipo de disjuntiva?
