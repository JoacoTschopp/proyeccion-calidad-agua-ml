# Proyección de la calidad del agua mediante machine learning

Predicción y monitoreo de la calidad del agua mediante modelos de machine learning aplicados a datos ambientales temporales.

---

## 📁 Estructura del repositorio

```
proyeccion-calidad-agua-ml/
├── manuscript/                  # Manuscrito en LaTeX
├── data/
│   ├── final.csv                # Dataset final para modelado
│   └── eda_interpolado.csv      # Dataset con interpolación y análisis exploratorio
├── notebooks/
│   ├── 01_interpolacion_series_temporales.ipynb
│   └── 02_generacion_train_test_walkforward.ipynb
├── requirements.txt             # Entorno Python
└── README.md
```

---

## 📓 Notebooks

### 01 - Interpolación de series temporales

Este notebook contiene el proceso de interpolación de variables ambientales a partir de datos con fechas irregulares. Se aplican técnicas como `CubicSpline` y visualizaciones para validar la consistencia temporal de los datos interpolados.

### 02 - Generación de conjuntos train/test (walk-forward)

Este notebook implementa una división de datos tipo walk-forward, para respetar la naturaleza temporal de las series. Se construyen conjuntos de entrenamiento y validación en bloques sucesivos y se aplican transformaciones como codificación y escalado.

---

## 🛠 Requisitos

Instalar los paquetes necesarios con:

```bash
pip install -r requirements.txt
```

---

## 📜 Licencia

Este proyecto se distribuye bajo la [Licencia Apache 2.0](LICENSE).

---

## 📬 Contacto

Para más información, podés contactarte con el autor del proyecto a través de este repositorio.

```
