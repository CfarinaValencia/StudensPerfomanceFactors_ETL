# 📊 Análisis del Rendimiento Estudiantil - EDA & Transformaciones

Este repositorio contiene un análisis exploratorio de datos (EDA) y una transformación detallada del conjunto de datos de rendimiento estudiantil.
El objetivo es identificar factores clave que influyen en el desempeño académico mediante análisis estadísticos y aprendizaje automático.

---

## 📌 Objetivos del Análisis
✔️ **Identificar factores que más afectan el rendimiento académico.**  
✔️ **Explorar la relación entre horas de estudio y calificaciones.**  
✔️ **Analizar cómo el nivel socioeconómico y el acceso a recursos impactan el aprendizaje.**  
✔️ **Evaluar si la motivación y la participación extracurricular afectan los puntajes.**  
✔️ **Desarrollar modelos de predicción del rendimiento académico.**  

---

## 🔧 Herramientas Utilizadas
- **Python**
  - `pandas` (para manipulación de datos)
  - `matplotlib` y `seaborn` (para visualización de datos)
  - `scikit-learn` (para normalización y modelado)
- **Jupyter Notebook / VS Code**
- **GitHub** (para control de versiones)

---

## 🚀 Cómo Usar Este Proyecto

### **1️⃣ Clonar el Repositorio**
```bash
git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>
```

### **2️⃣ Descargar el Dataset**
Descarga el archivo `student_performance_large_dataset.csv` desde [Kaggle](https://www.kaggle.com/datasets/adilshamim8/student-performance-and-learning-style/data)  
Colócalo en la carpeta del proyecto.

### **3️⃣ Crear un Entorno Virtual (Opcional pero Recomendado)**
```bash
python -m venv venv  # Crear entorno virtual
source venv/bin/activate  # Para Linux/macOS
venv\Scripts\activate  # Para Windows
```

### **4️⃣ Instalar Dependencias**
```bash
pip install -r requirements.txt
```

### **5️⃣ Ejecutar el Análisis Exploratorio de Datos (EDA)**
Para ejecutar el análisis de datos y visualizar estadísticas y gráficos:

```bash
jupyter notebook
```

Abre el archivo `Fase1.ipynb` en Jupyter Notebook y ejecuta las celdas paso a paso.

### **6️⃣ Aplicar Transformaciones de Datos**
Para ejecutar las transformaciones de datos y generar un archivo limpio, ejecuta:

```bash
python data_transformation.py
```

Esto generará un archivo llamado **student_performance_transformed.csv** con los datos procesados.

---

## 📊 Contenido del Proyecto

📁 `Fase1.ipynb` - Contiene el análisis exploratorio de datos (EDA).  
📁 `requirements.txt` - Lista de dependencias necesarias.  
📁 `student_performance_large_dataset.csv` - Dataset original utilizado en el análisis.  

---


💡 ¡Tu ayuda es bienvenida para mejorar el análisis y la interpretación de los datos! 🚀
