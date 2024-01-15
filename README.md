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
Aplicar conocimientos obtenidos en la materia de Profundización en Automatización y Control.

* Descripción:
El programa contiene el desarrollo del proyecto final en la materia de Profundización de Automatización y Control respecto a una idea propuesta por cada grupo. En nuestro caso, optamos por trabajar orientados en la industria, con datos que registran las medidas de calidad de potencia con el analizador de redes instalado en el punto de inyección de un sistema fotovoltaico de 15kWp que integra 30 PV a 540 W, y finalmente dar un agregado con lo aprendido en la materia.

Los principales obstáculos en el desarrollo de este programa radican en:
+ Los datos: Los datos se encontraban en un formato CSV pero los valores estaban guardados como cadena de caracteres y en notación científica, por lo tanto se requirión un pre-procesado de los datos, filtrándolos y ajustándolos para facilitar la lectura de los mismos en VScode.
+ Cantidad de datos: El módulo encargado de arrojar los datos usados, solo guarda una cantidad finita y relativamente pequeña de los mismos, por lo cual se generó un desequilibrio de casos dificultando enormemente obtener resultados satisfactorios en las predicciones de nuestro modelo.


* Resultados:
Se obtuvo el modelo que cumple con los requerimientos funionales para la automatización de la tarea de alerta a operarios en caso de problemas en la red eléctrica. Se evidencia la clasificación de los datos anómalos.
De la misma forma se logró automatizar la exportación de graficas de 300dpi lo cual es una buena resolución para posteriorres análisis de los datos.
Nuestro programa facilita la monitorización de las medidas sobre la calidad de potencia eléctrica para los 8 días registrados por la máquina, brinda información fisual a trvés de gráficas con el mismo fin y además da el análisis de los posibles problemas en la red eléctrica como los mostrados en la gráfica.