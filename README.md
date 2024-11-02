# Análisis Exploratorio de Datos del Dataset de Pingüinos

Este proyecto es un ejemplo de un Análisis Exploratorio de Datos (EDA) realizado sobre el dataset de pingüinos. Se basa en el trabajo realizado en [este proyecto](https://deepnote.com/app/mazzaroli/Analisis-exploratorio-de-datos-caba7762-e435-481e-9060-523263a820b1) y sirve como ejemplo de cómo usar Cookiecutter para estructurar un proyecto de ciencia de datos con información detallada.

## Descripción

El cuaderno de Jupyter incluido en este repositorio realiza un análisis exploratorio completo del dataset de pingüinos, que es una alternativa al famoso dataset de iris. El objetivo es identificar patrones y relaciones entre las variables para entender mejor las características de las diferentes especies de pingüinos.

Este proyecto también muestra cómo utilizar Cookiecutter para generar una estructura estándar de proyecto, facilitando la organización y escalabilidad del código y los datos.

## Contenido del Proyecto

- **notebooks/**: Contiene el cuaderno de Jupyter `1.0 EDA.ipynb` con el análisis exploratorio.
- **data/**: Directorio destinado a almacenar los datos brutos y procesados.
- **src/**: Código fuente utilizado para el procesamiento y análisis de datos.
- **requirements.txt**: Lista de dependencias y paquetes necesarios.
- **README.md**: Este archivo, que proporciona una descripción general del proyecto.

## Requisitos Previos

- Python 3.x
- Jupyter Notebook o JupyterLab
- Paquetes listados en `requirements.txt`

## Instalación

1. **Install cookiecutter**:

   ```bash
   pipx install cookiecutter-data-science # con pipx
    o
   pip install cookiecutter-data-science # con pip
   ```

1. **Usar el comando de cookiecutter y el repositorio**:

   ```bash
   ccds https://github.com/Andnog/Example-EDA-MDC-FCD
   ```

1. **Navegar al directorio del proyecto**:

   ```bash
   cd tu_proyecto
   ```

1. **Crear un entorno virtual y activarlo**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows usa 'venv\Scripts\activate'
   ```

1. **Instalar las dependencias**:

   ```bash
   pip install -r requirements.txt
   ```

Sigue las celdas del cuaderno para ver el proceso de análisis y visualización de datos.

## Dataset

El dataset de pingüinos proporciona información sobre tres especies diferentes: Adelie, Chinstrap y Gentoo. Incluye características como:

- Longitud y profundidad del pico
- Longitud de las aletas
- Masa corporal
- Sexo
- Isla de origen

## Estructura Generada con Cookiecutter

Este proyecto utiliza Cookiecutter para crear una estructura estándar, lo que facilita:

- **Organización**: Separación clara entre código, datos y documentación.
- **Escalabilidad**: Base sólida para ampliar el proyecto en el futuro.
- **Colaboración**: Facilita que otros contribuyan y entiendan la estructura del proyecto.

Para más información sobre Cookiecutter, visita la [documentación oficial](https://cookiecutter.readthedocs.io/en/latest/).

## Referencias

- Proyecto base: [Análisis exploratorio de datos](https://deepnote.com/app/mazzaroli/Analisis-exploratorio-de-datos-caba7762-e435-481e-9060-523263a820b1)
- Dataset de pingüinos: Disponible en la librería `seaborn` o en [palmerpenguins](https://github.com/allisonhorst/palmerpenguins)
- Cookiecutter Data Science: [Repositorio oficial](https://drivendata.github.io/cookiecutter-data-science/)

## Contribuciones

Este proyecto es un ejemplo educativo y no está abierto para contribuciones externas. Sin embargo, eres libre de utilizarlo como referencia o punto de partida para tus propios proyectos.

## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         project_name and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── project_name   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes project_name a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

