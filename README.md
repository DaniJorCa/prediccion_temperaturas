# Predicción de Temperaturas

Este proyecto permite realizar predicciones de temperaturas utilizando datos históricos almacenados en un archivo Excel.

## Estructura del proyecto

- `pred_temperaturas.ipynb`: Notebook principal donde se desarrolla el análisis y la predicción.
- `dataset/temps.xlsx`: Archivo de datos históricos de temperaturas.

## Requisitos

- Python 3.11
- Paquetes recomendados: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `openpyxl`, `jupyter`

## Instalación

1. Clona este repositorio.
2. Crea y activa el entorno virtual:

   ```sh
   python -m venv env
   # En Windows:
   .\env\Scripts\activate
   # En Linux/Mac:
   source env/bin/activate
   ```

3. Instala las dependencias necesarias:

   ```sh
   pip install requirements.txt
   ```

## Uso

1. Asegúrate de que el archivo de datos `dataset/temps.xlsx` está presente.
2. Inicia Jupyter Notebook:

   ```sh
   jupyter notebook
   ```

3. Abre el archivo `pred_temperaturas.ipynb` y sigue las instrucciones dentro del notebook para ejecutar el análisis y la predicción.

## Notas

- Puedes modificar el archivo de datos en `dataset/temps.xlsx` para trabajar con tus propios datos.
- Las temperaturas se trabajan siendo 22.7 grados a 227.0

---