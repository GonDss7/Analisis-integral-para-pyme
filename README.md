# 🛒 Retail B2C Analytics – End-to-End Data Project  
Análisis integral de una pyme B2C de productos consumibles, desarrollado completamente desde cero.  
Incluye diseño de base de datos, ETL, KPIs, modelado financiero y dashboard interactivo.

---

## 📌 1. Descripción del Proyecto

Este proyecto consiste en la creación end-to-end del ecosistema de datos de una **pyme real del sector retail B2C**, dedicada a la venta de productos consumibles.

Todo el sistema fue **desarrollado desde cero**, incluyendo:

- Construcción del dataset maestro  
- Modelado de productos, categorías, marcas y proveedores  
- Generación de tablas de ventas, stock y movimientos  
- Diseño de estructura de costos  
- Cálculo de márgenes, pricing, indicadores financieros y operativos  
- Proceso ETL completo (Excel → SQL/Python → Dashboard)  
- Visualización final en Tableau / Power BI

El objetivo es **transformar una operación tradicional en un modelo de gestión basado en datos**, permitiendo decisiones comerciales y financieras más rápidas, confiables y eficientes.

---

## 🎯 2. Objetivos del Proyecto

- Crear una base de datos desde cero para simular la operación completa de una pyme.  
- Diseñar tablas y relaciones que permitan análisis financiero, comercial y operativo.  
- Desarrollar un proceso ETL reproducible y escalable.  
- Construir un dashboard profesional para toma de decisiones.  
- Analizar ventas, rentabilidad, stock y tendencias clave.  
- Identificar oportunidades de pricing, costos y eficiencia.

---

## 🧱 3. Arquitectura del Proyecto

-Excel (Raw Data)
-↓
-Python / SQL (ETL, Limpieza, Cálculo de KPIs)
-↓
-Modelado de Datos (Tablas Fact & Dim)
-↓
-Dashboard (Tableau / Power BI)

## 📂 4. Estructura del Repositorio
-📁 data/ → datasets originales y transformados
-📁 scripts/ → SQL y Python del proceso ETL
-📁 dashboards/ → imágenes y recursos del dashboard
-📁 notebooks/ → análisis exploratorio y cálculos
-📄 README.md → documentación del proyecto

## 📊 5. KPIs Principales

### **Financieros**
- Margen bruto por producto / marca / categoría  
- Margen neto (según estructura de costos)  
- ROI por producto  
- % Costos fijos vs variables  
- Pricing recomendado  

### **Comerciales**
- Ventas totales (unidades / facturación)  
- Top productos por rentabilidad  
- Ventas por categoría, marca y proveedor  
- Clientes y ticket promedio  

### **Operativos**
- Rotación de stock  
- Días de inventario  
- Oportunidades de reposición  
- Eficiencia por proveedor  

---

## 🧪 6. Metodología ETL

### **1. Extracción**
- Archivos Excel creados manualmente  
- Simulación de ventas, productos, stock y costos

### **2. Transformación**
- Limpieza, normalización y validación  
- Cálculo de márgenes, costos, impuestos y pricing  
- Unión de tablas fact y dim  

### **3. Carga**
- Exportación a SQL o carga directa en herramientas BI  
- Creación de relaciones y modelo estrella 

