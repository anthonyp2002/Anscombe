# Universidad Politécnica Salesiana 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/FwzB5Nx/Ups.png" alt="Ups" border="center"></a>

### Carrera: Computacion
### Periodo: 65
### Estudiante: Anthony Damian Pulla Sanchez

---

## Cuarteto de Anscombe

El cuarteto de Anscombe es un conjunto de cuatro grupos de datos que, aunque tienen estadísticas similares (media, varianza, correlación y línea de regresión), muestran gráficas totalmente diferentes. Fue creado por el estadístico Francis Anscombe para hacernos ver que no basta con analizar números y promedios; es importante visualizar los datos para entender mejor lo que está pasando. Con este conjunto de datos, Anscombe nos recuerda que mirar solo las estadísticas puede llevarnos a interpretaciones equivocadas si no tomamos en cuenta cómo se distribuyen los datos al graficarlos.

---
## Contenido

1. **`data/`**
   - Contiene todos los conjuntos de datos que se utilizan para esta práctica.
   - Incluye tanto los datos de Anscombe como los del conjunto DataSaurus.

2. **`anscombe/`**
   - Contiene el código fuente del análisis en un archivo Jupyter Notebook (.ipynb) y su resultado en formato HTML.
   - El análisis incluye:
      - Carga del dataset de Anscombe.
      - Resúmenes estadísticos.
      - Gráficas individuales de cada conjunto de datos del cuarteto de Anscombe.
      - Gráficas de box-plot de cada grupo.
   - El código está debidamente documentado con celdas Markdown y comentarios para facilitar su comprensión.

3. **`DataSaurus/`**
   - Contiene un archivo `.Rmd` usado para explorar el conjunto de datos del DataSaurus, que incluye 13 conjuntos.
   - También incluye el archivo HTML generado a partir del `.Rmd` con el análisis del conjunto completo de DataSaurus.

4. **`ggplot2`**
   - Incluye el código de la herramienta utilizada para realizar la regresión lineal en uno de los datasets del conjunto DataSaurus.
   - Incluye el código que genera la gráfica de regresión lineal, de acuerdo con la selección que se hizo en clase.

---
