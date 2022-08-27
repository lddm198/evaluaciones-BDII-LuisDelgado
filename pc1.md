# Prueba Corta #1
## _Bases de Datos II_
### Luis Diego Delgado Muñoz
### Prof. Nereo Campos

#### Fecha de Entrega: 26/08/2022
-----
1. Explique en que consisten los siguientes conceptos:
a. Data Warehouse: Un almacenamiento de datos es un repositorio central de información que se puede analizar para tomar decisiones mejor informadas. Los datos fluyen hacia un almacenamiento de datos desde sistemas transaccionales, bases de datos relacionales y otros orígenes, normalmente a una cadencia regular. (Lahtela & Kaplan, 1966)
b. Data Lake: Los data lakes son repositorios centralizados que están diseñados para almacenar, procesar y proteger grandes cantidades de datos estructurados, semiestructurados y sin estructurar. Pueden almacenar datos en su formato nativo y procesar cualquier variedad sin tener en cuenta ningún límite de tamaño. (Google, 2022)
c. Data Mart: Un data mart es una forma simple de almacén de datos centrado en un solo tema o línea de negocio. Con un data mart, los equipos pueden acceder a los datos y obtener información más rápidamente, ya que no tienen que perder tiempo buscando en un almacén de datos más complejo o agregando manualmente datos de diferentes fuentes. (Oracle, 2022)

2. ¿De que forma se benefician las aplicaciones del uso de Columnar Storage? Explique.
**R/** El Columnar Storage para las tablas de la base de datos es un factor importante para optimizar el rendimiento de las consultas analíticas porque reduce drásticamente los requisitos generales de E/S del disco y reduce la cantidad de datos que necesita cargar desde el disco. (Burnworth, 2021)

3. ¿En que consiste streaming y batch processing?
**R/** El batch processing es cuando el procesamiento y el análisis ocurren en un conjunto de datos que ya se han almacenado durante un período de tiempo. El streaming processing ocurre a medida que los datos fluyen a través de un sistema. Esto da como resultado un análisis y un informe de los eventos a medida que ocurren. El streaming processing significa que los datos se analizarán y se tomarán medidas sobre los datos en un período corto de tiempo o casi en tiempo real, lo mejor que se pueda. (Confluent, 2022)

4. ¿En que consiste datos estructurados, semi estructurados y no estructurados?
**R/** Los datos estructurados son información que ha sido formateada y transformada en un modelo de datos bien definido. Los datos sin procesar se mapean en campos prediseñados que luego se pueden extraer y leer a través de SQL fácilmente. Los datos semiestructurados son un tipo de datos que tienen algunas características consistentes y definidas. No se limita a una estructura rígida como la necesaria para las bases de datos relacionales. Las propiedades organizativas como los metadatos o las etiquetas semánticas se utilizan con datos semiestructurados para hacerlos más manejables; sin embargo, todavía contiene cierta variabilidad e inconsistencia. Los datos no estructurados se definen como datos presentes en forma absoluta sin procesar. Estos datos son difíciles de procesar debido a su compleja organización y formato. La gestión de datos no estructurados puede tomar datos de muchas formas, incluidas publicaciones en redes sociales, chats, imágenes satelitales, datos de sensores de IoT, correos electrónicos y presentaciones, para organizarlos de manera lógica y predefinida en un almacenamiento de datos. (Naeem, 2022)


# Referencias Bibliográficas

Lahtela, M., &amp; Kaplan, P. (P. (1966).  Conceptos relacionados con el almacenamiento de datos. Amazon. Retrieved August 26, 2022, from https://aws.amazon.com/es/data-warehouse/ 
Oracle, C. (2022). What is a Data Mart? Oracle. Retrieved August 26, 2022, from https://www.oracle.com/autonomous-database/what-is-data-mart/ 
Google, C. (2022). What is a Data Lake? &nbsp;|&nbsp; google cloud. Google. Retrieved August 26, 2022, from https://cloud.google.com/learn/what-is-a-data-lake 
Burnworth, T. E. C. (2021). Redshift. Amazon. Retrieved August 26, 2022, from https://docs.aws.amazon.com/redshift/latest/dg/c_columnar_storage_disk_mem_mgmnt.html 
Confluent, I. (2022). Batch processing vs real time data streams. Confluent. Retrieved August 26, 2022, from https://www.confluent.io/learn/batch-vs-real-time-data-processing/
Burnworth, T. E. C. (2021). Redshift. Amazon. Retrieved August 26, 2022, from https://docs.aws.amazon.com/redshift/latest/dg/c_columnar_storage_disk_mem_mgmnt.html 

