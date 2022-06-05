# Práctica 2: Titanic Dataset Analysis

## Descripción:
Esta práctica se ha realizado bajo el contexto de la asignatura Tipología y ciclo de vida de los datos, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. En ella, se realiza el tratamiento del dataset "Titanic", identificando los datos relevantes y tratamientos necesarios de integración, limpieza y validación de los datos, para responder distintas preguntas que se plantean y aplicar métodos estadísticos para comparar distintas muestras dentro del dataset. 

## Integrantes del equipo:
* Erika Paola Martínez Soria
* Eugenia Bezek

## Ficheros del repositorio:

* titanic_analysis.py: Es el script que contiene el código donde se realiza la limpieza, tratamiento y el análisis de los datos.
* titanic.csv: Es el archivo con los datos.
* M2.851_20211_Prac2_BezekEugenia_ErikaMartinez.pdf: Documento con las respuestas de la práctica.

## Detalle del dataset:
##### El conjunto de datos tiene 12 columnas o varables:

* Passenger ID: ID to identity each passenger
* Name
* Age
* Survived: Survival: 0 = No, 1 = Yes
* Pclass: A proxy for socio-economic status (SES)
    1st = Upper
    2nd = Middle
    3rd = Lower
* SibSp: # of siblings / spouses aboard the Titanic:
    Sibling = brother, sister, stepbrother, stepsister
    Spouse = husband, wife (mistresses and fiancés were ignored)
* Parch: # of parents / children aboard the Titanic:
    Parent = mother, father
    Child = daughter, son, stepdaughter, stepson.
    Some children travelled only with a nanny, therefore parch=0 for them.
* Ticket: Ticket number
* Fare: Passenger fare
* Cabin: Cabin number
* Embarked: Port of Embarkation:
    C = Cherbourg
    Q = Queenstown
    S = Southampton
    

##### Las librerias que hay que instalar son:
   * pip install statsmodels
