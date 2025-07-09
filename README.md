# Prueba técnica Bluetab

**Axl Emiliano López Rodríguez-Malpica**

Este repositorio contiene la solución de la prueba técnica proporcionada por Bluetab para la vacante de Data Scientist Jr.

## Objetivo 

Realizar dos metodologías para la predicción de una variable continua (PAY_AMT4) y una variable discreta (default payment next month), mediante el uso de técnicas de Machine Learning.

## Tecnologías Utilizadas

- Python
- TensorFlow / Keras
- NumPy
- scikit-learn
- matplotlib
- pandas

## Solución

- Archivo `assesment.iynb`: cuaderno de jupyter dividido en las siguientes secciones
    - EDA y Limpieza de Datos
    - Preparación de los datos (feature engineering)
    - Modelación
    - Conclusiones
    - Respuestas a preguntas acerca de la solución
    - Cuestionario general

## Estructura del Proyecto

```Directory structure:
└──Bluetab_assesment/
    ├── README.md
    ├── assesment.ipynb
    ├── default of credit card clients.csv
    ├── pyproject.toml 
    ├── uv.lock
    ├── .python-version       
    └── presentacion.pdf 
```
[Ver presentación en PDF](./presentacion.pdf)

## Pasos para ejecutar el proyecto

1. **Clonar el repositorio.**  
   Haz un fork y clónalo en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/axl2301-bluetab_assesment.git
   cd bluetab_assesment
    ```
2. **Configurar entorno virtual e instalar dependencias**
Asegúrate de tener Python instalado, luego corre:

```bash
uv venv
uv source/bin/activate
uv sync
```

3. **Correr cuaderno de jupyter**

Ya sea correr completo el cuaderno de jupyter o bloque por bloque.