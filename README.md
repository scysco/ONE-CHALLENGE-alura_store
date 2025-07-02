-----

# Desafío Alura Store: Análisis de Datos para Decisión Estratégica 📊

Este repositorio contiene el análisis de datos exploratorio realizado para el **Desafío Alura Store**, propuesto por el programa **Oracle Next Education (ONE) + Alura Latam** para la formación de Científico de Datos.

El objetivo principal del proyecto es analizar el rendimiento de cuatro sucursales de la cadena "Alura Store" para proporcionar una recomendación, basada en evidencia, sobre cuál de ellas debería ser vendida para financiar un nuevo emprendimiento.

-----

## 📖 Contexto del Desafío

Un empresario, el Sr. Juan, necesita tomar una decisión estratégica: debe vender una de sus cuatro tiendas para obtener capital. Para minimizar el impacto en su negocio, ha solicitado un análisis de datos que identifique a la tienda con el menor rendimiento y, por lo tanto, la candidata ideal para la venta.

### Pregunta de Negocio

> ¿Qué tienda de la cadena Alura Store es la menos eficiente y debería ser recomendada para su venta?

-----

## Dataset

El análisis se basa en un conjunto de datos que contiene información detallada de las transacciones de las cuatro tiendas. Las columnas principales incluyen:

  * **Producto y Categoría:** Artículos vendidos y su clasificación.
  * **Precio y Costo de Envío:** Valores monetarios de la transacción y la logística.
  * **Fecha de Compra:** Información temporal de las ventas.
  * **Vendedor y Lugar de Compra:** Información sobre el personal y la ubicación de la venta.
  * **Calificación y Método de Pago:** Feedback del cliente y detalles de la transacción.
  * **Coordenadas Geográficas (lat, lon):** Ubicación del comprador para análisis geográfico.

-----

## 🛠️ Metodología y Análisis Realizado

Para responder a la pregunta de negocio, se realizó un análisis comparativo y multifacético, abordando el rendimiento de cada tienda desde diferentes ángulos:

1.  **Análisis de Rendimiento Fundamental:**

      * **Ingresos Totales (Valor):** Se comparó la facturación total de cada tienda para identificar cuál genera menos valor monetario.
      * **Volumen de Ventas (Cantidad):** Se analizó la cantidad de productos vendidos por categoría para entender la popularidad y el movimiento de inventario.

2.  **Análisis de Experiencia del Cliente:**

      * **Calificaciones Promedio:** Se evaluó la satisfacción del cliente para descartar que el bajo rendimiento se deba a una mala reputación.
      * **Costos de Envío:** Se compararon los costos promedio de logística como posible barrera de compra.

3.  **Análisis de Contexto Operativo:**

      * **Evolución Temporal:** Se creó una serie de tiempo para visualizar si el bajo rendimiento era un problema crónico o una caída reciente.
      * **Rendimiento de Vendedores:** Se analizó el desempeño del equipo de ventas de cada sucursal para determinar si el problema era general o individual.

-----

## 🚀 Resultados y Conclusión Clave

El análisis arrojó una conclusión consistente a través de todas las métricas evaluadas.

  * **Rendimiento Inferior:** La **Tienda 4** es la que presenta los **ingresos más bajos** y también el **menor volumen** de productos vendidos.
  * **Problema Crónico:** El bajo rendimiento de la Tienda 4 es **constante a lo largo del tiempo**, no una situación puntual.
  * **Desempeño General:** El problema no se atribuye a vendedores específicos, sino a un **rendimiento general inferior** de la sucursal en su conjunto.

### Recomendación Final

La recomendación final, basada en la convergencia de toda la evidencia, es **vender la Tienda 4**. Es la unidad de negocio menos productiva y su venta representa el menor impacto para la rentabilidad global de la cadena "Alura Store".

-----

## 🔧 Herramientas Utilizadas

  * **Lenguaje:** Python 3
  * **Librerías:**
      * `pandas` para la manipulación y análisis de datos.
      * `matplotlib` para la creación de visualizaciones estáticas.
  * **Entorno:** Jupyter Notebook

-----

## 📁 Cómo Ejecutar el Proyecto

1.  Clonar este repositorio en tu máquina local.
2.  Asegurarse de tener las librerías necesarias instaladas:
    ```bash
    pip install pandas matplotlib folium jupyter
    ```
3.  Abrir el archivo `Challenge_AluraStore.ipynb` utilizando Jupyter Notebook o Jupyter Lab para ver y ejecutar el análisis completo.

-----

## ✍️ Autor

  * **Francisco Jesus Sanchez Manuel**
  * **LinkedIn:** https://www.linkedin.com/in/scysco/
  * **GitHub:** https://github.com/scysco
