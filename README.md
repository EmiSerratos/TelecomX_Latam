# 📊 TelecomX LATAM – Análisis de Churn

Aquí encontrarás un análisis completo sobre la **evasión de clientes (Churn)** en TelecomX LATAM, un reto clave para cualquier empresa de telecomunicaciones que busca **retener a sus clientes y construir relaciones de largo plazo**.

---

## 🎯 Objetivo

El propósito de este proyecto es **entender por qué los clientes se van y qué factores influyen en su decisión de cancelar el servicio**.
Con base en estos hallazgos, se proponen **estrategias de retención** que pueden marcar una diferencia real en la experiencia de los usuarios.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas y NumPy
- Matplotlib y Seaborn
- Jupyter / Google Colab

---

## 📂 Estructura del proyecto

- **TELECOMX.json** → Base de datos de clientes (fuente abierta de referencia):  
  https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json

- **TelecomX_LATAM_Challenge2.ipynb** → Notebook principal con el análisis paso a paso.

---

## 🔎 Análisis realizado

1. **Extracción de datos**  
   - Se cargó la información directamente desde el archivo JSON proporcionado.

2. **Manejo de inconsistencias**  
   - Se identificaron y corrigieron incoherencias en los datos para asegurar calidad en el análisis.

3. **Transformación de datos**  
   - Creación de la métrica **Cuentas_Diarias** a partir de la facturación mensual.  
   - Conversión de variables binarias: *Yes → 1, No → 0*.

4. **Carga y análisis exploratorio**  
   - Análisis descriptivo de variables clave (*tenure*, cargos mensuales, etc.).  
   - Distribución de evasión (Churn): proporción de clientes que permanecieron vs. los que cancelaron.  
   - Recuento y conteo de evasión: análisis de la cantidad de clientes en cada grupo.  
   - Visualizaciones para comparar la evasión según variables categóricas y numéricas.

5. **Informe**  
   - Resumen con introducción, limpieza de datos, hallazgos principales, conclusiones y recomendaciones estratégicas para la empresa.

---

## 💡 Conclusiones

- El churn afecta a aproximadamente **1 de cada 4 clientes (~26%)**.  
- El **tipo de contrato** es el factor más fuerte de permanencia.  
- **Método de pago** e **InternetService** también muestran patrones claros.  
- **Retener clientes en los primeros meses** puede reducir significativamente la evasión.

---

## 🚀 Recomendaciones estratégicas

- Incentivar a los clientes a cambiar de contratos mensuales a contratos más largos con **bonos o descuentos**.  
- Implementar un **programa de onboarding** y soporte reforzado para clientes nuevos.  
- Promover **métodos de pago automáticos** más confiables.  
- Diseñar campañas específicas para clientes con **Fiber optic**.  
- Crear un **programa de lealtad** que premie la antigüedad.

---

## ✨ Autor

Proyecto desarrollado por **Emilio Serratos**.
