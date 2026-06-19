# Análisis ConnectaTel — Sprint 7

## Objetivo
Evaluar el comportamiento de los clientes de ConnectaTel,
una empresa de telecomunicaciones en Latinoamérica,
mediante exploración, limpieza, visualización y segmentación
de datos registrados hasta el año 2024.

## Datasets utilizados
- `plans.csv` — información de los planes (precio, minutos, GB, costos extra)
- `users_latam.csv` — información de los clientes (edad, ciudad, plan, churn)
- `usage.csv` — detalle del uso real de servicios (llamadas y mensajes)

## Etapas del análisis
1. Carga y exploración inicial de los tres datasets
2. Identificación de problemas de calidad de datos (nulos, sentinels, fechas)
3. Limpieza básica (reemplazo de sentinels, fechas imposibles, verificación MAR)
4. Agrupación y resumen estadístico de uso por usuario
5. Visualización de distribuciones y detección de outliers
6. Segmentación de clientes por nivel de uso y grupo de edad
7. Análisis ejecutivo con recomendaciones para el negocio

## Cómo ejecutar el notebook
1. Abre el archivo en [Google Colab](https://colab.research.google.com/)
2. Sube los datasets a la carpeta `/datasets/` o ajusta las rutas según tu entorno
3. Ejecuta las celdas en orden de arriba hacia abajo

## Guía de reproducción
- Python 3.x
- Librerías necesarias: `pandas`, `seaborn`, `matplotlib`
- Los datasets deben estar disponibles en `/datasets/` antes de ejecutar
