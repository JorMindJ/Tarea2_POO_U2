Descripción del Proyecto:

Realizar la actividad de la tarea 1 Unidad 2 Relación entre Clases tiene como propósito 
ampliar y mejorar un proyecto Java utilizando conceptos avanzados de Programación Orientada a Objetos (POO), tales como herencia, asociación, agregación, y composición. 

Las características principales del proyecto son:

•	La importación del proyecto de GitHub configurado en el Workspace del IDE Eclipse.
•	La creación de nuevas clases y subclases con la implementación de los atributos, métodos y relaciones definidas.
•	La creación de un diagrama de clases del proyecto con las convenciones del UML.
•	La creación de un repositorio personal con el proyecto subido en GitHub.
•	La gestión del repositorio con 3 commits, descripciones y el archivo README.md

Se finaliza con la validación de la correcta funcionalidad del sistema y sin errores aparentes.


Nuevas clases y funcionalidades añadidas:
-	La clase Actor con una relación de asociación de la clase Película.
-	La clase Temporada con una relación de agregación de la clase SerieDeTV.
-	La clase Investigador con una relación de agregación de la clase Documental.

Creación de 2 nuevas clases con sus respectivas subclases:
-	La clase SocialReels y la subclase Usuarios con la relación de agregación.
-	La clase Publicidad y la subclase Producto con la relación de composición.

Desarrollo de un diagrama de clases del proyecto.
-Se agregan 2 nuevas instancias en la clase PruebaAudioVisual:
  -contenidos[3] = new SocialReels
  -contenidos[4] = new Publicidad
Se agregan 3 commits en la rama master:
  -Repositoreo Creado-Commit e2f5e82 by JorMindJ
  -Se agrega el atributo: descripciondelreels a la clase SocilaReels.-Commit 601f22e by JorMindJ
  -Se agrega comentarios al inicio de cada clase-Commit ae93442 by JorMindJ

Instrucciones para clonar y ejecutar el proyecto.

Paso 1: Abrir IDE Eclipse y selecciona la opción "Importar un proyecto desde GitHub". 

Paso 2: Utilizar el enlace proporcionado para clonar el repositorio en tu entorno de desarrollo. 
Paso 3: Verificar de que el proyecto se ha importado correctamente.
Paso 4: Dirigirse hacia el proyecto importado en el Paquete de Exploración del IDE, darle click derecho y seleccionar Run As en Java Application, funcionalidad que permite la interpretación y ejecución del código fuente del proyecto.


Mejoras:
-	En la optimización de la memoria como la creación de objetos, evitar la duplicación de datos y liberar recursos inactivos.
-	En la ejecución de pruebas unitarias usar frameworks como JUnit.
