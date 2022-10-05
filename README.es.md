<!-- hide -->
# Random Forest Project Tutorial
<!-- endhide -->

- Hasta ahora, solo hemos utilizado el conjunto de datos del Titanic como referencia en nuestro proceso de aprendizaje. Ha sido nuestra guía en la parte de análisis exploratorio de datos, preprocesamiento de datos y un referente en nuestro primer modelo: la regresión logística. En el proyecto actual y en el próximo, Titanic será el dato principal de nuestro proyecto.

- Si has estado practicando con Titanic hasta ahora, es posible que tengas algunos datos limpios listos para modelar. De lo contrario, te recomendamos que comiences a hacer un poco de eda y limpieza en el conjunto de datos del Titanic para tenerlo listo para los próximos dos modelos.

- En este proyecto, practica tus nuevas habilidades de Random Forest para intentar hacer una predicción precisa de la supervivencia del Titanic. Luego, como siempre, optimiza sus hiperparámetros.

- Si ya tiene un notebook para Titanic en tu repositorio de Github, no dudes en usarlo para este proyecto. Continúa tu notebook con una nueva pieza de modelado, ¡esta vez usando Random Forest! Si aún no ha creado un repositorio para Titanic, sigue las instrucciones sobre cómo iniciar este proyecto.

# 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones

**Predecir la supervivencia del Titanic usando Random Forest**

Necesitamos construir un modelo predictivo que responda a la pregunta: "¿qué tipo de personas tenían más probabilidades de sobrevivir?" utilizando datos de pasajeros (es decir, nombre, edad, sexo, clase socioeconómica, etc.). Para poder predecir qué pasajeros tenían más probabilidades de sobrevivir, utilizaremos Random Forest para entrenar el modelo.

**Paso 1:**

El conjunto de datos se puede encontrar en esta carpeta de proyecto como archivo 'titanic_train.csv'. Te invitamos a cargarlo directamente desde el enlace (`https://raw.githubusercontent.com/4GeeksAcademy/random-forest-project-tutorial/main/titanic_train.csv`), o para descargarlo y agregarlo a tu carpeta data/raw. En ese caso, no olvides agregar la carpeta de datos al archivo .gitignore.

¡Es hora de trabajar en ello!

**Paso 2:**

Explora y limpia los datos.

**Paso 3:**

Construye un primer modelo predictivo usando Random Forest. Elije una métrica de evaluación y luego optimiza los hiperparámetros de tu modelo.

**Paso 4:**

Utiliza app.py para crear tu pipeline.

**Paso 5:**

Para guardar tu modelo y poder usarlo más tarde, usa el siguiente código:

```py

import pickle

filename = 'finalized_model.sav'
pickle.dump(model, open(filename, 'wb'))
```

En tu archivo README escribe un breve resumen.