# Caspone Project - H&M Recomendation
## Data Science and Machine Learning Postgraduate Course at UB, 2021-22
### Ester Iglesias Masó, Raquel Dominguez León y Ana Berta Vegas Segura

En este repositorio se puede encontrar el trabajo del Posgrado de Data Science y Maching Learning de Ester, Raquel y Ana Berta.

El objetivo del proyecto es encontrar un modelo que recomiende productos de H&M en función de sus clientes. Es decir, dado un conjunto de observaciones usuario-artículo, proporcionar un ranking adecuado por cada usuario.

Este trabajo repositorio esta estructurado de la siguente manera:

**1. Datos** (debido a la gran volumetría de estos, los archivos no son completos sino que son samples)
  - articles_sample.csv - datos detallados para cada article_id disponible para la compra
  - customers_sample.csv - datos para cada customer_id en el conjunto de datos
  - sample_submission_sample.csv - archivo de envío de muestra en el formato correcto de la solución
  - transactions_train_sample.csv - los datos de entrenamiento, que consisten en las compras de cada cliente para cada fecha, así como información adicional. Las filas duplicadas corresponden a compras múltiples del mismo artículo.

**2. Estudio de los datos**
  - Articles.ipynb* - estudio del dataset articles.csv
  - Customers.ipynb* - estudio del dataset customers.csv
  - Transactions.ipynb* - estudio del dataset transactions_train.csv 
  - Relacions.ipynb - estudio de las relaciones de los tres datasets anteriores
 
 *Al final de estos tres notebooks de estudio se extraen unos nuevos datasets que son los que se aplicaran al modelo: articles_model.csv, customers_model.csv y transactions_train_model.csv
 
**3. Modelo**
  - Model_H&M_Recomendation.ipynb - utilizaremos el sistema de recomendación Tensorflow (tfrs): Retrieval models para recomendaciones de productos de H&M.

La documentación de este proyecto se encuentra a lo largo de los notebooks tanto en la carpeta de "Estudio de los datos" como en la carpeta del "Modelo". 

