# Dashboard de Desempeño Comercial | Andes Retail Group

Proyecto de análisis y visualización de datos desarrollado en Tableau Public para evaluar el desempeño comercial de Andes Retail Group en Perú, Chile y Colombia durante 2024 y 2025.

## Objetivo

Diseñar un dashboard ejecutivo que permita monitorear el comportamiento de ingresos y rentabilidad, identificar patrones de estacionalidad y comparar el desempeño por país, categoría de producto y segmento de cliente.

## Herramientas utilizadas

- Tableau Public
- Microsoft Excel
- Análisis exploratorio de datos
- Diseño de dashboards y storytelling con datos

## KPIs principales

- Ingresos Totales
- Margen Bruto
- Volumen Vendido
- Participación de Ventas de Alto Valor

## Visualizaciones incluidas

### Vista Overview
- KPIs principales del negocio
- Evolución de ingresos en el tiempo
- Heatmap de ingresos por país y categoría de producto
- Gráfico de ingresos por categoría de producto y segmento de cliente
- Filtros interactivos por año, país, categoría de producto y estación

### Vista Detail
- Ingresos por año y estación
- Comparación de margen bruto por región
- Ingresos por país y segmento de cliente
- Tabla detalle por país, región y categoría
- Filtros interactivos por año, región, estación y segmento de cliente

## Hallazgos clave

- El negocio presenta una marcada estacionalidad: los ingresos caen entre otoño e invierno y se recuperan hacia el cierre del período.
- Perú concentra los mayores ingresos en las categorías de Deportes y Electrónica.
- El segmento Premium lidera el aporte de ingresos en los tres países, aunque con distinta intensidad.
- Las regiones operan con márgenes relativamente similares, con diferencias más visibles en volumen de ingresos que en rentabilidad.

## Regla de negocio destacada

Se creó la variable **Nivel_Ventas** para clasificar las ventas según el criterio del negocio:

- **Venta Alta**: ingresos mayores o iguales a 1000
- **Venta Baja**: ingresos menores a 1000

A partir de esta clasificación se calculó la participación de ventas de alto valor dentro del total.

## Dashboard público

Puedes explorar la versión interactiva del dashboard en Tableau Public aquí:  
**(https://public.tableau.com/authoring/Proyecto9_Dayana_Rodriguez/Dashboard1/Detalle#1)**

## Capturas del proyecto

### Overview
![Overview del dashboard](images/overview-dashboard.png)

### Detail
![Detail del dashboard](images/detail-dashboard.png)

## Nota
El análisis fue diseñado inicialmente como parte del proceso de exploración en Power BI. Sin embargo, para fines de portafolio y acceso público, la versión documentada y compartida en este repositorio corresponde a Tableau Public.
