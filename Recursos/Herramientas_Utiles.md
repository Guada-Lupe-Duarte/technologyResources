# Máquina virtual. También conocido como "VM".

- Encontramos: Virtualbox, VMWare, KVM, Xen

# Docker

# Postman

> Sitio oficial: https://www.postman.com/product/what-is-postman/ 

Postman es una plataforma API para crear y utilizar API. Postman simplifica cada paso del ciclo de vida de la API y agiliza la colaboración para que puedas crear mejores API y más rápido.

Lo solemos utilizar para probar las distintas peticiones de cada proyecto.

# Git

# Zitadel

# Base de datos
Se utiliza para crear, editar y mantener archivos y registros de bases de datos, lo que facilita la creación de archivos y registros, la entrada de datos, la edición de datos, la actualización y la creación de informes.

La elección de la bbdd depende de lo que requiera el proyecto.

Las bases de datos relacionales están muy estructuradas y reconocen un lenguaje de programación denominado Lenguaje de consulta estructurado (SQL, por sus siglas en inglés). Las bases de datos no relacionales son muy diversas y admiten una gran variedad de estructuras de datos. Puesto que muchas bases de datos no relacionales no utilizan SQL, a menudo se denominan bases de datos NoSQL.

> ***Base de datos relacional***\
En una base de datos relacional, que es el tipo más común, los datos se organizan en tablas que contienen información sobre cada entidad y representan categorías predefinidas mediante filas y columnas. Estos datos estructurados son eficaces y flexibles a la hora de acceder a ellos.\
Algunos ejemplos de bases de datos relacionales son SQL Server, Azure SQL, MySQL, PostgreSQLy MariaDB.

> ***Base de datos no relacional***\
Las bases de datos no relacionales almacenan datos no estructurados o semiestructurados. No usan tablas con columnas y filas como lo hacen las bases de datos relacionales. En su lugar, utilizan un modelo de almacenamiento que está optimizado para los requisitos específicos del tipo de datos que se almacena. Las bases de datos no relacionales permiten acceder a conjuntos más grandes de datos distribuidos, actualizarlos y analizarlos rápidamente.\
Algunos ejemplos de bases de datos no relacionales son MongoDB, Azure Cosmos DB, DocumentDB, Cassandra, Couchbase, HBase, Redis y Neo4j.\
El término “NoSQL” hace referencia a almacenes de datos que no usan SQL (o no solo SQL) para las consultas.\
Un tipo de base de datos no relacional (una base de datos de objetos) usa la programación orientada a objetos. Los objetos se codifican con un estado (datos fácticos), que se almacena en un campo o variable, y un comportamiento, que se muestra mediante un método o una función. Los objetos se pueden mantener en un almacenamiento persistente para siempre y leerse y asignarse directamente sin una API o herramienta, lo que proporciona un acceso más rápido a los datos y un mejor rendimiento.

> Arquitectura de la base de datos

- **Base de datos centralizada,** todos los datos de un sistema residen en un solo sistema.

- **Base de datos distribuida,** puede abarcar bases de datos tanto relacionales como no relacionales. En las bases de datos distribuidas, los datos se almacenan en varias ubicaciones físicas, ya sea en varios equipos locales o dispersos en una red de equipos interconectados.
  
- **Base de datos distribuida,** varias bases de datos distintas que se ejecutan en servidores independientes se unifican en un objeto grande.

> Capacidad de aumentar

- **Escalado vertical,** proceso de agregar recursos, puede ser memoria o cpu para que se adapten al servidor actual.

- **Escalado horizontal** agrega más máquinas al grupo de recursos. Amplia el ciclo de vida del hardware actual, permite actualizar los recursos sin depender de un proveedor, reduce los costos y lo potencia en flexibilidad a largo plazo.