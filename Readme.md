# Análisis de Desempeño de Tiendas — Alura Store Latam

Este proyecto presenta un análisis integral del rendimiento de diferentes tiendas pertenecientes a la marca Alura Store Latam, con el objetivo de identificar cuál de ellas presenta un menor desempeño operativo y comercial, a fin de fundamentar una recomendación estratégica para su posible venta.

---

## Tecnologías Utilizadas

- Python 3.x  
- Pandas: procesamiento y análisis de datos.  
- NumPy: operaciones numéricas y cálculo de métricas.  
- Matplotlib: generación de gráficas y visualizaciones.  

---

## Descripción del Proyecto

El análisis se centra en comparar el desempeño de cuatro tiendas a través de distintos indicadores clave.  
Cada punto de evaluación otorga un punto negativo a la tienda con peor resultado dentro de la métrica analizada.  
La tienda con mayor cantidad de puntos negativos se considera la de peor rendimiento global.

### Indicadores Analizados

1. Ingresos Totales: volumen general de ventas.  
2. Categorías de Productos: diversidad y rendimiento por categoría.  
3. Calificaciones Promedio: nivel de satisfacción de los clientes.  
4. Relación entre Productos Más y Menos Vendidos: medición del equilibrio comercial mediante el índice `peso_unidades_vendidas`.  
5. Coste de Envío Promedio: evaluación de la eficiencia logística.  

---

## Metodología

El análisis se basa en una estructura de puntuación acumulativa:

- En cada categoría, la tienda con peor desempeño recibe 1 punto negativo.  
- Al finalizar, se suman los puntos totales para obtener un marcador global.  
- La tienda con mayor cantidad de puntos negativos se recomienda para ser vendida.

El flujo del análisis se documenta en el notebook, acompañado de gráficas y tablas que facilitan la interpretación visual de los resultados.

---

## Resultados Finales

| Tienda | Puntuación Total |
|:-------|:-----------------:|
| Tienda 1 | 1 |
| Tienda 2 | 2 |
| Tienda 3 | 1 |
| Tienda 4 | 1 |

Conclusión:  
La Tienda 2 obtuvo el mayor puntaje negativo, evidenciando un rendimiento inferior en varios indicadores clave.  
Por tanto, se recomienda su venta como acción estratégica.

---

## Ejecución del Proyecto

Para ejecutar el análisis, sigue estos pasos:

1. Abre el archivo `AluraStoreLatam.ipynb` en Google Colab o Jupyter Notebook.  
2. Asegúrate de tener instaladas las dependencias necesarias:
   ```bash
   pip install pandas numpy matplotlib
