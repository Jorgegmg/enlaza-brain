# Dashboard Diario - Evolución Delegaciones

## Objetivo
Generar HTML interactivo con estado consolidado de operaciones del día anterior.

## Inputs
- Archivo: `/DATOS/OAC-Exports/[fecha]-scorecard.csv`
- Columnas requeridas: sr_fecha, sr_plaza, sr_trafico, sr_ori, sr_des, Facturación€, Total Palets
- Delegaciones: 089 (Barcelona), 283 (Madrid), 461 (Valencia), 129 (Castellón)

## Outputs
- Archivo HTML: `/LOGS/Dashboard-Outputs/[fecha]-dashboard.html`
- Distribución: Email + Teams
- Visualizaciones:
  - KPIs consolidados (Facturación total, palets totales, margen promedio)
  - Gráfico comparativo delegaciones (4 colores)
  - Evolución 7 días (tendencias)
  - Top rutas por volumen y facturación
  - Tabla detalle por delegación

## Criterios de éxito
- ✓ Colores Valencia (461+129), Madrid, Barcelona respetando convención
- ✓ Números comparables con día anterior (incluir % variación)
- ✓ Responsive (funciona en mobile para Teams)
- ✓ Interactivo (filtros, hover, tooltips)
