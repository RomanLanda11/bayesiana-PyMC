# Inferencia bayesiana

Material didáctico en Jupyter Notebook para introducir la inferencia bayesiana y practicar la actualización de distribuciones a partir de datos.

## Contenido

- [`notebooks/01_inferencia_bayesiana.ipynb`](notebooks/01_inferencia_bayesiana.ipynb): regla de Bayes, modelos bayesianos y ejercicios sobre agua en la Tierra, tiros en la NBA y una enfermedad rara.

## Requisitos

Python 3 y Jupyter. El notebook utiliza NumPy, Matplotlib, SciPy y PreliZ.

En Windows, desde la carpeta del proyecto, puedes instalar las dependencias y abrir Jupyter con:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install jupyter numpy matplotlib scipy preliz arviz_base
jupyter lab
```

En Google Colab, abre el notebook desde GitHub; la primera celda instala PreliZ y ArviZ Base si hacen falta.
