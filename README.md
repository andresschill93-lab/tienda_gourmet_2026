# Dashboard Interactivo - Tienda Gourmet

Sistema de control comercial que procesa datos históricos de ventas para apoyar 
la toma de decisiones. Incluye gráficos estáticos e interactivos integrados en 
un dashboard web, con una paleta de colores personalizada (tonos café y cobre).

## Funcionalidades

- **Pandas:** limpieza de datos y cálculo de márgenes de ganancia
- **Matplotlib:** evolución mensual de ventas (gráfico de líneas)
- **Seaborn:** rentabilidad por categoría (gráfico de barras)
- **Plotly:** distribución de ganancias (gráfico de torta interactivo)
- **Dash:** panel de control unificado en servidor web local

## Estructura
TIENDA_GOURMET/

├── data/          → base de datos (ventas_gourmet.csv)

├── sources/       → carga y limpieza de datos

├── view/          → gráficos (matplotlib, seaborn, plotly)

├── data_processing.py  → lógica de negocio

└── main.py        → punto de entrada del dashboard

## Instalación
```bash
pip install pandas matplotlib seaborn plotly dash
```

## Ejecución
```bash
py main.py
```
Abrí el navegador en: http://127.0.0.1:8050