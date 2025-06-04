# Banco-Base
Este proyecto analiza los datos del sistema Ecobici de la Ciudad de México en los años 2023 y 2024. Se realizan análisis exploratorios, segmentación de estaciones mediante clustering y análisis de tendencias temporales con regresión lineal. El objetivo es obtener información accionable para apoyar decisiones operativas y de política pública.

---

## Estructura del proyecto

```
ecobici-analisis/
├── notebook .ipynb        # Notebook con código y análisis
├── ecobici_reporte.pdf           # Reporte visual con gráficas e interpretaciones
├── requirements.txt              # Lista de librerías necesarias
├── README.md                     # Este archivo
└── https://drive.google.com/drive/folders/1LOdnQfxSSGa1V6bEOOMEqLs3OsoTPAA0?usp=sharing  # Carpeta con los CSV de viajes de 2023 y 2024
```

---

## Contenido del análisis

- Análisis exploratorio general: género, edad, horarios, estaciones con más uso.
- Detección de valores atípicos en duración.
- Clustering con KMeans y DBSCAN para perfilar estaciones.
- Regresión lineal para detectar tendencias de crecimiento o caída en uso.
- Visualizaciones con interpretaciones.

---


Requiere las siguientes librerías:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---


##  Documentación

El notebook contiene:
- Comentarios en todo el código.
- Celdas Markdown con justificación de cada paso.
- Interpretaciones .

---

## Fuentes

- Datos descargados de: https://datos.cdmx.gob.mx/
