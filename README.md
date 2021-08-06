# Evaluacion_Tecnoap
Evaluación para vacante de Científico de Datos en Tecnoap realizada por 
Carlos Alberto Juarez Santini


El codigo esta escrito en una notebook, fue elaborado en Google Colab. 
Este script se llama: "Tecnoap_Evaluacion.ipynb".

Es necesario cargar los dataset "Faults.train" y "Faults.test" en la carpeta raíz del proyecto, los cuales contienen los datos para entrenar algun modelo de machine learning y para hacer la prueba.

"Faults.train" contiene en la columna con indice 0 un identificador de la instancia del planchón, seguido de 27 columnas donde se regstran los valores de los atributos y 7 columnas más las cuales tienen los valores de la clase a la que pertenece. Son 1455 observaciones en total.

"Faults.test" contiene en la columna con indice 0, un identificador de la instnacia del planchon. Seguido de 27 columnas que representan los atributos de cada instancia que se busca clasificar. En total son 485 observaciones.

El archivo "Faults_completed.test", es el archivo generado al final de todo el proceso. Este archivo sigue la estructura de "Faults.train" pero con los datos de "Faults.test", agregandole la prediccion de la clase generada por el algoritmo, que corresponde cada instancia. Es decir se agregan 7 columnas más en el archivo.

"Tecnoap_decision_tree.pdf" es un mapa que representa las decisiones hechas por el arbol de decision entrenado.
