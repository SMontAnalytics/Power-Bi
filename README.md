# 📊 Power Bi - Tienda de Tecnología

Este proyecto presenta un conjunto de dashboards desarrollados en **Power BI** para analizar el rendimiento comercial de una tienda de tecnología. Utiliza múltiples fuentes de datos integradas en un modelo relacional para ofrecer una visión completa de las ventas, rentabilidad, comportamiento de clientes y desempeño por zonas geográficas.

---

## 📁 Archivos utilizados

El modelo se construyó a partir de los siguientes archivos en formato Excel:

- `Clientes.xlsx`: Información detallada de clientes (perfil, contacto, educación, ocupación, descuentos).
- `Producto.xlsx`: Catálogo de productos con atributos técnicos y logísticos.
- `Medios de pago.xlsx`: Métodos de pago disponibles y sus descuentos asociados.
- `Territorio.xlsx`: Ubicación geográfica de las ventas (ciudad, país, coordenadas).
- `Vendedor.xlsx`: Datos de los vendedores, sucursales y zonas de operación.
- `Ventas`: Tabla de hechos que conecta todas las dimensiones anteriores.

---

## 🧠 Modelo de Datos

El modelo sigue una estructura tipo **estrella**, con la tabla de hechos `Ventas` en el centro y las siguientes dimensiones:

- **Clientes**
- **Producto**
- **Medios de pago**
- **Territorio**
- **Vendedor**
- **Tiempo** (generada en Power BI para análisis temporal)

Relaciones establecidas mediante claves como `Id cliente`, `Id Prod`, `Cod Pago`, `Id Ubicación`, `Id vendedor`.

---

## 📈 Visualizaciones principales

### 1. Detalle de Ventas
- Filtros por ciudad y método de pago.
- Métricas clave: total de ventas, costos, rentabilidad, diferencia de días.
- Segmentación por zona geográfica (Sur, Norte, Oriente, Occidente).
- Tendencia de ventas por mes y año.
- Comparación de ventas y rentabilidad por método de pago.

### 2. Overview Financiero
- Totales acumulados: ventas, costos, rentabilidad, cantidades vendidas.
- Gráficos por mes, zona, tamaño de producto y método de pago.
- Análisis de rentabilidad por segmento (B2B vs B2C).

---

## 🎯 Objetivo del proyecto

Brindar una herramienta visual e interactiva para:

- Identificar tendencias de ventas y rentabilidad.
- Evaluar el impacto de los métodos de pago y descuentos.
- Analizar el comportamiento por zona, ciudad y segmento comercial.
- Tomar decisiones estratégicas basadas en datos.

---

## 🛠️ Tecnologías utilizadas

- **Power BI Desktop**
- **Excel** (como fuente de datos)
- **Modelo relacional** con relaciones uno a muchos
- **DAX** para medidas y cálculos personalizados



