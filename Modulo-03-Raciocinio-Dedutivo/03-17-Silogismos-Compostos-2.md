# [03-17] Silogismos Compostos (2)


<!-- nav-sequencial -->
> ← [Silogismos Compostos (1)](03-16-Silogismos-Compostos-1.md) · [Panorama](../00-Panorama-Geral.md) · [Índice](../README.md) · [Módulo 4 — Indução e Crítica Argumentativa](../Modulo-04-Inducao-Critica/04-00-Visao-Geral.md) →
<!-- /nav-sequencial -->








## Por que isso importa?

Argumentos longos costumam ser apresentados compactos: "Todo A é B; todo B é C; todo C é D; logo, todo A é D." Sem escrever cada silogismo intermediário. Isso é **sorites**: polissilogismo abreviado. Dominá-lo fecha o M03 com a forma mais usada em demonstrações extensas, da matemática elementar à argumentação filosófica.

## Conceito Central

**Sorites é argumento composto que encadeia várias premissas categóricas em sequência, suprimindo conclusões intermediárias**, chegando a uma conclusão final que liga o primeiro termo ao último.

## Sorites aristotélico vs. gocleniano

| Tipo | Direção da extensão | Estrutura |
|---|---|---|
| **Aristotélico** | Extensão **crescente** | Predicado da premissa anterior = sujeito da próxima |
| **Gocleniano** | Extensão **decrescente** | Sujeito da anterior = predicado da próxima |

### Sorites aristotélico (exemplo)

```
Todo A é B.
Todo B é C.
Todo C é D.
Logo, todo A é D.
```

Predicado de cada linha (B, C) reaparece como sujeito da seguinte. Extensão "sobe" até D.

### Sorites gocleniano (exemplo)

```
Todo D é C.
Todo C é B.
Todo B é A.
Logo, todo D é A.
```

Sujeito de cada linha reaparece como predicado da seguinte. Extensão "desce" de D para A.

## Proslipsis e epagoge

- **Proslipsis:** premissa tácita ou suprimida no sorites (termo ou proposição subentendida). Análogo ao enthymema ([03-09](03-09-Tipos-de-Inferencia.md)), mas em cadeia.
- **Epagoge:** termo usado na conclusão que não apareceu explicitamente nas premissas visíveis; exige reconstrução da cadeia completa.

Será que suprimir passos é sempre falha? Não, se cada passo suprimido seria válido. O risco é esconder um elo inválido. Na prática, expandir o sorites em polissilogismo ([03-16](03-16-Silogismos-Compostos-1.md)) é o teste de sanidade.

## Sorites válido vs. inválido

| Válido | Inválido |
|---|---|
| Cada elo respeitaria silogismo simples | Quebra de distribuição em algum elo oculto |
| Mesma suposição de termos ao longo da cadeia | Homonímia em termo intermediário |
| Conclusão não mais forte que premissas | Conclusão universal a partir de premissas particulares |

## Aplicação prática

Numa argumentação moral clássica: "Todo ato injusto é ilegítimo. Todo ilegítimo é condenável. Todo condenável deve ser evitado. Logo, todo ato injusto deve ser evitado." Sorites aristotélico. Antes de aceitar, expanda em três silogismos e verifique cada regra de [03-11](03-11-Principios-Regras-Silogismo-Simples.md). Um elo quebrado derruba toda a cadeia.

## Conexões
- **Anterior:** [Silogismos Compostos (1)](03-16-Silogismos-Compostos-1.md)
- **Próximo:** [Módulo 4 — Indução e Crítica Argumentativa](../Modulo-04-Inducao-Critica/04-00-Visao-Geral.md)
- **Retorno:** Enthymema e epicheirema em [03-09](03-09-Tipos-de-Inferencia.md)
- **Referência clássica:** Goclenius; Aristóteles, encadeamentos no *Analíticos*


## Auto-reflexão

1. Converta um sorites de três premissas em polissilogismo explícito.
2. Qual a diferença prática entre sorites aristotélico e gocleniano?
3. O M03 termina aqui. Qual lacuna resta que o M04 preenche?
