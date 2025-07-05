# Análisis Exploratorio de Datos – Instacart Orders

## Descripción del Proyecto

Este proyecto fue desarrollado como parte del Sprint 4 del bootcamp de análisis de datos de TripleTen. Utiliza un conjunto de datos modificado de la plataforma de entregas de comestibles **Instacart**, originalmente publicado en una competencia de Kaggle. El objetivo es aplicar técnicas de limpieza, transformación y análisis exploratorio para descubrir patrones en los hábitos de compra de los usuarios.

---

## Etapas del Proyecto

### 1. Carga y Exploración de Datos
- Lectura de cinco archivos CSV: `orders`, `products`, `order_products`, `aisles`, `departments`.
- Revisión de estructura, tipos de datos y primeras observaciones.

### 2. Preprocesamiento
- Conversión de tipos de datos.
- Identificación y tratamiento de valores ausentes.
- Eliminación de duplicados.
- Justificación de decisiones de limpieza.

### 3. Análisis Exploratorio

#### [A] Análisis general:
- Validación de rangos en `order_hour_of_day` y `order_dow`.
- Gráficos de pedidos por hora del día y día de la semana.
- Análisis del tiempo entre pedidos.

#### [B] Comportamiento de compra:
- Comparación de hábitos de compra entre miércoles y sábados.
- Distribución del número de pedidos por cliente.
- Identificación de los 20 productos más pedidos.

#### [C] Reordenamientos y patrones:
- Distribución de artículos por pedido.
- Productos más frecuentemente reordenados.
- Proporción de reordenamientos por producto y por cliente.
- Productos más comunes como primer artículo en el carrito.

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- Análisis exploratorio de datos (EDA)  
- Limpieza y transformación de datos

---

## Diccionario de Datos

| Tabla               | Descripción                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `instacart_orders`  | Información de cada pedido (usuario, día, hora, frecuencia)                 |
| `products`          | Detalles de cada producto (nombre, pasillo, departamento)                   |
| `order_products`    | Relación entre pedidos y productos (orden de carrito, reordenamientos)      |
| `aisles`            | Categorías de pasillos                                                      |
| `departments`       | Categorías de departamentos                                                 |

---

## Resultados

- Se identificaron patrones de compra por hora y día de la semana.
- Se detectaron productos con alta frecuencia de reordenamiento.
- Se analizaron hábitos de compra por cliente y comportamiento en el carrito.
- Se generaron visualizaciones claras para comunicar hallazgos clave.

---

## 📫 Contacto

Paz Emmanuel Balderas Cerezo  
📧 pazemmanuel24032005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/paz-emmanuel-balderas-cerezo-dataanalyst)
