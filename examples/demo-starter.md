# Demo Starter — teste o raciocínio do sistema

Use esta demo para entender em poucos minutos por que o **JHULIE ECOM AI STARTER** não é só uma coleção de prompts.

## Rode
Dentro do Claude Code:

```text
/jhulie-daily
```

Depois cole:

```text
PERÍODO: últimos 3 dias
COMPARAÇÃO: 3 dias anteriores

SHOPIFY
Revenue: $18.600 → $16.900
Orders: 248 → 211
AOV: $75,00 → $80,09
CVR: 1,82% → 1,26%
Mobile CVR: 1,61% → 0,91%
Desktop CVR: 2,24% → 2,13%

META
Spend: $5.200 → $5.380
Platform revenue: $12.400 → $13.100
Purchases reported: 171 → 183
CPA: $30,41 → $29,40
CTR link: 1,44% → 1,46%
CPC link: $1,19 → $1,17

GOOGLE
Spend: $1.960 → $2.020
Platform revenue: $4.700 → $4.410
CPA: $36 → $40

OBSERVAÇÃO
Nenhuma grande mudança de criativo foi feita.
```

## O que uma leitura rasa pode fazer
- dizer que Meta melhorou e recomendar escala;
- culpar Google pela queda geral;
- pedir troca de criativo sem evidência.

## O que o JHULIE // DIRECTOR deve perceber
- Shopify mostra queda de pedidos e CVR;
- mobile deteriorou muito mais que desktop;
- Meta reporta melhora enquanto Shopify registra piora geral;
- CTR e CPC do Meta estão praticamente estáveis;
- existe risco de inconsistência de tracking/atribuição;
- existe sinal forte de problema pós-clique/mobile;
- escalar antes de validar essas premissas aumenta risco.

## Resultado esperado
A resposta não precisa ser idêntica, mas deve chegar perto de:

1. Não escalar Meta ainda.
2. Validar a discrepância entre purchases/revenue da plataforma e Shopify.
3. Investigar a queda de CVR mobile.
4. Diagnosticar Google separadamente, sem tratá-lo como explicação única da queda.
5. Não trocar criativos apenas porque a operação piorou.
6. Acionar Tracking Analyst + Store Analyst/Optimizer antes de mudança agressiva de budget.

> **JHULIE ECOM AI — o valor não está em dar mais respostas. Está em evitar a decisão errada primeiro.**

Todos os dados desta demo são fictícios e educacionais.
