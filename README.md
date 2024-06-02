
# Proyecto de investigación enfocado en la detección de anomalías en datos geográficos vector y ráster
## [Maestría en Ciencias de la Información y las Comunicaciones - MCIC ](https://facingenieria.udistrital.edu.co/maestria-ciencias-informacion/index.php/)
## Universidad Distrital Francisco José de Caldas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000?style=for-the-badge&logo=postgresql) ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Vscode](https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Contexto

El siguiente proyecto tiene como propósito

## Tabla de contenido

 - [Introducción]()
 - [Entendimiento del negocio]()
 - [Entendimiento de los datos]()
 - [Preparacón de los datos]()
 - [Uso de los modelos]()
 - [Evaluación de mejores modelos]()
 - [Recomendaciones finales]()


## Autores
- [Carlos Gutiérrez - @ingenieco](https://github.com/Ingenieco)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ingenieco-cegu/)


## Introducción

El siguiente proyecto tiene como objetivo evaluar diferentes modelos de clasificación y de predicción para un conjunto de datos de viviendas en venta en la ciudad de Medellín. A través de modelos supervisados y no supervisados se quiere predecir valores de inmuebles en venta y, clasificarlos en apartamentos o casas.

Para el desarrollo del presente proyecto se empleó la metodología CRISP-DM. Y en consecuencia se definió la siguiente Arquitectura del Proyecto.

### Arquitectura
![Arquitectura del proyecto](https://github.com/Ingenieco/tf_aa_uao/blob/main/imagenes/arquitectura.svg)

### [Gestión de procesos - Trello](https://trello.com/b/86Xuoozl)

Se construyó un tablero con la gestión de procesos, gestionado a través de Trello. Donde se establecieron lassiguientes listas de actividades:
* Lista de tareas
* En proceso
* Pendientes
* Terminados

## Entendimiento del negocio

El valor de un bien raíz no sólo está determinado por sus características estrictamente residenciales, comerciales o industriales, sino también por los complejos procesos de inversión, especulación y arbitraje que tienen lugar con el crecimiento y desarrollo urbano de las ciudades, con la congestión de las áreas urbanas inducida por el mayor poblamiento y el crecimiento de la edificación, y con las políticas de regulación urbana que implementa la autoridad, entre otros. 

La Teoría de Precios Hedónicos pretende explicar el valor de un bien raíz, entendido como un conjunto de atributos (superficie, aptitud de uso del suelo, calidad de la construcción, diseño interior y exterior, áreas verdes, ubicación, características del vecindario, etc.), en función de cada uno de ellos, obteniendo sus respectivas valoraciones y, por ende, demandas implícitas. 

En otras palabras, la teoría permite identificar la importancia relativa de cada atributo en el valor asignado por el mercado a un bien raíz, mediante lo cual es posible determinar cómo cambiará dicho valor al variar la cantidad y calidad en que se encuentra presente cada uno de estos atributos, y consecuentemente, predecir precios. (Lever, 2016)

$$V = f(I, V, S, E)$$

Siendo $I$: características del inmueble; $V$: características del vecindario; $S$: características del nivel de equipamiento exterior; $E$: externalidades presentes en el entorno del bien inmueble

## EDA
[Gestión de procesos - Trello](https://github.com/Ingenieco/tf_aa_uao/blob/main/notebooks/EDA.ipynb)

Ver mapa [mapa interactivo](https://github.com/Ingenieco/tf_aa_uao/blob/main/imagenes/mapa.html){target="_blank"}

<a href = "https://github.com/Ingenieco/tf_aa_uao/blob/main/imagenes/mapa.html" target="_blank">Abrir archivo HTML en una nueva pestaña</a>