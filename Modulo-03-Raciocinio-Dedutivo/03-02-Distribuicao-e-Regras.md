# [03-02] Distribuição e Regras

## Por que isso importa?

Dois colegas debatem: "Todo professor é dedicado. Algum dedicado é pontual. Logo, algum professor é pontual." A conclusão parece plausível, mas o argumento é inválido. O termo que deveria ligar as premissas ("dedicado") nunca foi tomado em toda a sua extensão. Esse erro só se detecta quando você domina **distribuição**.

Distribuição responde a uma pergunta simples: quando uso um termo numa proposição, estou falando de *todos* os indivíduos da extensão daquele termo, ou apenas de *alguns*? A resposta determina se um silogismo funciona ou colapsa.

## Conceito Central

**Um termo está distribuído quando é tomado em toda a sua extensão** (referindo-se a cada indivíduo abrangido pelo conceito). **Está não distribuído quando é tomado apenas em parte da extensão.**

## Regras de distribuição por forma AEIO

| Forma | Sujeito | Predicado |
|---|---|---|
| **A** (Todo S é P) | Distribuído | Não distribuído |
| **E** (Nenhum S é P) | Distribuído | Distribuído |
| **I** (Algum S é P) | Não distribuído | Não distribuído |
| **O** (Algum S não é P) | Não distribuído | Distribuído |

### Mnemônico prático

- **Sujeito** de **E** e **O** → distribuído (vogal "E" e "O" no sujeito)
- **Predicado** de **A** e **E** → distribuído (vogal "A" e "E" no predicado)

Mas por que essas regras? Porque "Todo S é P" fala de *todos* os S (sujeito distribuído), mas o P pode ser apenas um subconjunto dos P existentes (predicado não distribuído). Já "Nenhum S é P" exclui *todo* S de *todo* P: ambos os termos são distribuídos.

## Distribuição é / não é

| Distribuição é | Distribuição não é |
|---|---|
| Tomar o termo em toda extensão | Sinônimo de "importante" no argumento |
| Propriedade da *forma* da proposição | Depender do conteúdo (verdadeiro ou falso) |
| Ferramenta para validar silogismos | Opcional na análise dedutiva |

## Por que a distribuição importa para silogismos?

No silogismo, o **termo médio** deve aparecer distribuído pelo menos uma vez nas premissas. Se não aparecer, os extremos não se ligam. No exemplo do início, "dedicado" é predicado de uma proposição **I** nas duas premissas: nunca distribuído. Resultado: falácia do termo médio não distribuído (detalhada em [03-11](03-11-Principios-Regras-Silogismo-Simples.md)).

Pense na distribuição como um **zoom**: termo distribuído = zoom total sobre todos os indivíduos; termo não distribuído = zoom parcial. Para construir uma ponte entre dois extremos, o termo médio precisa cobrir toda a área de ligação pelo menos uma vez.

Numa busca de escola para o filho, "Toda escola particular tem ensino religioso" toma "escola particular" em toda extensão (distribuído), mas "ensino religioso" apenas parcialmente. Se você concluir algo sobre *todas* as formas de ensino religioso a partir dessa premissa, comete processo ilícito.

## Exercício de diagnóstico rápido

Para qualquer proposição categórica:

1. Identifique a forma (A/E/I/O)
2. Marque sujeito e predicado como D (distribuído) ou d (não distribuído)
3. Antes de silogizar, verifique se o termo médio terá pelo menos um D

Exemplo: "Nenhum inseto é mamífero" → E → sujeito D, predicado D. Se "inseto" for termo médio num silogismo, esta premissa cumpre a Regra 3 ([03-11](03-11-Principios-Regras-Silogismo-Simples.md)) por distribuir o médio.

## Distribuição e a Lei da Razão Inversa

Lembre [01-03 — O Conceito](../Modulo-01-Concepcao/01-03-Conceito.md): intensão e extensão obedecem à razão inversa. Distribuição opera sobre **extensão**: termo distribuído = toda a extensão em jogo. Quando um argumento "amplia" na conclusão o que estava restrito na premissa, frequentemente viola tanto distribuição quanto a razão inversa entre termos.

## Conexões

- **Anterior:** [03-01 — Formas AEIO](03-01-Formas-AEIO.md)
- **Próximo:** [03-03 — Forma Lógica Própria](03-03-Forma-Logica-Propria.md)
- **Adiante:** Regra 3 do silogismo ([03-11](03-11-Principios-Regras-Silogismo-Simples.md)) exige termo médio distribuído
- **Referência clássica:** Aristóteles, *Analíticos Próprios*; Leibniz, *Dissertatio de Arte Combinatoria*

## Auto-reflexão

1. Na proposição "Algum animal não é domesticável", quais termos estão distribuídos?
2. Por que o predicado de "Todo S é P" não está distribuído?
3. Identifique o termo médio não distribuído: "Todo gato é felino. Algum felino é selvagem. Logo, algum gato é selvagem."
