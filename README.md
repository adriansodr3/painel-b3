# Painel B3

Painel web para acompanhar ações da bolsa brasileira com dados reais da [brapi.dev](https://brapi.dev).

**Acesse:** https://adriansodr3.github.io/painel-b3

## Funcionalidades

- Faixa de mercado: Ibovespa, dólar, euro, Selic e IPCA 12 meses
- Gráfico de candles ou linha com médias móveis (9 e 21) e volume — períodos de 5 dias, 1 e 3 meses
- Indicadores: P/L, LPA, valor de mercado, IFR(14), volatilidade anualizada, faixa de 52 semanas
- Maiores altas, maiores baixas e mais negociadas (entre as 150 ações mais líquidas)
- Lista de acompanhamento com busca de tickers, salva no navegador
- Fila de requisições e cache para respeitar a cota da API (contador mensal visível)

## Tecnologias

- HTML, CSS e JavaScript puros, sem build
- [Lightweight Charts](https://github.com/tradingview/lightweight-charts) para os gráficos
- API REST da brapi.dev

## Como usar

1. Abra o site.
2. Crie um token gratuito em [brapi.dev](https://brapi.dev) e cole no botão **Token da API**. Ele fica salvo apenas no seu navegador (localStorage), nunca no código.
3. Sem token, apenas PETR4, VALE3, ITUB4 e MGLU3 retornam dados.

## Limitações (plano gratuito da brapi)

- Atraso de até 30 minutos nas cotações
- Histórico de até 3 meses
- Um ativo por requisição e 15.000 requisições por mês
- P/VP, ROE e dividendos exigem plano pago

> Projeto de estudo. Não é recomendação de investimento.
