# DataScience
# Análisis de Rendimiento de Tiendas - Alura Store

## Propósito del Análisis

El propósito de este proyecto es ayudar al Sr. Juan a decidir cuál de las cuatro tiendas de la cadena **Alura Store** debe vender para financiar un nuevo emprendimiento. Para ello, se realiza un análisis de datos basado en métricas clave como ingresos, calificaciones de clientes, costos de envío, categorías más vendidas y productos más vendidos. El análisis utiliza la biblioteca **Pandas** para manipulación de datos y **Matplotlib** para visualización, generando al menos tres gráficos diferentes para identificar la tienda menos eficiente. Finalmente, se proporciona una recomendación fundamentada sobre qué tienda vender.

## Estructura del Proyecto

Dado que el proyecto se ejecuta en **Google Colab**, no requiere una estructura de archivos local. Los datos se cargan directamente desde URLs públicas proporcionadas por Alura. La organización es la siguiente:

- **Notebook Principal**: `Alura_Store_Analysis.ipynb` (se crea en Google Colab al ejecutar el código).
  - Contiene el código completo para:
    - Analizar métricas (ingresos, calificaciones, costos de envío, categorías y productos más vendidos).
    - Generar visualizaciones (gráficos de barras y dispersión).
    - Proporcionar una recomendación final.
- **Datos**: Los datos de las cuatro tiendas se cargan desde las siguientes URLs:
  - Tienda 1: [tienda_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
  - Tienda 2: [tienda_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
  - Tienda 3: [tienda_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
  - Tienda 4: [tienda_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)
- **Dependencias**: 
  - Python 3
  - Bibliotecas: `pandas`, `matplotlib` (preinstaladas en Google Colab).

## Ejemplos de Gráficos

El análisis genera tres gráficos para visualizar el rendimiento de las tiendas. A continuación, se describen los gráficos y algunos insights típicos (los resultados exactos dependen de los datos reales):

1. **Gráfico de Barras: Ingresos Totales por Tienda**
   - **Descripción**: Compara los ingresos totales de cada tienda.
   
   
2. **Gráfico de Barras: Calificaciones Promedio por Tienda**
   - **Descripción**: Muestra la puntuación promedio de calificaciones de clientes (1-5) por tienda.


3. **Gráfico de Dispersión: Costo de Envío Promedio por Tienda**
   - **Descripción**: Visualiza el costo de envío promedio por tienda con etiquetas.
 
**Otros Insights**:
- **Categorías Más Vendidas**: Identifica la categoría principal por tienda (en ingresos). Por ejemplo, si la Tienda 3 depende excesivamente de una categoría de bajo margen, su modelo de negocio puede ser menos sostenible.
- **Productos Más Vendidos**: Muestra los productos más vendidos por tienda (en cantidad). Una tienda con pocos productos populares podría tener un inventario menos atractivo.
- **Recomendación Final**: Basada en los datos, la tienda con menores ingresos, peores calificaciones y/o costos de envío elevados (por ejemplo, Tienda 3) se recomienda para la venta.

**Nota**: Los gráficos e insights específicos dependen de los datos reales. Ejecuta el notebook para obtener resultados personalizados.

## Instrucciones para Ejecutar el Notebook

El proyecto está diseñado para ejecutarse en **Google Colab**, un entorno gratuito basado en la nube que no requiere configuración local. Sigue estos pasos:

1. **Accede a Google Colab**:
   - Abre [Google Colab](https://colab.research.google.com/) en tu navegador.
   - Inicia sesión con una cuenta de Google si es necesario.

2. **Crea un Nuevo Notebook**:
   - Haz clic en **File > New Notebook** para crear un nuevo notebook.

3. **Copia y Pega el Código**:
   - Copia el código proporcionado en el mensaje de respuesta (el código Python corregido).
   - Pégalo en una celda del notebook en Colab.

4. **Ejecuta el Notebook**:
   - Haz clic en el botón **Run** (triángulo de reproducción) en la celda, o presiona `Shift + Enter`.
   - El código se ejecutará automáticamente, cargando los datos desde las URLs, generando gráficos y mostrando la recomendación.

5. **Requisitos**:
   - **Conexión a Internet**: Necesaria para cargar los datos desde las URLs.
   - **Dependencias**: Las bibliotecas `pandas` y `matplotlib` están preinstaladas en Colab, por lo que no necesitas instalar nada.

6. **Verifica las Salidas**:
   - Revisa las salidas de depuración (por ejemplo, nombres de columnas) para confirmar que los datos se cargaron correctamente.
   - Observa los gráficos generados y el resumen de métricas.
   - Lee la recomendación final para conocer la tienda sugerida para la venta.


## Notas Adicionales

- **Datos**: Los CSV contienen columnas como `Producto`, `Categoría del Producto`, `Precio`, `Costo de envío`, `Fecha de Compra`, `Vendedor`, `Lugar de Compra`, `Calificación`, `Método de pago` y `Cantidad de cuotas`.

- **Personalización**: Los gráficos son básicos pero claros. Puedes modificar colores, tamaños o tipos de gráficos en el código si lo deseas.

Para cualquier duda o ajuste, contacta al desarrollador o revisa la documentación de las bibliotecas utilizadas (`pandas` y `matplotlib`).

---

**Autor**: Armando Vicencio  
**Fecha**: Abril 2025
