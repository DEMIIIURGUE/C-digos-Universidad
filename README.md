# DESARROLLO PROYECTO FINAL.                       
Códigos entregables universidad Nariño    
Desarrollado Por:                         
* Juan José Torres Quiñonez. 220160099.            
* Jeison Guillermo Moreno Eraso. 220160072.  
* Jonathan David Rosero Moreno. 220160119.

* Introducción:
En el presente trabajo se pretende presentar por medio de código en python, el entrenamiento de un modelo para la clasificación de datos faltantes importados desde la base de datos obtenida de una planta agroindustrial real. Dicho modelo presenta el análisis y alerta en casos de fallas en la red eléctrica por medio del reconocimiento de datos anómalos en tensión RMS en una de las fases del dispositivo.

* Objetivos:
Automatizar un proceso, en este caso, el reconocimiento de fallas en la red eléctrica de la planta agroindustrial.
Clasificar los datos anómalos.
Exportar gráficas representativas.

* Descripción:
El programa contiene el desarrollo del proyecto final en la materia de Profundización de Automatización y Control respecto a una idea propuesta por cada grupo. En nuestro caso, optamos por trabajar orientados en la industria, con datos que registran las medidas de calidad de potencia con el analizador de redes instalado en el punto de inyección de un sistema fotovoltaico de 15kWp que integra 30 PV a 540 W, y finalmente dar un agregado con lo aprendido en la materia.

Los principales obstáculos en el desarrollo de este programa radican en:
+ Los datos: Los datos se encontraban en un formato CSV pero los valores estaban guardados como cadena de caracteres y en notación científica, por lo tanto se requirión un pre-procesado de los datos, filtrándolos y ajustándolos para facilitar la lectura de los mismos en VScode.
+ Cantidad de datos: El módulo encargado de arrojar los datos usados, solo guarda una cantidad finita y relativamente pequeña de los mismos, por lo cual se generó un desequilibrio de casos dificultando enormemente obtener resultados satisfactorios en las predicciones de nuestro modelo.


* Resultados:
