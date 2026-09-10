# JHULIE ECOM AI STARTER

**Uma camada pública e prática da minha lógica operacional para ecommerce, dentro do Claude Code.**

Este repositório não é um pack de prompts.

É uma versão enxuta do ecossistema **JHULIE ECOM AI SYSTEM**, criada para quem quer começar a operar ecommerce com agentes especializados, raciocínio estruturado e uma rotina diária de decisão.

## O que vem nesta Starter

- 6 agentes especialistas para ecommerce;
- 1 comando central: `/jhulie-daily`;
- skills reutilizáveis para análise;
- regras de integridade de dados;
- exemplo de uso sem formulário gigante;
- arquitetura pronta para rodar dentro do Claude Code.

## Os 6 agentes

| Identidade | Nome técnico | Função |
|---|---|---|
| **JHULIE // DIRECTOR** | `diretor-operacao` | coordena a operação, resolve conflitos e define prioridades |
| **JHULIE // STORE ANALYST** | `store-analyst` | lê métricas, funil e saúde comercial da loja |
| **JHULIE // STORE OPTIMIZER** | `store-optimizer` | CRO, PDP, coleção, UX e conversão |
| **JHULIE // META BUYER** | `meta-media-buyer` | diagnóstico e decisões de Meta Ads |
| **JHULIE // GOOGLE BUYER** | `google-media-buyer` | Search, Shopping, PMax e intenção |
| **JHULIE // TRACKING ANALYST** | `tracking-analyst` | GA4, Pixel/CAPI, Google Ads e qualidade do sinal |

## A lógica do sistema

```text
DADO REAL
   ↓
CONFIABILIDADE DO SINAL
   ↓
DIAGNÓSTICO
   ↓
GARGALO PRINCIPAL
   ↓
PRIORIDADE
   ↓
ESPECIALISTA
   ↓
AÇÃO / TESTE
   ↓
VALIDAÇÃO
```

A regra é simples:

> **Não tome uma decisão sofisticada em cima de um dado que ainda não é confiável.**

## JHULIE DAILY

O ponto de entrada principal da Starter é:

```text
/jhulie-daily
```

Você pode colar:

- screenshot de Shopify, Meta, Google ou GA4;
- export/CSV;
- poucas métricas;
- relatório;
- ou simplesmente explicar o que está acontecendo.

O sistema deve trabalhar com o que existe e pedir no máximo 1–3 dados adicionais quando eles realmente mudarem a decisão.

### Exemplo

```text
/jhulie-daily

Receita: $8.300
Pedidos: 118
CVR: 1,2%
Meta spend: $2.100
Google spend: $900
Observação: mobile caiu bastante nos últimos dias.
```

## Instalação

No terminal:

```bash
git clone https://github.com/jhuliecommerce-design/jhulie-ecom-ai-starter.git
cd jhulie-ecom-ai-starter
claude
```

Dentro do Claude Code:

```text
/agents
```

Você deverá encontrar os 6 especialistas do projeto.

Depois rode:

```text
/jhulie-daily
```

## O que esta Starter NÃO faz

Os agentes não possuem acesso mágico às suas contas.

Sem API, MCP ou backend conectado, eles trabalham com:

- dados que você fornecer;
- screenshots e arquivos;
- páginas públicas acessíveis;
- contexto do projeto.

Nunca devem afirmar que leram uma conta, alteraram campanha, publicaram tema ou executaram uma ação externa sem ferramenta real e confirmação de execução.

## Por que existe uma Starter

A Starter foi desenhada para mostrar uma diferença fundamental:

**IA não é só uma ferramenta para responder perguntas. Pode ser organizada como sistema operacional de decisão.**

Esta é apenas a porta de entrada do ecossistema **JHULIE ECOM AI SYSTEM**.

## Princípio

> **JHULIE ECOM AI — menos respostas soltas. Mais decisão operacional.**
