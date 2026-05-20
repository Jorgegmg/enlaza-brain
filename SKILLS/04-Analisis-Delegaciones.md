# Análisis Comparativo Delegaciones (Tendencias)

## Objetivo
Identificar patrones, anomalías y desempeño relativo entre delegaciones.

## Inputs
- Histórico últimos 28 días de CSVs (archivados en /DATOS)
- Métricas: Facturación, palets, margen bruto, SLA cumplimiento

## Outputs
Dashboard con:
- Gráfico de tendencias (28 días)
- Ranking actual vs ranking semana anterior
- Anomalías detectadas (cambios >15% día a día)
- Margen por delegación (comparativo)
- Productividad (facturación/palé)

## Criterios de éxito
- ✓ Detecta delegaciones en riesgo
- ✓ Resalta oportunidades (qué hace bien Madrid vs Barcelona)
- ✓ Sugiere acciones si hay caída
- ✓ Comparable con histórico

## Frecuencia
- Bi-semanal: Lunes 09:00
- Input: Sube CSVs de último mes
