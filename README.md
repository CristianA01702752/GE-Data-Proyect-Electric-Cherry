# Electric-Cherry
## ⚡ Integrantes del equipo
* Cristian Rogelio Espinoza Diaz - A01702752
* Flavio Ruvalcaba Leija - A01367631
* Anatanael Jesus Miranda Faustino - A01769232

## 📋 Resumen
Este repositorio alberga la documentación y los scripts de código generados por nuestro equipo para la configuración y gestión del proyecto en el contexto de la asignatura de 'Inteligencia Artificial Avanzada para la Ciencia de Datos II' (Grupo 501).

Nuestro proyecto tiene como objetivo la generación de un modelo para identificación del modo conocido como "Stable Cruise" mediante el uso de diversas herramientas tecnológicas, como Python, y metodologías como CRISP-DM (Cross-Industry Standard Process for Data Mining).

## 📘 Contenido del repositorio
Al momento de redacción de esta versión del readme (3 de noviembre de 2023), el contenido se encuentra ubicado en la rama 'develop', siguiendo el método de trabajo establecido por el equipo.

Dentro de esta rama, encontrarás carpetas organizadas según las fases de la metodología CRISP-DM, que son las siguientes:
* Business Understanding
* Data Understanding
* Data Preparation
* Modeling
* Evaluation
* Deployment

Cada fase tendrá sus respectivas carpetas de 'scripts' y 'documentos'. En la carpeta de 'scripts', se encuentran los códigos ejecutados para el desarrollo de la fase correspondiente en formato .ipynb.

La carpeta 'documentos' albergará documentación o proporcionará un enlace para dirigirte a la unidad de Drive del equipo donde se encuentra almacenada la documentación, ya que la documentación de algunas fases aún está en proceso. Algunas fases todavía están en desarrollo, por lo que la documentación puede estar incompleta.

Finalmente, debido a la estructura de la unidad de formación, el equipo ha generado documentación que no se puede clasificar en ninguna de las fases de CRISP-DM. Por lo tanto, se creó una carpeta adicional denominada como 'Documentación adicional'.

## 🕹️ Uso
Para hacer uso de los scripts, realice los siguientes pasos:
1.- Clonar este repositorio en tu ambiente local:
   ```bash
   git clone https://github.com/CristianA01702752/Electric-Cherry.git
   ```
2.- Modificar los scripts con el propósito de adaptarlos al entorno donde se planea ejecutarlo. Por ejemplo, las rutas usadas para el almacenamiento del dataset.
3.- Ejecutar el o los scripts mediante el botón de "Run All" en la parte superior de visual studio code. En caso de no estar usando visual studio, se puede usar el siguiente comando en jupyter notebook para la ejecución:
   ```bash
   jupyter nbconvert --execute --to notebook --inplace nombre_del_archivo.ipynb
   ```
Asegúrate de reemplazar nombre_del_archivo.ipynb con el nombre de script que quieras ejecutar. Este comando ejecutará todas las celdas en el notebook y guardará los resultados en el mismo archivo.

Ten en cuenta que necesitarás tener Jupyter Notebook y nbconvert instalados en el entorno de eecución para usar este comando. Además, es importante recordar que, al ejecutar todas las celdas de un notebook, los resultados pueden variar según las dependencias y el entorno en el que se ejecute.

## 🎯 Dependencias
Librerías utilizadas de los scripts:

* Pyhton 3.9.7
* Dask
* Pandas
* Scikit-Learn
* Seaborn
* Matplotlib
* Numpy
* Joblib
* Statsmodels
* SciPy
* Imbalanced-Learn
* XGBoost
* Tensorflow
