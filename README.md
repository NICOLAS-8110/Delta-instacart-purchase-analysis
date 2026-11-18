# Delta-instacart-purchase-analysis<img width="1280" height="640" alt="WhatsApp Image 2026-11-17 at 3 00 46 PM (3)" src="https://github.com/user-attachments/assets/e292a454-f033-4381-9730-0461db809beb" />

# 🛒 Análisis de Hábitos de Compra en Instacart

## 📋 Descripción
**Instacart** es una plataforma de entrega de comestibles que permite a los usuarios realizar pedidos en línea y recibirlos directamente en su hogar. El objetivo de este proyecto fue analizar datos históricos de compras para comprender mejor los hábitos de consumo de los clientes, identificar patrones de comportamiento y generar información accionable para la toma de decisiones comerciales.

Para lograrlo, se integraron y procesaron múltiples conjuntos de datos relacionados con pedidos, productos, pasillos y departamentos, ejecutando procesos rigurosos de limpieza, validación y análisis exploratorio de datos (EDA).

## 🎯 Objetivos
- ✅ Evaluar la calidad e integridad de los conjuntos de datos disponibles.
- ✅ Identificar y corregir valores ausentes y registros duplicados.
- ✅ Analizar los patrones y frecuencias de compra de los clientes.
- ✅ Identificar los horarios y días de la semana con mayor actividad en la plataforma.
- ✅ Estudiar los tiempos entre compras y las tasas de recompra de productos.
- ✅ Detectar los artículos y categorías más populares de Instacart.
- ✅ Desarrollar visualizaciones claras que faciliten la interpretación de resultados.
- ✅ Generar hallazgos estratégicos que respalden decisiones basadas en datos.

## 🛠️ Herramientas y Habilidades Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas y Matplotlib
* **Entorno:** Jupyter Notebook
* **Técnicas:** Análisis Exploratorio de Datos (EDA), Limpieza y transformación de datos, Cruce de tablas relacionales y Visualización de datos.

## 📊 Fuente de Datos
El estudio se desarrolló utilizando una base de datos relacional de Instacart compuesta por cinco archivos principales que detallan órdenes, catálogos y comportamiento de usuarios:

* **Archivos utilizados:** `instacart_orders.csv`, `products.csv`, `order_products.csv`, `aisles.csv`, `departments.csv`
* **Variables clave analizadas:** `order_id`, `user_id`, `product_id`, `order_dow`, `order_hour_of_day`, `days_since_prior_order`, `product_name`, `department`, `aisle`, `reordered`.

## ⚙️ Metodología
1. **Exploración y auditoría:** Inspección inicial de los cinco datasets para evaluar su estructura y calidad.
2. **Saneamiento de datos:** Detección y tratamiento de valores faltantes, eliminación de duplicados y verificación de consistencia en llaves primarias.
3. **Análisis temporal:** Estudio de la distribución de pedidos por hora del día, día de la semana y tiempo transcurrido entre compras.
4. **Comportamiento de carrito:** Evaluación de la cantidad de pedidos por usuario y número de artículos por orden.
5. **Análisis de catálogo y lealtad:** Identificación de productos estrella, tasas de recompra y orden en que se agregan los artículos al carrito.
6. **Visualización:** Creación e interpretación de gráficos para comunicar los hallazgos de negocio.

## 💡 Principales Hallazgos
* **Horas pico diurnas:** Los pedidos se concentran mayoritariamente durante el día, especialmente entre la mañana y las primeras horas de la tarde.
* **Inicio de semana fuerte:** Los domingos y lunes registran el mayor volumen de órdenes en toda la plataforma.
* **Perfil de recurrencia:** La mayoría de los clientes realiza un número reducido de compras ocasionales, mientras que un segmento más pequeño mantiene una actividad altamente recurrente.
* **Tamaño del carrito:** El pedido típico (mediana) contiene alrededor de **8 productos**, con un promedio cercano a los **10 artículos** por compra.
* **Dominio de productos frescos:** Frutas, verduras y alimentos frescos lideran las preferencias; las **bananas** y los productos orgánicos encabezan tanto las ventas como las recompras.
* **Alta fidelidad:** Se detectaron tasas de recompra muy elevadas en productos de consumo básico y diario.
* **Prioridad en el carrito:** Los primeros artículos añadidos a la orden suelen ser productos esenciales y recurrentes en la compra habitual del usuario.

## 📈 Visualizaciones Desarrolladas
* Distribución de pedidos por hora del día y por día de la semana.
* Comparación de actividad por hora entre miércoles y sábado.
* Distribución del tiempo transcurrido entre pedidos.
* Distribución del número de pedidos por cliente y productos por orden.
* Rankings de productos más vendidos y artículos con mayor tasa de recompra.

## 📂 Archivos Principales
* `Delta_instacart_purchase_analysis.ipynb`
* `instacart_orders.csv`
* `products.csv`
* `order_products.csv`
* `aisles.csv`
* `departments.csv`

## 🏁 Conclusión
El análisis de los datos de Instacart permitió trazar una radiografía completa sobre los hábitos de compra de los usuarios tras un proceso riguroso de limpieza y validación. Los resultados confirman que la demanda se concentra en horarios diurnos y al arranque de la semana, con carritos medianos dominados por frutas, verduras y productos frescos de alta recompra. Estos hallazgos ofrecen una base sólida para optimizar la gestión de inventarios, afinar los motores de recomendación y diseñar promociones estratégicas basadas en datos.
