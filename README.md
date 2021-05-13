# Taller de productividad basada en herramientas tecnologicas
# Descripción
El planteamiento recae en un sistema de gestion de ventas, dadas de alta para usuarios y productos, con lo que se busca gestionar una PyME utilizando este herramienta, se estima agilizar los movimientos del usuario, en vez de utilizar papel para registrar los productos, utilizar un sistema para darlos de alta almacenadolos en una base de datos y de esta manera tenga acceso a ello con una facilidad en una aplicacion.

# Problema identificado
* Las tiendas locales pequeñas como abarrotes, tienditas, etc. (PyME) muchas veces no cuentan con un sistema de punto de venta debido a los altos costos, por lo que identificar productos, escanearlos, etc resulta muy dificil cuando se intenta registrarlo en una hoja de papel, por lo que mi idea principal es lograr desarrollar un sistema que ayude a las PyMES mitigando este problema y agilizando sus movimientos, mi principal objetivo es otorgar gratuitamente este sistema a las tiendas PyME que existen cerca de mi localidad, de esta manera mejorar la economia local cerca de mi hogar.

# Tabla de contenido

Proyecto punto de venta
* Build
  -  Classes
  - built-jar.properties

* Classes
  - Img
    - Imagenes
  - Modelo
    - .class (Clases)
  -  Vistas
     - .class (Vistas)
 
 * nbproject
     - private
       -  build-impl.xml
       -  genfiles.properties
       -  project.properties
       -  project.xml
  
 - .circleci
 - LICENSE
 - README.md
 - build.xml
 - config.yml
 - manifest.mf

# Requerimientos
* Lectura de archivos .xls
* Id de productos
* Gestor de inventario
* Agregar y modificar altas de productos
* Agregar y modificar altas de usuarios
* Importar usuarios
* Guardar informacion
* Almacenamiento en base de datos
* Visualizacion de informacion actualizada

# Diseño
* Login
* Interfaz de usuario
* Ventana de ventas
* Ventana de alta de usuario
* Ventana de Alta de productos
* Tabla con informacion del usuario
* Tabla con informacion de Id del producto

# Versión de Java
Version 8 Update 291

# Base de datos
La implementacion consta de una base de datos en la que se almacenan la informacion del cliente y de los productos, por medio de una conectividad en java mysql.java para lograr obtener los datos almacenados y los productos almacenados para lograr mostrarlos.

* Para poder correr el programa es necesario tener phpmyadmin para importar el .sql del proyecto, de esta forma se podran hacer cambios asi como logearse debido a la integracion del login.

# Instalación
* Descargar el proyecto del repositorio
* Descomprimir .rar / .zip
* Se abre la carpeta para localizar el archivo .jar
* Se inicia el ejecutable

# Configuración
* Se procede a instalar la version 8 de java o en su defecto la más actual.
* Configuracion del ambiente de JAVA 

# Uso
El principal uso es exclusivamente para los negocios PyME que requieran dar alta de usuarios, productos para agilizar sus movimientos de registro, con este software el usuario lograra implementar mejores practicas para agilizar sus procesos, para esto se otorga una cuenta administrador en la que el usuario lograra ingresar y modificar parámetros.

# Contribución
* Se abre el repositorio
* Link del repositorio: https://github.com/VictorInterian/TallerProd
* Dentro del branch master lograremos encontrar la version actual del software
* En el lado derecho podemos encontrar los botones clone y download
* De manera que podemos elejir entre abrir en escritorio o descargar .zip (Recomendable)

# Roadmap
Se espera que se mejore la implementacion de la base de datos con el sistema, se espera mejorar mas funciones como el boton de ayuda e implementar mas caracteristicas que ayudaran a mejorar el sistema

# Alumno
Victor Hugo Cavazos Interián   2838808


