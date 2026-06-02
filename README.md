# Dirty Cafe Sales Analysis
## Objetivo
Explorar y limpiar un dataset de ventas de cafetería para obtener insights sobre productos, ventas, comportamiento de clientes y calidad de los datos.

## Descripción del proyecto
Este proyecto se centra en la limpieza de datos reales y el análisis exploratorio (EDA)
El dataset contiene problemas típicos del mundo real como:
- Valores faltantes
- Errores de registro
- Tipos de datos incorrectos
Después de la limpieza, el dataset se utiliza para analizar:
- Rendimiento de productos
- Ingresos
- Comportamiento de ventas por ubicación
- Tendecias en el tiempo

## Proceso de limpieza de datos
Durante la limpieza se realizaron las siguientes tareas:
- Conversión de tipos de datos (numéricos y fechas)
- Manejo de valores nulos
- Reemplazo de valores invalidos
- Imputación de valores usando lógica de negocio
- Eliminación de registros incompletos no recuperables

## Análisis realizados
- Productos con más ingresos
- Tendencia de ventas por mes
- Tienda con más ingresos
- Productos más rentables
- Días de mayor venta
- Participación de ventas

## Insights
### 1. Productos con mayor ingreso:
- Las ensaladas (Salad) son el producto con mayor generación de ingresos (16,575), seguidas de Sandwich y Smoothie. 
- Insight clave: La mayor parte de los ingresos dependen de pocos productos.
### 2. Tendencia de ventas por mes:
- Las ventas muestran fluctuaciones moderadas a lo largo del año, el comportamiento general es relativamente estable, sin tendencia fuerte de crecimiento o caída. 
- Insight clave: No hay crecimiento constante, sino estacionalidad leve y variaciones mensuales.
### 3. Ingresos por tipo de compra:
- In-store: 23,506.
- Takeaway: 22,849.
- Insight clave: El comportamiento de consumo está casi dividido al 50%, sin una modalidad dominante.
### 4. Productos más rentables (por ingresos vs cantidad):
- Salad, Sandwich y Smoothie no solo generan más ingresos, sino que también mantienen buen volumen de ventas.
- Cookie tiene alta cantidad vendida pero bajos ingresos, indicando bajo valor por unidad.
- Insight clave: No todos los productos tienen el mismo valor unitario; hay productos de alto volumen pero bajo ticket.
### 5. Días con mayor venta:
- Mayor actividad: Sunday (11,284) Friday (11,179).
- Menor actividad: Wednesday (10,389).
- Insight clave: Los fines de semana y pre-fin de semana concentran mayor consumo.
### 6. Participación de ventas:
- Salad representa el 21,6% del total de ingresos.
- Salad, Sandwich y Smoothie concentran casi el 55% de los ingresos.
- Cookie es el producto con menor participación (4%).
- Insight clave: Alta concentración de ingresos en pocos productos.

## Recomendaciones
1. Gestión de inventario enfocada en productos clave
- Priorizar stock y disponibilidad de Salad, Sandwich y Smoothie, ya que representa la mayor parte del ingresos.
2. Revisión de productos de bajo valor
- Cookie, Tea y Coffee generan menor ingreso relativo. Se recomienda:
- Ajustar precios.
- Mejorar marketing.
- Evaluar si mantener o reformular oferta.
3. Estrategia por días pico
- Incrementar personal y stock los días Friday, Saturday y Sunday para aprovechar mayor la demanda.
4. Reducir dependencia de pocos productos
- Como más del 50% de ingresos viene de pocos productos:
- Diversificar oferta.
- Promocionar productos secundarios.

## Conclusión
El análisis muestra que el negocio depende fuertemente de pocos productos clave, con una distribución de ingresos concentrada y variaciones moderadas en el tiempo. Esto sugiere oportunidades de diversificación y optimización operativa.

## Herramientas utilizadas
- Python
- Pandas
- Numpy
- Matplotlib
- Plotly
- Seaborn
- Jupyter Notebook
    
## Dataset
Fuente: Kaggle – Dirty Cafe Sales Dataset

