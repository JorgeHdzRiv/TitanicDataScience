# Índice

* **[Título del proyecto](#titulo-del-proyecto)**
* **[Descripción](#descripcion)**
* **[Objetivos](#objetivos)**
* **[Datos](#datos)**
* **[Métodos](#metodos)**
* **[Instalación y Ejecucion](#instalación-y-ejecución)**
* **[Recursos](#recursos)**
* **[Resultados](#resultados)**

## Título del proyecto

Análisis y predeccion de la supervivencia en el Titanic

## Descripción

Este proyecto tiene como objetivo analizar los factores que influyeron en la supervivencia de los pasajeros del Titanic y crear un modelo predictivo para determinar si un pasajero sobrevivió o no al hundimiento del Titanic.

## Objetivos

* Realizar un análisis exploratorio de datos para comprender la distribución y relaciones en el conjunto de datos.
* Preprocesar los datos para manejar valores faltantes y convertir variables categóricas.
* Construir y comparar modelos predictivos utilizando algoritmos de aprendizaje automático.
* Analizar los resultados y extraer conclusiones sobre los factores que influyeron en la supervivencia.

## Datos

[Dataset Completo](https://www.kaggle.com/competitions/titanic/overview)

Este conjunto de datos contiene información sobre los pasajeros del Titanic, incluyendo su edad, género, clase de boleto, tarifa, etc. El objetivo es predecir si un pasajero sobrevivió o no al hundimiento del Titanic. El conjunto de datos tiene 12 columnas y 1309 filas entre el dataset Train y Test. 

Algunas de las columnas son:

Pclass: La clase del boleto del pasajero (1 = primera clase, 2 = segunda clase, 3 = tercera clase).
Sex: El género del pasajero.
Age: La edad del pasajero.
SibSp: El número de hermanos/cónyuges a bordo.
Parch: El número de padres/hijos a bordo.
Fare: La tarifa pagada por el pasajero.
Embarked: El puerto de embarque del pasajero (C = Cherbourg, Q = Queenstown, S = Southampton).

## Métodos

* Análisis exploratorio de datos (EDA).
* Preprocesamiento de datos.
* Construcción de modelos predictivos con algoritmos de clasificación.




## Instalación y Ejecución

Para trabajar en este proyecto, se recomienda el uso de un ambiente virtual. Sigue estos pasos para configurar el ambiente y ejecutar el proyecto:

1. **Crea un ambiente virtual:**

    ```bash
    pip install virtualenv
    virtualenv venv
    ```

2. **Activa el ambiente virtual:**

    - En sistemas basados en Unix (Linux o macOS):

      ```bash
      source venv/bin/activate
      ```

    - En Windows:

      ```bash
      .\venv\Scripts\activate
      ```

3. **Instala las dependencias:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Ejecuta el proyecto:**

    Por ejemplo, para ejecutar el análisis exploratorio de datos:

    ```bash
    jupyter notebook notebooks/exploratory_analysis.ipynb
    ```

5. **Desactiva el ambiente virtual cuando hayas terminado:**

    ```bash
    deactivate
    ```

Asegúrate de seguir estos pasos para configurar el ambiente virtual antes de trabajar en el proyecto. ¡Disfruta del análisis y la predicción de la supervivencia en el Titanic!


## Recursos

* [Documentación de scikit-learn](https://scikit-learn.org/stable/index.html) para referencia sobre algoritmos de aprendizaje automático.
* [Tutorial de análisis exploratorio de datos con Pandas](https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python).

## Resultados