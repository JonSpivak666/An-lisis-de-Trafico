# Análisis de Tráfico Vehicular en Los Ángeles

Este proyecto analiza los datos de colisiones de tráfico en la ciudad de Los Ángeles desde el año 2010 hasta la actualidad. Utiliza técnicas de análisis de datos y visualización para identificar patrones y tendencias en los accidentes de tráfico.

## Dataset

El dataset utilizado en este proyecto proviene de [Los Angeles Traffic Collision Data](https://www.kaggle.com/datasets/cityoflosangeles/los-angeles-traffic-collision-data). El dataset incluye información sobre colisiones de tráfico reportadas por el Departamento de Policía de Los Ángeles (LAPD).

### Contenido del Dataset

- **DR Number**: Número de registro del departamento.
- **Date Reported**: Fecha en la que se reportó el incidente.
- **Date Occurred**: Fecha en la que ocurrió el incidente.
- **Time Occurred**: Hora en la que ocurrió el incidente.
- **Area ID**: Identificador de la zona geográfica de LAPD.
- **Area Name**: Nombre de la zona geográfica de LAPD.
- **Reporting District**: Distrito de reporte.
- **Crime Code**: Código del crimen.
- **Crime Code Description**: Descripción del código del crimen.
- **Victim Age**: Edad de la víctima.
- **Victim Sex**: Sexo de la víctima.
- **Victim Descent**: Descendencia de la víctima.
- **Premise Code**: Código del lugar donde ocurrió el incidente.
- **Premise Description**: Descripción del lugar donde ocurrió el incidente.
- **Address**: Dirección del incidente.
- **Cross Street**: Calle transversal más cercana al incidente.
- **Location**: Ubicación (coordenadas XY) del incidente.

### Licencia

Este dataset está disponible bajo la [Creative Commons 1.0 Universal (CC0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `traffic-collision-data-from-2010-to-present.csv`: El archivo de datos original utilizado para el análisis.
- `Proyecto1_analisis_de_trafico.ipynb`: Notebook de Jupyter que contiene el análisis de datos, visualizaciones y modelo predictivo.
- `modelo_arbol_decision.pkl`: Archivo del modelo de Árbol de Decisión entrenado.
- `scatter_predicciones_arbol.png`: Gráfico de dispersión comparando predicciones y valores reales.

## Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio a tu máquina local:
   ```sh
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
