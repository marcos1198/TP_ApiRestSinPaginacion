# TP_ApiRestSinPaginacion
# Datos del alumno👨‍🎓:

* Nombre: Oropel, Marcos Jose
* Legajo: 43986

# Datos institucionales📚:

* Universidad Tecnológica Nacional - Facultad Regional Mendoza
* Cátedra: Desarrollo de Software
* Comisión: 3K09
* Turno: tarde
* Año: 2023

# Acerca de la entrega💾:

* Se entrega un modelod de persistencia de un diagrama de clases dado por la cátedra.
* Existen las entidades, los repositorios de las mismas y una serie de enumeraciones para facilitar el trabajo
* Descargar el archivo zip, desempaquetarlo, esperar a que se instalen las dependencias y ejecutar el codigo en el ide.
* Realizar las siguientes actividades correspondientes al estudio del modelo de Biblioteca expresado en los videos de Colmena Tec
* 1-Crear el Modelo de Diagrama de Clase que se muestra en el video:
* Capturar la pantalla del diagrama y pegarla en un documento word. El nombre del archivo será apellidoLegajoDia.doc
* 2- Estudiar la siguiente Playlist:
* https://www.youtube.com/watch?v=rmCvCOBAqEA&list=PLRFOqDrY-6nueU8NwtjRIcX5-nsD6jkru&ab_channel=ColmenaTEC
* Desde el video :
* API REST con Spring Boot 1 Introducción HASTA el video  API REST con Spring Boot 12 Probando la API con Postman
* a-  No considerar la sección de auditoría de Enver.
* b- Refactorice el código  de los videos para utilizar una base de datos H2.
* c- Coloque las dependencias correspondientes de Swagger como dependencia en el buil.gradle:
* // https://mvnrepository.com/artifact/org.springdoc/springdoc-openapi-starter-webmvc-ui
* implementation group: 'org.springdoc', name: 'springdoc-openapi-starter-webmvc-ui', version:'2.1.0'
* d- Crearse una cuenta en Render
* f- Incorporar en el archivo de build.gradle:
* jar {
*    manifest {
*      attributes 'RestfakeApplication': 'com.facu.restfake.RestfakeApplication' // Reemplaza 'tu.paquete.MainClass' con la clase principal de tu aplicación
*   }
*}
* - Ejecute el comando gradle build  desde la terminal para crear el jar correspondiente.
* Se creará en el proyecto una carpeta:
* build/libs/restfake-0.0.1-SNAPSHOT.jar
* e-  Utilizar el Archivo Dockerfile que se propone en el github y actualizar el nombre de tu jar:
* FROM openjdk:17-alpine
* EXPOSE 9000
* COPY --from=build ./build/libs/elnombredetujar-0.0.1-SNAPSHOT.jar ./app.jar
* f - Descargar el proyecto MODELO AUXILIAR  a analizar desde el Link de Github:
* https://github.com/cortezalberto/claseFakeGenerico
* - Estudiar las entidadesProducto y Rating correspondientes y realizar la interpretación de las mismas.
* Las capas de la aplicación, los controladores genéricos, Servicios y repositorios.
* Rúbrica de evaluación del Tp:
*  Todas las clases
*  Todas las enumeraciones
*  Propiedades y métodos en las clases
*  Todas las relaciones 
* Todas las cardinalidades
* Todos los controladores - Todos los repositorios - Todos los Servicios
* El jar creado 
* El archivo del diagrama de clases creado
* Un archivo generado con postman para probar TU API - Una colleción
* El trabajo se entrega en un Repo en la nube, con todo lo solicitado

para sincronizar la aplicación con render y recordar los pasos:
https://www.youtube.com/watch?v=p8mta5Q7rx8&ab_channel=ColmenaTEC

# LINKS:
GitHub:https://github.com/marcos1198/TP_ApiRestSinPaginacion.git
Render:https://sinpaginacion.onrender.com
Diagrama de clases:
https://github.com/marcos1198/TP_ApiRestSinPaginacion/blob/c5f54103e44e75a01b13ddd6de58e40caef59e5b/DC_SinPaginacion.png

# Contacto☎️:
* Email📩: m.oropel1198@gmail.com
