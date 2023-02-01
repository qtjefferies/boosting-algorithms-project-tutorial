<!-- hide -->
# Tutorial de Proyecto de Algoritmo de Impulso
<!-- endhide -->

- El sistema de compartición de bicicletas puede ser una red de sensores virtual que se puede usar para detectar la movilidad en una ciudad. Por lo tanto, se espera que la mayoría de los eventos importantes en la ciudad se puedan detectar a través del monitoreo de estos datos.

- En este proyecto, practica tus nuevas habilidades de algoritmo de aumento intentando predecir el número de alquileres de bicicletas en una ciudad específica.

## 🌱 Cómo comenzar este proyecto

Esta vez no harás un fork, por favor toma un tiempo para leer estas instrucciones:

1. Crea un nuevo repositorio basado en [proyecto de aprendizaje automático](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) haciendo [clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio recién creado en Gitpod usando la [extensión del botón Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que VSCode de Gitpod haya terminado de abrir, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de crear tu modelo, asegúrate de confirmar tus cambios, empujar a tu repositorio y dirigirte a 4Geeks.com para cargar el enlace del repositorio.

## 📝 Instrucciones

**Predicción de alquiler de bicicletas usando el Algoritmo de Boosting**

**Paso 1:**

El conjunto de datos se puede encontrar en esta carpeta del proyecto como el archivo 'bike_sharing_dataset.csv'. El conjunto de datos principal está relacionado con el registro histórico de dos años correspondiente a los años 2011 y 2012 del sistema Capital Bikeshare, Washington D.C., EE. UU., Que está disponible públicamente en http://capitalbikeshare.com/system-data. También puedes cargarlo directamente desde el siguiente enlace (`https://raw.githubusercontent.com/4GeeksAcademy/random-forest-project-tutorial/main/impressions.csv`), o descargarlo y agregarlo a tu carpeta de datos/raw. En ese caso, no olvides agregar la carpeta de datos al archivo .gitignore.

Puedes encontrar la descripción de cada característica en el archivo 'data-dictionary.md' de esta carpeta.

¡Es hora de trabajar en ello!

**Paso 2:**

Explora y limpia los datos.

**Paso 3:**

Construye un primer modelo de línea base usando Regresión Lineal. Elige una métrica de evaluación. Luego, usa un algoritmo de boosting y evalúa el rendimiento de ambos modelos.

**Paso 4:**

Usa app.py para crear tu tubería.

**Paso 5:**

Para guardar tu modelo y poder usarlo más tarde, usa el siguiente código:
py

```py

import pickle

filename = 'finalized_model.sav'
pickle.dump(model, open(filename, 'wb'))
```

En tu archivo README escribe un breve resumen.
