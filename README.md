<<<<<<< HEAD
# segemntacion_clientes-basico


La segmentación de clientes es el proceso que permite a las empresas dividir a sus consumidores en categorías específicas, basadas en características que se extraen de su comportamiento como clientes y la información que pueden obtener de sus interacciones con la empresa.

Para este proyecto de <b>segmentación de clientes</b>, se usará un algoritmo de aprendizaje no supervisado, <b>k-means</b>; el cual, es un método de agrupamiento, que tiene como objetivo la partición de un conjunto de n observaciones (clientes en este caso) en k grupos en el que cada observación o cliente pertenece a un grupo característico. 

La base de datos que se usará para la elaboración de este cuaderno fue tomado de Kaggle. En esta dice que: 
_Este conjunto de datos se crea únicamente con fines de aprendizaje de los conceptos de segmentación de clientes, también conocido como análisis de la cesta de la compra._
https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python


Para esta tarea contamos con un conjunto de datos de 5 variables.
<li> <b>CustomerID:</b> identificador único de los clientes.
<li> <b>Gender:</b> género de los clientes. (Male, Female)
<li> <b>Age:</b> edad de los clientes.
<li> <b>Annual Income:</b> ingreso de los clientes por año.
<li> <b>Spending Score (1-100):</b> puntuación de compra. 
    
K-Means encuentra clústers basándose en la distancia, por lo que es importante que no tengamos variables categóricas. También, no tomaremos en cuenta la variable <b>"CustomerID"</b>, debido que sólo es un identificador que no nos aportará información. Nos quedamos con 3 variables.
    
Mediante el método de codo, para nuestro caso, podríamos determinar que entre nuestros datos existen entre 4 y 6 segmentos de clientes. Este es un punto donde entra el criterio experto para tomar la decisión de cual escoger. El método de codo sugiere 4 clusters.
    
### Conclusión
    
Como se menciona anteriormente, la cantidad de segmentos o clusters k es definido mediante criterio experto, el cual podría depender del problema al cual se busca hallar una solución. O bien, podríamos utilizar el método de codo para casos en el cual no tengamos una tarea definida o estemos desarrollando minería de datos.
 
=======
# SEGMENTACIÓN DE CLIENTES

Nosotros como persona o empresa, tenemos preferencias, rutinas, comportamientos, etc.,  

La segmentación de clientes es el proceso que permite a las empresas dividir a sus consumidores en categorías específicas, basadas en características que se extraen de su comportamiento como clientes y la información que pueden obtener de sus interacciones con la empresa.
>>>>>>> 130cea0230b25e83aa3bf421204a1896add89c2a
