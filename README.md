# 📊 ConnectaTel | Análisis de Clientes y Comportamiento

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-yellow?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualización-green?style=for-the-badge)
![Estado](https://img.shields.io/badge/Proyecto-Completo-brightgreen?style=for-the-badge)

---

## 🚀 Descripción del proyecto

Este proyecto realiza un **análisis completo de comportamiento de clientes** para la empresa  ConnectaTel, con el objetivo de entender patrones de uso, limpiar datos reales y generar **insights accionables para la empresa**.

---

## 🎯 Objetivo

- Limpiar y preparar datos de telecomunicaciones  
- Detectar valores nulos, sentinels y outliers  
- Analizar el comportamiento de usuarios  
- Segmentación de clientes por edad y nivel de uso  
- Generar recomendaciones estratégicas basadas en datos  

---

## 📁 Datasets utilizados

- **users.csv** → Información demográfica de clientes  
- **usage.csv** → Registro de llamadas y mensajes  
- **plans.csv** → Información de planes y servicios  

---

## 🧹 Limpieza de datos

Durante el proceso se realizaron las siguientes acciones:

- Reemplazo de valores sentinels como **-999 en age**  
- Conversión de valores inválidos (`?`) en `city` a nulos  
- Corrección de formatos de fecha con `pd.to_datetime()`  
- Identificación de valores nulos estructurales en `usage`  
- Validación de tipos de datos  

---

## 📊 Análisis exploratorio (EDA)

- Uso de `.head()`, `.info()` y `.describe()`  
- Análisis de valores nulos y su proporción  
- Distribución de variables categóricas (`plan`, `city`)  
- Detección de inconsistencias en los datos  

---

## 📈 Visualización de datos

- Histogramas de edad y uso de servicios  
- Distribución de llamadas, mensajes y minutos  
- Boxplots para detección de outliers  
- Comparación entre planes de usuarios  

---

## 👥 Segmentación de clientes

### 🔹 Segmentación por uso
- **Bajo uso** → poca actividad en llamadas y mensajes  
- **Uso medio** → actividad moderada  
- **Alto uso** → usuarios intensivos (power users)  

### 🔹 Segmentación por edad
- **Jóvenes (<30)** → menor consumo de servicios  
- **Adultos (30–60)** → mayor actividad general  
- **Adultos mayores (>60)** → menor uso promedio  

---

## 📌 Insights principales

- Los datos presentan distribución sesgada hacia la derecha en variables de uso  
- Los outliers representan usuarios intensivos, no errores  
- Existe una segmentación clara por nivel de consumo  
- La edad no determina completamente el nivel de uso  
- Un pequeño grupo de usuarios genera la mayor actividad  

---

## 📊 Estructura final del dataset




---

## 💡 Recomendaciones de negocio

- Crear planes premium para usuarios de alto consumo  
- Ofrecer planes económicos para usuarios de bajo uso  
- Implementar estrategias de migración de planes (upselling)  
- Segmentación de marketing por edad y comportamiento  
- Personalización de ofertas según uso real  

---


📌 Conclusión

Este proyecto convierte datos crudos de telecomunicaciones en información estructurada y accionable, permitiendo identificar segmentos clave de clientes y oportunidades de mejora en productos y estrategias comerciales.

