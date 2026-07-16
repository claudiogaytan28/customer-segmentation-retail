# Segmentación de Clientes en Transacciones Retail

Identificación de patrones de comportamiento de clientes en datos de
transacciones retail mediante clustering, con el fin de generar hallazgos
accionables orientados al negocio.

## Problema

Las empresas de retail suelen tratar a todos sus clientes de la misma manera,
aunque el comportamiento de compra varía enormemente entre ellos. Este proyecto
responde una pregunta concreta: **¿qué tipos de clientes existen en este negocio,
según su comportamiento real de compra?**

## Metodología

1. Limpieza de datos
2. Feature engineering a nivel cliente (transacciones, gasto, uso de descuentos y promociones)
3. Escalado de variables
4. Clustering con KMeans (k seleccionado mediante el método del codo)
5. Visualización con PCA
6. Interpretación de clusters

## Hallazgos principales

- **El ticket promedio es estable en todos los segmentos (~$52)** — lo que
  realmente diferencia a los clientes es la frecuencia de compra, no el tamaño
  del carrito.
- **Cinco perfiles de cliente distintos**, desde compradores esporádicos
  impulsados por descuentos hasta clientes leales y frecuentes que concentran
  la mayor parte del valor.
- **Implicación de negocio:** la retención y la frecuencia de compra — no el
  ticket promedio — son las palancas más prometedoras para aumentar el valor
  del cliente.

## Herramientas

Python · pandas · scikit-learn · matplotlib

## Notebook

[Ver notebook completo →](https://github.com/claudiogaytan28/customer-segmentation-retail/blob/main/02_customer_segmentation.ipynb)
