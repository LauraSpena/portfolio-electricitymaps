# Consumo eléctrico en Argentina (2021–2024)

Este proyecto analiza y visualiza datos de consumo eléctrico en Argentina utilizando como fuente principal el dataset abierto de **ElectricityMaps**.  
El objetivo es construir un pipeline automatizado (n8n/Python) y un dashboard interactivo (Tableau/Google Sheets) que permitan entender patrones de consumo en distintas escalas temporales (horaria, diaria, mensual).  

---

## 📊 Objetivos
- Descargar y procesar datos horarios, diarios y mensuales de consumo eléctrico.  
- Construir un **pipeline automatizado** para actualizar los datos periódicamente.  
- Diseñar un **dashboard interactivo** que muestre tendencias de consumo.  
- Agregar contexto ESG (participación de renovables, intensidad de carbono).  

---

## 📂 Estructura del repositorio
data/ # Datasets crudos y procesados
notebooks/ # Exploraciones y análisis iniciales
pipeline/ # Workflows en n8n o scripts en Python
dashboard/ # Capturas y enlaces a dashboards
docs/ # Documentación extendida


---

## 📑 Dataset principal
- **Fuente:** [ElectricityMaps – Argentina](https://app.electricitymaps.com)  
- **Cobertura temporal:** 2021–2024  
- **Frecuencia:** horaria, diaria y mensual  
- **Formato:** CSV
- **Licence:** Open Database License (ODbL) 

---

## 🚀 Próximos pasos
1. Configurar pipeline en n8n para descarga y limpieza automática.  
2. Diseñar dashboard inicial con visualización horaria y mensual.  
3. Incorporar datos de renovables y emisiones para enriquecer el análisis.  
4. Documentar hallazgos e insights en el repositorio.  

---

## 📊 Resultados iniciales

Este repositorio ya incluye un primer análisis basado en los datos **YEARLY** de ElectricityMaps (2021–2023).  

### 🔗 Archivos principales
- [Notebook exploratorio (2021–2023)](notebooks/electricitymaps-argentina-exploraci-n-inicial.ipynb)  
- [Dataset procesado anual (2021–2023)](electricitymaps_yearly_summary_2021_2023.csv)  

### 📑 Hallazgos preliminares
- El porcentaje de **energías renovables** subió de **27% (2021)** a **43% (2023)**.  
- La energía **libre de carbono (CFE%)** pasó de **34% a casi 50%** en el mismo período.  
- La **intensidad de carbono** mostró un pico en 2022 (~325 gCO₂eq/kWh) antes de bajar en 2023 (~293 gCO₂eq/kWh).  

👉 Próximo paso: incorporar datos **horarios o diarios** para analizar estacionalidad mensual y patrones intra-anuales.



