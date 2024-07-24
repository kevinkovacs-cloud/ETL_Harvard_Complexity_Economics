# ETL_Harvard_Complexity_Economics
Proyecto de ETL para base de datos de complejidad económica (comex).

En el notebook ETL encontrarán dos formas (una fallida y una exitosa) de extraer la base de datos compuesta por 60 archivos ".dta". 
Una vez cargados, intenté mergearlos pero me tiró un error debido a que los data types eran diferentes entre las columnas.
Iteré sobre cada archivo para identificar esos errores y lo solucioné.
Luego exporté dos datasets, uno con todos los paises y otro con países de interés para estudiar (Argentina, Brasil, Indonesia, Tailandia, Corea del Sur y Malasia).
Ambos con 6 productos elegidos de comercio entre países (sector secundario).

En el notebook ETL2 hice un proceso de transformación de datos para obtener los totales para cada país.
