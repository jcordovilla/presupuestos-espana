# Presupuestos de España Explicados

Panel interactivo que explica los Presupuestos Generales del Estado (PGE) de España de forma visual y accesible.

**[Ver el panel](https://jcordovilla.github.io/presupuestos-espana/)**

## Por qué

En 2021 publiqué [La odisea de entender los PGE](https://www.linkedin.com/pulse/la-odisea-de-entender-los-pge-jose-cordovilla), un artículo en el que contaba mi experiencia intentando descifrar los presupuestos públicos de mi país. Pasé semanas cruzando documentos contables, libros y capítulos de los PGE para poder responder a preguntas básicas: ¿cuánto ingresa el Estado? ¿En qué se gasta? ¿Cuánto se destina a infraestructuras, sanidad o educación?

Cinco años después, la situación no ha mejorado. Los PGE siguen siendo documentos contables pensados para justificar el aparato administrativo, no para informar al ciudadano. La transparencia presupuestaria en España es nominal: los datos existen, pero están dispersos en decenas de hojas Excel con clasificaciones crípticas, años prorrogados sin señalar, y cifras que no se pueden comparar sin entender la estructura institucional que hay detrás.

Este dashboard es un intento de hacer lo que el Estado debería hacer: presentar los presupuestos de forma que cualquiera pueda entenderlos.

## Qué es

Una aplicación web autocontenida (HTML + Chart.js) con 7 pestañas que desglosan los PGE vigentes (2025 prorrogados):

- **Visión general** — Resumen del presupuesto consolidado (578.183 M€)
- **Ingresos** — Clasificación económica: impuestos, cotizaciones, tasas, transferencias
- **Gastos** — Clasificación económica: personal, bienes, intereses, transferencias, inversiones
- **Políticas** — Las 30 políticas de gasto, de pensiones (190.687 M€) a cultura (1.652 M€)
- **Estructura** — Subsectores: Estado (43%), Seguridad Social (45%), OO.AA. (10%), resto (2%)
- **CCAA** — Transferencias a Comunidades Autónomas y la diferencia con las entregas a cuenta
- **Contexto** — Déficit, deuda pública y proyecciones hasta 2028

## Uso

Abrir `index.html` en cualquier navegador. No requiere servidor ni instalación. Necesita conexión a internet solo para cargar Chart.js desde CDN.

## Notas importantes

- España no ha aprobado nuevos PGE desde 2023. Los datos 2024-P y 2025-P son prorrogados (prácticamente idénticos a los de 2023).
- Los PGE solo muestran ~5.500 M€ en sanidad y ~5.300 M€ en educación. El gasto real de todas las AAPP es ~95.000 M€ y ~62.000 M€ respectivamente (competencias transferidas a CCAA).
- Las transferencias PGE a CCAA (~42.520 M€) no son comparables con las entregas a cuenta totales (~157.731 M€), que incluyen la participación en impuestos cedidos.

## Fuentes

### Datos presupuestarios (fuente principal)

- [Estadísticas presupuestarias — SEPG, Ministerio de Hacienda](https://www.sepg.pap.hacienda.gob.es/sitios/sepg/es-ES/Presupuestos/DocumentacionEstadisticas/Estadisticas/paginas/estadisticas.aspx) — Ficheros Excel con los PGE consolidados, del Estado, Seguridad Social, Organismos Autónomos y resto de entidades (enero 2026)
- [Descarga de datos PGE — Oficina Virtual IGAE](https://www.oficinavirtual.pap.hacienda.gob.es/sitios/oficinavirtual/es-ES/InformacionUtilidades/UtilidadesPresupuestarias/ElaboracionPge05/Paginas/DescargaPge05.aspx) — Portal de descarga oficial (futuro PGE 2026)

### Techo de gasto y financiación territorial

- [Techo de gasto 2026 — La Moncloa (18/11/2025)](https://www.lamoncloa.gob.es/consejodeministros/resumenes/paginas/2025/181125-rueda-de-prensa-ministros.aspx) — 212.026 M€ (sin fondos UE) / 216.177 M€ (con Plan de Recuperación)
- [Nota de prensa techo de gasto — Ministerio de Hacienda](https://www.hacienda.gob.es/en-GB/Prensa/Noticias/Paginas/2025/20251118-NP-CM-TECHO-GASTO.aspx) — Entregas a cuenta a CCAA (157.731 M€) y EELL (29.246 M€)

### Déficit y deuda pública

- [Déficit y deuda 2024 — Eurostat vía Swissinfo](https://www.swissinfo.ch/spa/espa%C3%B1a-cerr%C3%B3-2024-con-un-d%C3%A9ficit-del-3,2-%25-y-una-deuda-del-101,8-%25-del-pib,-seg%C3%BAn-eurostat/89197001) — Déficit 3,2%, deuda 101,8% PIB (2024)
- [Análisis déficit público 2024 — CaixaBank Research](https://www.caixabankresearch.com/es/publicaciones/notas-breves-actualidad-economica-y-financiera/espana/deficit-publico-descendio-315)
- [Deuda pública 2024 — Banco de España](https://www.bde.es/f/webbe/SES/Secciones/Publicaciones/PublicacionesSeriadas/DocumentosOcasionales/25/Fich/be2503-art04.pdf)

### Informes de referencia

- [Informe de Presupuestos Iniciales 2025 — AIReF](https://www.airef.es/wp-content/uploads/2025/04/Informes_presupuestos_iniciales/Informe-Presupuestos-Iniciales-2025.pdf)

## Aviso

Este dashboard tiene un propósito estrictamente informativo. No es un documento oficial ni pretende sustituir a las fuentes primarias.

Los datos proceden de fuentes públicas y han sido procesados con la ayuda de herramientas de inteligencia artificial. Tanto la IA como el autor pueden cometer errores de interpretación, transcripción o cálculo. Si detectas alguno, agradezco que lo reportes abriendo un [issue](https://github.com/jcordovilla/presupuestos-espana/issues).

Dicho esto: que un ejercicio ciudadano de divulgación pueda contener alguna imprecisión no exime a las administraciones públicas de su obligación de informar con claridad sobre cómo gestionan los recursos de todos. Ese servicio, a día de hoy, sigue sin prestarse.

## Licencia

Datos de dominio público (Gobierno de España). Contenido y visualización: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es).

---

**Autor:** [Jose Cordovilla](https://www.linkedin.com/in/josecordovilla/) · Director de Consultoría Estratégica en [TYPSA](https://www.typsa.com). Experto en infraestructuras y gestión pública. Hecho con la ayuda de mis agentes de IA, principalmente de [Claude](https://claude.ai) (Anthropic).
