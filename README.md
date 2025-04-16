# challenge1DataScience
# Análisis de Ventas por Tienda - Challenge Data Science LATAM
Este proyecto corresponde al desafío del curso de Data Science de Alura LATAM. Se analizan los datos de ventas de cuatro tiendas distintas, utilizando Python y bibliotecas como Pandas, Matplotlib, Seaborn y Folium para generar visualizaciones y extraer insights relevantes para la toma de decisiones.
## Objetivo
Determinar cuál tienda ofrece las mejores condiciones para vender los productos del Sr. Juan, con base en:
- Ingresos totales por tienda
- Categorías de productos más y menos vendidos
- Calificaciones promedio de los clientes
- Productos más y menos vendidos
- Costo promedio de envío por tienda
- Distribución geográfica de las ventas
## Herramientas utilizadas
- Python
- Google Colab
- Pandas
- Matplotlib / Seaborn
- Folium (para mapas interactivos)

## Análisis realizado
1. **Ingresos totales por tienda**
   - Se sumaron los valores de la columna `Precio` en cada tienda.
2. **Categorías más populares**
   - Se agruparon las ventas por `Categoría` y se contaron los registros.
3. **Calificaciones promedio**
   - Se calculó la media de la columna `Calificación` por tienda.
4. **Productos más y menos vendidos**
   - Se contaron los productos únicos más vendidos por tienda.
5. **Costo de envío promedio**
   - Se obtuvo el promedio de la columna `Costo envío` para cada tienda.
6. **Mapa geográfico**
   - Se usaron las columnas `lat` y `lon` para crear un mapa interactivo con `Folium`, mostrando la distribución de ventas por tienda y su ubicación promedio.
## Visualizaciones
- Gráficos de barras, gráficos circulares y mapas interactivos.
- Heatmaps para distribución geográfica de las ventas.
- Popups informativos en el mapa con los ingresos por tienda.
