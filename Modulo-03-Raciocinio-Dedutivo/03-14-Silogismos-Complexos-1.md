# [03-14] Silogismos Complexos (1)


<!-- nav-sequencial -->
> ← [Tipos de Silogismo](03-13-Tipos-de-Silogismo.md) · [Panorama](../00-Panorama-Geral.md) · [Índice](../README.md) · [Silogismos Complexos (2)](03-15-Silogismos-Complexos-2.md) →
<!-- /nav-sequencial -->








## Por que isso importa?

Nem todo raciocínio usa proposições categóricas ("Todo S é P"). Muitos argumentos do dia a dia são **condicionais**: "Se chover, cancelamos o piquenique. Choveu. Logo, cancelamos." Esse encadeamento é válido, mas não é silogismo categórico. É **silogismo hipotético**. Ignorá-lo deixa um terço dos argumentos reais fora da análise lógica.

Silogismos complexos tratam premissas compostas (condicionais, disjuntivas). Este documento foca no **hipotético**.

## Conceito Central

**Silogismo hipotético encadeia proposições condicionais** ("Se A, então B") com proposição que afirma ou nega o antecedente ou consequente, produzindo conclusão necessária.

## Formas válidas do hipotético

### Modus ponens (afirmando o antecedente)

```
Se A, então B.
A.
Logo, B.
```

Exemplo: "Se o contrato vence amanhã, devemos renovar. O contrato vence amanhã. Logo, devemos renovar."

### Modus tollens (negando o consequente)

```
Se A, então B.
Não B.
Logo, não A.
```

Exemplo: "Se a entrega foi feita, há recibo. Não há recibo. Logo, a entrega não foi feita."

## Formas inválidas (falácias formais)

| Forma inválida | Erro | Exemplo falacioso |
|---|---|---|
| Afirmar o consequente | De B inferir A | "Se chove, a rua molha. A rua molha. Logo, chove." (pode ser mangueira) |
| Negar o antecedente | De não-A inferir não-B | "Se estudo, passo. Não estudei. Logo, não passo." (pode passar por outro motivo) |

## Hipotético vs. categórico

| Silogismo categórico | Silogismo hipotético |
|---|---|
| Premissas AEIO | Premissa condicional + afirmação/negação |
| Termo médio liga extremos | Encadeamento de condicionais |
| Dictum de omni/nullo | Verdade funcional da condicional |

Será que "Se A então B" é verdadeiro sempre que A implica B? Depende da condicional *material* vs. *estrita*. Na lógica clássica aristotélica, trata-se sobretudo de implicação real (causa, natureza), não apenas de tabela-verdade. Num planejamento: "Se todos confirmarem, fazemos a festa" pressupõe relação real entre confirmação e festa, não mera coincidência.

## Aplicação prática

Numa conversa familiar: "Se você terminou a lição, pode jogar. Você está jogando." Alguém conclui "Então terminou a lição"? Falácia de afirmar o consequente. A criança pode estar jogando por outro motivo. Reconhecer a forma invalida evita acusações injustas e corrige o argumento antes da discussão escalar.

## Tabela de formas hipotéticas

| Forma | Nome | Validade |
|---|---|---|
| Se A→B; A; ∴ B | Modus ponens | Válida |
| Se A→B; ¬B; ∴ ¬A | Modus tollens | Válida |
| Se A→B; B; ∴ A | Afirmar consequente | Inválida |
| Se A→B; ¬A; ∴ ¬B | Negar antecedente | Inválida |

## Hipotético encadeado (sorites de condicionais)

"Se A então B. Se B então C. Se C então D. A. Logo D." Cada passo é modus ponens. Cadeias longas aparecem em protocolos ("Se autenticado, então autorizado; se autorizado, então acesso…"). Verifique cada condicional: uma ruptura no meio invalida o destino final.

## Conexões
- **Anterior:** [Tipos de Silogismo](03-13-Tipos-de-Silogismo.md)
- **Próximo:** [Silogismos Complexos (2)](03-15-Silogismos-Complexos-2.md)
- **Retorno:** Proposições compostas em M02
- **Referência clássica:** Pseudo-Robert Kilwardby; Boécio, *De Syllogismo Hypothetico*


## Auto-reflexão

1. Construa um modus ponens sobre uma decisão recente sua.
2. Por que "negar o antecedente" é falácia?
3. "Se A então B" e "Se B então A" são equivalentes?
