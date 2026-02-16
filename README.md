# Presupuestos de España Explicados

Dashboard interactivo que explica los Presupuestos Generales del Estado (PGE) de España de forma visual y accesible.

## Qué es

Una aplicación web autocontenida (HTML + Chart.js) con 7 pestañas que desglosan los PGE vigentes (2025 prorrogados):

- **Visión general** - Resumen del presupuesto consolidado
- **Ingresos** - Clasificación económica de ingresos
- **Gastos** - Clasificación económica de gastos
- **Políticas** - Las 30 políticas de gasto
- **Estructura** - Subsectores (Estado, SS, OO.AA.)
- **CCAA** - Transferencias a Comunidades Autónomas
- **Contexto** - Déficit, deuda y perspectivas

## Datos

Fuente oficial: [SEPG - Ministerio de Hacienda](https://www.sepg.pap.hacienda.gob.es/sitios/sepg/es-ES/Presupuestos/DocumentacionEstadisticas/Estadisticas/paginas/estadisticas.aspx) (enero 2026). Datos complementarios de La Moncloa, Eurostat, AIReF y Banco de España.

## Uso

Abrir `index.html` en cualquier navegador. No requiere servidor ni instalación. Necesita conexión a internet solo para cargar Chart.js desde CDN.

## Notas

- España no ha aprobado nuevos PGE desde 2023. Los datos 2024-P y 2025-P son prorrogados.
- Los PGE solo muestran ~5.500 M€ en sanidad y ~5.300 M€ en educación (competencias transferidas a CCAA). El gasto real de todas las AAPP es ~95.000 M€ y ~62.000 M€ respectivamente.

## Licencia

Datos de dominio público (Gobierno de España). Código y visualización: MIT.
