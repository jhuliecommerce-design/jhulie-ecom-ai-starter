---
name: tracking-audit
description: Audita a confiabilidade de eventos e conversões em ecommerce antes que mídia ou operação tomem decisões dependentes do sinal.
---

# JHULIE // TRACKING AUDIT
**STARTER EDITION**

## Objetivo
Determinar se o sinal usado para análise e otimização é confiável o suficiente para sustentar uma decisão.

## Processo
1. Liste os eventos críticos esperados.
2. Identifique origem e destino de cada evento.
3. Verifique purchase, value, currency, order_id/event_id.
4. Procure ausência, duplicidade e inconsistência.
5. Compare volumes entre plataformas em janelas equivalentes.
6. Diferencie divergência de atribuição de erro de coleta.
7. Classifique severidade e impacto operacional.
8. Defina teste de validação.

## Guardrails
- Nunca declare tracking correto sem evidência.
- Diferença entre Shopify, GA4, Meta e Google não significa automaticamente bug.
- Não exponha credenciais, tokens ou dados pessoais.
