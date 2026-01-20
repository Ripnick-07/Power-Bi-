# Análisis de Ventas y Forecast – Power BI

## 📌 Descripción del proyecto
Dashboard de ventas desarrollado en Power BI a partir de datos ficticios que simulan un entorno comercial real. El objetivo es analizar el desempeño de ventas, el cumplimiento del presupuesto y la evolución temporal para apoyar la toma de decisiones.

---

## 🛠 Herramientas utilizadas
- Power BI Desktop
- DAX
- Modelado de datos
- Tabla calendario

---
## 🧩 Modelo de datos

El modelo fue diseñado bajo un esquema tipo estrella, separando claramente las tablas de hechos y dimensiones:

- Tabla de hechos: Ventas
- Tablas de dimensión: Clientes, Productos y Calendario
- Se implementó una tabla calendario independiente para asegurar un análisis temporal correcto, permitiendo comparaciones mensuales, cálculo de crecimiento y correcta ordenación de fechas.
---
## 📊 KPIs principales
- Ventas Totales
- Presupuesto Total
- Variación $
- Cumplimiento %
- Crecimiento Mensual %
---

## 🎯 Decisiones de diseño

- Se priorizaron KPIs de alto impacto (Ventas Totales, Cumplimiento %, Variación $) para facilitar una lectura rápida del desempeño general.
- El dashboard fue estructurado para responder primero a una visión ejecutiva y luego permitir el análisis detallado mediante segmentadores.
- Se evitó el uso excesivo de visualizaciones para mantener claridad y foco en la toma de decisiones.

---

## 🧠 Insights obtenidos
- El desempeño global presenta un cumplimiento superior al 100%, indicando un sobrecumplimiento del presupuesto.
- Se observa una tendencia decreciente en las ventas a lo largo del período, lo que sugiere la necesidad de acciones comerciales correctivas.
- El análisis por vendedor permite identificar diferencias claras en el aporte a las ventas totales.
- El uso de segmentadores facilita el análisis por región, año y vendedor.

---

## ❓ Preguntas de negocio abordadas

- ¿Se está cumpliendo el presupuesto anual de ventas?
- ¿Cómo evoluciona el desempeño de ventas a lo largo del año?
- ¿Qué vendedores aportan mayor volumen de ventas?
- ¿Existen meses con caídas relevantes que requieran acciones comerciales?

---
## 🏢 Uso en un entorno real

Este dashboard podría ser utilizado por áreas comerciales y de control de gestión para:

- Monitorear el desempeño mensual de ventas
- Detectar desviaciones respecto al presupuesto
- Evaluar el rendimiento por vendedor
- Apoyar reuniones de seguimiento y toma de decisiones comerciales

---
## 🚀 Próximos pasos
- Incorporar forecast avanzado
- Automatizar la actualización de datos
- Integrar nuevas dimensiones de análisis
