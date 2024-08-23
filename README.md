
# Sistema de Recomendación de Cursos de Udemy

Este proyecto consiste en la construcción de un sistema de recomendación utilizando datos de un conjunto de cursos de Udemy. El cuaderno realiza un análisis exploratorio de datos, un análisis predictivo y finalmente construye un sistema de recomendación basado en los títulos de los cursos.

## Contenido

El cuaderno se estructura en las siguientes secciones:

### 1. Análisis Exploratorio de Datos

- **1.1 Descripción del Dataset:**  
  En esta sección se carga y describe el dataset `udemy_courses.xls` para entender la estructura de los datos.
  
- **1.2 Limpieza de Valores Nulos y/o Duplicados:**  
  Se realiza la limpieza de datos, eliminando o tratando valores nulos y duplicados para asegurar la calidad del análisis posterior.
  
- **1.3 Análisis de Variables Categóricas:**  
  Se exploran y visualizan las variables categóricas para entender su distribución y posibles patrones.
  
- **1.4 Análisis de Variables Numéricas:**  
  Se realiza un análisis de las variables numéricas para identificar tendencias, rangos y distribuciones.

### 2. Análisis Predictivo

- **2.1 Análisis de Precios:**  
  Esta sección está enfocada en analizar y predecir los precios de los cursos utilizando técnicas estadísticas y modelos de machine learning.

### 3. Análisis y Recomendación

- **Sistema de Recomendación Basado en el Título:**  
  Se desarrolla un sistema de recomendación que sugiere cursos basados en la similitud de los títulos de los cursos.
  
- **3.1 Preparación de Datos:**  
  Se preparan los datos para el sistema de recomendación, incluyendo la tokenización, limpieza y vectorización de textos.

- **3.2 Función:**  
  Se define la función general que se utiliza para el sistema y que hará de base para posibles variantes.

- **3.3 Pruebas y añadidos:**  
  Se ajusta la función del recomendador según otras variables, incluyendo el uso de 3 atributos, alterando el peso de los atributos, filtrado por distintos criterios, etc. 


### 4. Extras

- **4.1 Nube de palabras:**  
  Una nube de palabras es una visualización que muestra las palabras más frecuentes en un texto o conjunto de textos. Puede utilizarse como criterio extra de mejora de la función, tanto por la inclusion como por la exclusion de estas palabras en el sistema recomendador.

- **4.2 Ruta de aprendizaje:**  
  El recomendador Pro, donde se ofrece un plan de distintos cursos sobre la misma temática que de forma organizada y estructurada completarán la formación adquirida.

  ### 5. Futuros pasos: DAFO

  Se ha realizado un análisis DAFO (Debilidades, Amenazas, Fortalezas, Oportunidades) para evaluar la utilidad actual y los posibles futuros pasos de nuestro sistema de recomendación.




## Librerías Utilizadas

Este proyecto utiliza varias librerías de Python, entre ellas:

- `IPython`: Utilizada para la interacción avanzada en las celdas de Jupyter.
- `matplotlib`: Para la visualización de datos.
- `nltk`: Usada para el procesamiento de lenguaje natural.
- `numpy`: Para cálculos numéricos.
- `pandas`: Para manipulación y análisis de datos.
- `pylab`: Para visualización, parte de Matplotlib.
- `seaborn`: Para visualizaciones estadísticas.
- `sklearn`: Para algoritmos de machine learning.
- `tkinter`: Para interfaces gráficas de usuario.
- `wordcloud`: Para generar nubes de palabras.

## Instrucciones para Ejecutar

1. **Instalar Dependencias**: Asegúrate de tener instaladas todas las librerías necesarias. Puedes hacerlo utilizando `pip`:

   ```bash
   pip install numpy pandas matplotlib seaborn sklearn nltk wordcloud
   ```

2. **Cargar el Cuaderno**: Abre el cuaderno en Jupyter Notebook o JupyterLab.

3. **Ejecutar Secciones**: Ejecuta las celdas en el orden presentado para reproducir el análisis y el sistema de recomendación.

## Consideraciones

Este cuaderno está diseñado para trabajar con un dataset específico (`udemy_courses.xls`). Si deseas aplicar este análisis a otro dataset, asegúrate de ajustar el código y la limpieza de datos según corresponda.


## Agradecimientos

Quiero expresar mi sincero agradecimiento a Ironhack por su excepcional formación y por brindarme la oportunidad de aprender y desarrollar mis habilidades para la Ciencia de Datos. La experiencia y los conocimientos adquiridos en el programa han sido fundamentales para llevar a cabo este proyecto. 

También me gustaría dar las gracias a Udemy por su API de afiliado y sus datasets, que han sido esenciales para el desarrollo de este sistema de recomendación de cursos.

Gracias a todos los que han apoyado y contribuido a este proyecto.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más detalles.


