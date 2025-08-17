# Challenge TelecomX
## 🚀 Visión General
Este proyecto aborda el **análisis de churn (abandono de clientes)** en **Telecom X**, una empresa ficticia del sector de las telecomunicaciones en América Latina.  

El objetivo fue **recopilar, limpiar y analizar los datos de clientes** para descubrir los principales factores que explican la cancelación de servicios y, a partir de ellos, **proponer estrategias de retención más efectivas**.  

Este análisis exploratorio de datos (EDA) constituye la base para futuros **modelos predictivos de churn** y el diseño de **programas de fidelización**.  

---

## 🎯 Objetivos del Proyecto
- Identificar **patrones y tendencias** en clientes que abandonan.  
- Determinar las **variables clave** que influyen en el churn (demográficas, servicios contratados, contratos y métodos de pago).  
- Generar **insights accionables** para el equipo de Data Science y la gerencia, respondiendo:  
  - *¿Por qué se van los clientes?*  
  - *¿Qué podemos hacer para retenerlos?*  

---

## 📂 Estructura del Repositorio
- **README.md** → Resumen ejecutivo del proyecto.  
- **Challenge Telecom X – Análisis de evasión de clientes.ipynb** → Notebook con el código, análisis, visualizaciones e informe final.  
- **df_final.csv** → DataFrame consolidado tras la limpieza y transformación de datos.  

---

## 🛠️ Herramientas y Librerías
El análisis se desarrolló en **Python** utilizando:  

- **pandas** → Limpieza y manipulación de datos.  
- **numpy** → Operaciones numéricas.  
- **matplotlib** → Gráficos y visualizaciones básicas.  
- **seaborn** → Visualizaciones estadísticas y análisis exploratorio.  

---

## 🔑 Principales Etapas del Análisis
1. **Carga y Preparación de Datos**  
   - Importación desde JSON.  
   - Normalización de estructuras anidadas.  

2. **Limpieza y Transformación**  
   - Manejo de valores nulos/vacíos.  
   - Conversión de variables categóricas (*Yes/No → 1/0*).  
   - Creación de nuevas variables (ej. *Cuentas_Diarias*).  

3. **Análisis Exploratorio (EDA)**  
   - Cálculo de la **tasa general de churn (26,5%)**.  
   - Evaluación de churn por variables categóricas (**contrato, método de pago, género**).  
   - Análisis de variables numéricas (**antigüedad, cargos mensuales, cargos totales**).  
   - Visualizaciones con histogramas, boxplots y correlaciones.  

---

## 📌 Insights Clave
- Los clientes con **contratos Mes a Mes** son los más propensos a cancelar.  
- La **antigüedad baja (0–6 meses)** es un predictor fuerte de abandono.  
- El método de pago **Cheque Electrónico** está altamente correlacionado con churn.  
- **Cargos mensuales elevados** aumentan el riesgo de fuga.  
- Existe un **“punto dulce”** en la cantidad de servicios contratados (3–6).  

---

## ✅ Próximos Pasos
- Desarrollar un **modelo predictivo de churn** (Machine Learning).  
- Implementar un **sistema de alertas tempranas** para clientes en riesgo.  
- Evaluar el impacto de estrategias de **retención y fidelización** (ej. contratos largos, programas de onboarding, migración a pagos automáticos).  
