# 🐍 neoApp - Módulo de Análisis de Datos

## Juan Jose Gallego Mesa 
## Laura Perez Muñoz
## Brayan Vegetta Gallego (grupo de vierenes 6 am)
## Bulma Sofia Gallego

## 📊 Descripción

**neoApp** es una solución educativa enfocada en la **gestión y control de gastos hormiga** 💸, integrando tecnologías modernas como:

- 🐍 Python (análisis de datos)
- ⚛️ React (frontend)
- ☕ Spring Boot (backend)

Este repositorio contiene el módulo de **análisis de datos en Python**, encargado de procesar, limpiar y analizar la información financiera del usuario para generar insights útiles que faciliten la toma de decisiones.

El objetivo es ayudar a las personas a **identificar patrones de gasto pequeños pero frecuentes** que impactan significativamente sus finanzas personales.

---

## 🚀 Funcionalidades principales

- 📥 Carga y procesamiento de datos de gastos
- 🧹 Limpieza y transformación de datos
- 📈 Análisis exploratorio (EDA)
- 🔍 Identificación de gastos hormiga
- 📊 Generación de métricas e indicadores clave
- 🧠 Base para futuros modelos predictivos

---

## 🛠️ Tecnologías utilizadas

- 🐍 Python 3.x
- 📊 Pandas
- 🔢 NumPy (opcional)
- 📉 Matplotlib / Seaborn (opcional para visualización)

---

## ⚙️ Instalación

Sigue estos pasos para configurar el entorno:

```bash
# 1️⃣ Clonar el repositorio
git clone https://github.com/tu-usuario/neoApp-python.git

# 2️⃣ Entrar al directorio
cd neoApp-python

# 3️⃣ Crear entorno virtual (opcional pero recomendado)
python -m venv venv

# 4️⃣ Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En Mac/Linux:
source venv/bin/activate

# 5️⃣ Instalar dependencias
pip install pandas
```

---

## 📦 Uso básico de Pandas

Algunos comandos clave que se utilizan en este proyecto:

```python
import pandas as pd

# 📥 Cargar datos
df = pd.read_csv("gastos.csv")

# 👀 Ver primeras filas
df.head()

# 📊 Resumen estadístico
df.describe()

# 🧹 Limpieza de datos
df.dropna(inplace=True)

# 🔍 Filtrar gastos hormiga (ejemplo)
gastos_hormiga = df[df["monto"] < 10]

# 📈 Agrupar por categoría
df.groupby("categoria")["monto"].sum()
```

---

## 📁 Estructura del proyecto

```
neoApp-python/
│
├── data/              # 📂 Datos crudos y procesados
├── notebooks/        # 📓 Análisis exploratorio
├── src/              # 🧠 Lógica del análisis
├── reports/          # 📊 Resultados y visualizaciones
└── README.md         # 📄 Documentación
```

---

## 🎯 Objetivo educativo

Este proyecto está diseñado para:

- 👨‍💻 Aprender análisis de datos con Python
- 🔗 Integrar múltiples tecnologías (full stack)
- 💡 Resolver problemas reales de finanzas personales
- 📚 Aplicar buenas prácticas de desarrollo

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! 🚀  
Puedes mejorar análisis, agregar visualizaciones o proponer nuevas funcionalidades.

---

## 📌 Futuras mejoras

- 🤖 Modelos de predicción de gastos
- 📊 Dashboards interactivos
- 🔗 Integración con API backend (Spring Boot)
- ⚛️ Conexión en tiempo real con frontend
