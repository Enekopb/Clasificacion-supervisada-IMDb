El codigo esta impletado en 4 jupyter notebooks:
 1. Preprocess: Los datos van descargados en la carpeta datos, son dos archivos ".parquet", como no queriamos utilizar la proporcion de 50/50 para hacer train y test se juntan en un archivo "datos.csv" en este programa. 
 2. RQ1: Este programa entrena y clasifica el conjunto de instancias con varias configuraciones de parametros para ambos clasificadores y compara el F-Score de todas estas.
 3. RF: Random Forest classifier. Este programa hace la limpieza de los datos, aplica una vectorizacion BoW o TFIDF, entrena el modelo y saca los resultados.
 4. MLP: Multilayer Perceptron classifier. Este programa hace la limpieza de los datos, aplica una vectorizacion BoW o TFIDF, entrena el modelo y saca los resultados.

Se ha ejecutado utilizando Google Colaboratory en Google Drive, por lo tanto, hay que ajustar las rutas de los archivos "csv" y "parquet" a la aplicación donde se ejecute.
