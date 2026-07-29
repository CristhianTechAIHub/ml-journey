# ml-journey

> Mi viaje de aprendizaje en Machine Learning e Inteligencia Artificial — de ML clásico a agentes LLM e IoT.

---

## Español

### Descripción

Este repositorio documenta mi proceso de aprendizaje en Ciencia de Datos, Machine Learning e Inteligencia Artificial. Contiene notebooks de práctica organizados por lección, datasets de apoyo y proyectos aplicados, con el objetivo de construir una base sólida que luego se extienda hacia temas más avanzados como agentes basados en LLM y aplicaciones de IA en IoT.

### Estructura de carpetas

```
ml-journey/
├── leccion-01/     # Fundamentos: NumPy y Pandas
├── leccion-02/     # Visualización de datos: Matplotlib y Seaborn
├── datasets/       # Datasets usados en los notebooks (los pesados no se versionan, ver .gitignore)
├── proyectos/      # Proyectos aplicados que integran varias lecciones
└── README.md       # Este archivo
```

### Tecnologías usadas

- **Python 3**
- **NumPy** — cómputo numérico vectorizado
- **Pandas** — manipulación y análisis de datos
- **Matplotlib** / **Seaborn** — visualización de datos
- **scikit-learn** — modelos de Machine Learning clásico
- **JupyterLab** — entorno de notebooks
- **Miniconda** — gestión de entornos y dependencias

### Cómo clonar y configurar el entorno

```bash
# Clonar el repositorio
git clone https://github.com/<tu-usuario>/ml-journey.git
cd ml-journey

# Crear el entorno de Miniconda
conda create -n ml-journey python=3.11 -y
conda activate ml-journey

# Instalar dependencias
pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab ipykernel

# Registrar el entorno como kernel de Jupyter
python -m ipykernel install --user --name ml-journey --display-name "Python (ml-journey)"

# Abrir JupyterLab
jupyter lab
```

### Progreso de lecciones

| # | Lección | Tema | Estado |
|---|---------|------|:------:|
| 1 | [leccion-01](leccion-01/) | NumPy y Pandas — fundamentos | ✅ |
| 2 | [leccion-02](leccion-02/) | Visualización de datos con Matplotlib y Seaborn | ✅ |

---

## English

### Description

This repository documents my learning process in Data Science, Machine Learning, and Artificial Intelligence. It contains practice notebooks organized by lesson, supporting datasets, and applied projects, with the goal of building a solid foundation that later extends into more advanced topics such as LLM-based agents and AI applications in IoT.

### Folder structure

```
ml-journey/
├── leccion-01/     # Fundamentals: NumPy and Pandas
├── leccion-02/     # Data visualization: Matplotlib and Seaborn
├── datasets/       # Datasets used in the notebooks (heavy files are not versioned, see .gitignore)
├── proyectos/      # Applied projects integrating multiple lessons
└── README.md       # This file
```

### Technologies used

- **Python 3**
- **NumPy** — vectorized numerical computing
- **Pandas** — data manipulation and analysis
- **Matplotlib** / **Seaborn** — data visualization
- **scikit-learn** — classical Machine Learning models
- **JupyterLab** — notebook environment
- **Miniconda** — environment and dependency management

### How to clone and set up the environment

```bash
# Clone the repository
git clone https://github.com/<your-username>/ml-journey.git
cd ml-journey

# Create the Miniconda environment
conda create -n ml-journey python=3.11 -y
conda activate ml-journey

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab ipykernel

# Register the environment as a Jupyter kernel
python -m ipykernel install --user --name ml-journey --display-name "Python (ml-journey)"

# Launch JupyterLab
jupyter lab
```

### Lesson progress

| # | Lesson | Topic | Status |
|---|--------|-------|:------:|
| 1 | [leccion-01](leccion-01/) | NumPy and Pandas — fundamentals | ✅ |
| 2 | [leccion-02](leccion-02/) | Data visualization with Matplotlib and Seaborn | ✅ |
