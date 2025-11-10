# Dashboard Corporativo (Power BI)

## Objetivo
Consolidar KPIs executivos em uma única página para decisão rápida.

## Modelo de Dados
![modelo-estrela](docs/model-star.png)

## KPIs e Métricas
- Ticket médio (por mês e acumulado)
- Churn (% e contagem)
- Receita por categoria / canal
- SLA de atendimento (prazos vs cumpridos)

## O que foi feito
- Modelagem em estrela (Fato Vendas + dimensões)
- Medidas DAX para KPIs e comparativos (YoY/MoM)
- Segmentações por período e categoria
- Página única “executiva” com drill visual

## Evidências
- Print principal: `docs/kpis.png`
- Modelo: `docs/model-star.png`
- Arquivo: `model/dashboard.pbix`
- (Opcional) Versão publicada: <link público do Power BI>

## Próximos passos
- Forecast simples com DAX
- Página 2: detalhamento por produto

## Licença
MIT
