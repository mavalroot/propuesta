
# Catálogo de requisitos

| **R01**     | **Issues**           |
| --------------: | :------------------- |
| **Descripción** | Requisitos perfectamente definidos y convertidos en incidencias (Issues) de Github.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R02**     | **Código fuente**           |
| --------------: | :------------------- |
| **Descripción** | Código fuente publicado en Github             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R03**     | **Estilo del código**           |
| --------------: | :------------------- |
| **Descripción** | Estilo del código según las normas internas de Yii2 para el código y para las plantillas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R04**     | **Releases**           |
| --------------: | :------------------- |
| **Descripción** | Tres lanzamientos (releases) etiquetados en el repositorio como v1, v2 y v3.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R05**     | **README.md**           |
| --------------: | :------------------- |
| **Descripción** | README.md en el directorio raíz con la descripción principal del proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R06**     | **Documentación**           |
| --------------: | :------------------- |
| **Descripción** | Documentación generada con yii2-apidoc y publicada en Github Pages a partir del contenido del directorio /docs:  a. Contenido:    i. Guía general    ii. API  b. Formato: Github flavored Markdown (fuente) y HTML (resultado).  c. Usar script publicar_doc.sh contenido en la raíz del proyecto.  d. Opciona: conversión a PDF             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R07**     | **Incidencias**           |
| --------------: | :------------------- |
| **Descripción** | Administración y resolución de todas las incidencias notificadas en Github.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R08**     | **Etiquetas e hitos**           |
| --------------: | :------------------- |
| **Descripción** | Usar etiquetas e hitos:  a. Etiquetas: mínimo, importante, opcional (además de las ya existentes).  b. Hitos: v1, v2, v3 (con fechas de entrega aproximadas).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R09**     | **Rama master**           |
| --------------: | :------------------- |
| **Descripción** | La rama mastr debe reflejar en todo momento el estado más estable de la aplicación, de manera que:  a. La rama master no debe contener bugs conocidos.  b. El desarrollo deberá hacerse en otras ramas creadas a tal efecto (una distinta por cada funcionalidad) y se irán combinando con la master una vez que se haya implementado la funcionalidad correspondiente.  c. Cada rama debe ir asociada con una incidencia. El nombre de la rama debe empezar por el número de la incidencia correspondiente (p. ej. 17-login).  d. La release actual en Heroku corresponderá siempre con el último commit de la rama master (usar los deploys automáticos de Heroku conectando la aplicación de Heroku con la rama master de Github).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R10**     | **Waffle**           |
| --------------: | :------------------- |
| **Descripción** | Usar Waffle para la gestión general del proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R11**     | **Iteraciones**           |
| --------------: | :------------------- |
| **Descripción** | Al final de cada iteración:  a. Se realiza el lanzamiento que toque (v1, v2 o v3), etiquetando el commit correspondiente con el hito adecuado.  b. Se actualiza y publica la documentación.  c. Al final del Proyecto, se tiene que cumplir lo siguiente:    i. Todas las incidencias cerradas con su debida justificación.    ii. En el backlog sólo pueden quedar tarjetas con prioridad opcional.    iii. El lanzamiento v3 desplegado en la nube.    iv. La documentación correctamente actualizada y publicada.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R12**     | **Validación de formularios**           |
| --------------: | :------------------- |
| **Descripción** | Validación de los campos de los formularios usando JavaScript.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R13**     | **Gestión de ventanas**           |
| --------------: | :------------------- |
| **Descripción** | Gestión de la apariencia de las ventanas. Creación de nuevas ventanas y comunicación entre ventanas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R14**     | **Manejo de eventos**           |
| --------------: | :------------------- |
| **Descripción** | Interactividad a través de mecanismo de manejo de eventos intuitivos y eficaces.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R15**     | **Uso del DOM**           |
| --------------: | :------------------- |
| **Descripción** | Uso y manipulación de las características del modelo de objetos del documento (DOM).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R16**     | **Cookies**           |
| --------------: | :------------------- |
| **Descripción** | Uso de mecanismos de almacenamiento en el lado del cliente.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R17**     | **Jquery**           |
| --------------: | :------------------- |
| **Descripción** | Uso de la librería Jquery.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R18**     | **Plugins**           |
| --------------: | :------------------- |
| **Descripción** | Incluir al menos un plugin no trabajado en clase.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R19**     | **AJAX**           |
| --------------: | :------------------- |
| **Descripción** | Utilización de mecanismos de comunicación asíncrona: AJAX.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R20**     | **PHP**           |
| --------------: | :------------------- |
| **Descripción** | Usar PHP 7.1             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R21**     | **Yii2**           |
| --------------: | :------------------- |
| **Descripción** | Usar Yii2 Framework versión 2.0.10 o superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R22**     | **PostgreSQL**           |
| --------------: | :------------------- |
| **Descripción** | Usar PostgreSQL versión 9.6 o superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R23**     | **Heroku**           |
| --------------: | :------------------- |
| **Descripción** | Despliegue de la apliación en la plataforma Heroku.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R24**     | **Codeception**           |
| --------------: | :------------------- |
| **Descripción** | Pruebas funcionales con Codeception.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R25**     | **Code Climate**           |
| --------------: | :------------------- |
| **Descripción** | Estilo y mantenibilidad del código fuente validados por Code Climate.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R26**     | **Escalabilidad**           |
| --------------: | :------------------- |
| **Descripción** | La aplicación ha de ser escalable             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R27**     | **HTML5**           |
| --------------: | :------------------- |
| **Descripción** | Para estructurar el contenido se utilizarán las etiquetas semánticas de HTML5.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R28**     | **CSS3**           |
| --------------: | :------------------- |
| **Descripción** | Todo lo relacionado con la presentación se trabajará mediante CSS3.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R29**     | **Diseño flexible**           |
| --------------: | :------------------- |
| **Descripción** | El diseño será flexible             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R30**     | **Animaciones**           |
| --------------: | :------------------- |
| **Descripción** | Existirán transiciones, transformaciones, animaciones y contenido multimedia.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R31**     | **Microdatos**           |
| --------------: | :------------------- |
| **Descripción** | Uso de microdatos.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R32**     | **Superar pruebas**           |
| --------------: | :------------------- |
| **Descripción** | Se deberá comprobar que el código supera:  a. Validador para HTML5, CSS3.  b. Nivel de accesibilidad AA.  c. Prueba del seis.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R33**     | **Resoluciones**           |
| --------------: | :------------------- |
| **Descripción** | Implementar el diseño para resoluciones grandes y pequeñas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R34**     | **Navegadores**           |
| --------------: | :------------------- |
| **Descripción** | Comprobar que el diseño es correcto en: Internet Explorer, Chrome, Mozilla Firefox, Opera.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R35**     | **Despliegue en Host**           |
| --------------: | :------------------- |
| **Descripción** | Realizar el despliegue en un Host:   a. Utilizando algún servicio gratuito de hosting como los vistos en clase.  b. Instalar / configurar o solicitar el software necesario para desplegar el proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R36**     | **Despliegue local**           |
| --------------: | :------------------- |
| **Descripción** | Realizar un despliegue en un servidor local usando y configurando tres máquinas virtuales para:  a. Crear un servicio de Nombres de dominio.  b. Gestionar y administrar el servidor Apache tanto en Windows como en Linux.    i. Instalar el servidor y configurarlo.    ii. Configurar directivas.    iii. Usar directorios virtuales y redireccionamientos.    iv. Usar diferentes módulos estáticos y dinámicos.    v. Usar autenticaciones.    vi. Usar ficheros de configuración personalizada de directorios.    vii. Usar HTTPS y certificados Digitales.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R37**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R38**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R39**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R40**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R41**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R42**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R43**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R44**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R45**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R46**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R47**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R48**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R49**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R50**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R51**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R52**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R53**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R54**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R55**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R56**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R57**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R58**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R59**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R60**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R61**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R62**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R63**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R64**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R65**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R66**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R67**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |


| **R68**     | ****           |
| --------------: | :------------------- |
| **Descripción** |              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     |              |



## Cuadro resumen

| **Requisito** | **Prioridad** | **Tipo** | **Complejidad** | **Entrega** |
| :------------ | :-----------: | :------: | :-------------: | :---------: |
| (**R01**) Issues | Mínimo | Técnico | Fácil | v1 |
| (**R02**) Código fuente | Mínimo | Técnico | Fácil | v2 |
| (**R03**) Estilo del código | Mínimo | Técnico | Fácil | v3 |
| (**R04**) Releases | Mínimo | Técnico | Media | v3 |
| (**R05**) README.md | Mínimo | Técnico | Media | v3 |
| (**R06**) Documentación | Mínimo | Técnico | Media |  |
| (**R07**) Incidencias | Mínimo | Técnico | Media |  |
| (**R08**) Etiquetas e hitos | Mínimo | Técnico | Media |  |
| (**R09**) Rama master | Mínimo | Técnico | Media |  |
| (**R10**) Waffle | Mínimo | Técnico | Media |  |
| (**R11**) Iteraciones | Mínimo | Técnico | Media |  |
| (**R12**) Validación de formularios | Mínimo | Técnico | Media |  |
| (**R13**) Gestión de ventanas | Mínimo | Técnico | Media |  |
| (**R14**) Manejo de eventos | Mínimo | Técnico | Media |  |
| (**R15**) Uso del DOM | Mínimo | Técnico | Media |  |
| (**R16**) Cookies | Mínimo | Técnico | Media |  |
| (**R17**) Jquery | Mínimo | Técnico | Media |  |
| (**R18**) Plugins | Mínimo | Técnico | Media |  |
| (**R19**) AJAX | Mínimo | Técnico | Media |  |
| (**R20**) PHP | Mínimo | Técnico | Media |  |
| (**R21**) Yii2 | Mínimo | Técnico | Media |  |
| (**R22**) PostgreSQL | Mínimo | Técnico | Media |  |
| (**R23**) Heroku | Mínimo | Técnico | Media |  |
| (**R24**) Codeception | Mínimo | Técnico | Media |  |
| (**R25**) Code Climate | Mínimo | Técnico | Media |  |
| (**R26**) Escalabilidad | Mínimo | Técnico | Media |  |
| (**R27**) HTML5 | Mínimo | Técnico | Media |  |
| (**R28**) CSS3 | Mínimo | Técnico | Media |  |
| (**R29**) Diseño flexible | Mínimo | Técnico | Media |  |
| (**R30**) Animaciones | Mínimo | Técnico | Media |  |
| (**R31**) Microdatos | Mínimo | Técnico | Media |  |
| (**R32**) Superar pruebas | Mínimo | Técnico | Media |  |
| (**R33**) Resoluciones | Mínimo | Técnico | Media |  |
| (**R34**) Navegadores | Mínimo | Técnico | Media |  |
| (**R35**) Despliegue en Host | Mínimo | Técnico | Media |  |
| (**R36**) Despliegue local | Mínimo | Técnico | Media |  |
| (**R37**)  | Mínimo | Técnico | Media |  |
| (**R38**)  | Mínimo | Técnico | Media |  |
| (**R39**)  | Mínimo | Técnico | Media |  |
| (**R40**)  | Mínimo | Técnico | Media |  |
| (**R41**)  | Mínimo | Técnico | Media |  |
| (**R42**)  | Mínimo | Técnico | Media |  |
| (**R43**)  | Mínimo | Técnico | Media |  |
| (**R44**)  | Mínimo | Técnico | Media |  |
| (**R45**)  | Mínimo | Técnico | Media |  |
| (**R46**)  | Mínimo | Técnico | Media |  |
| (**R47**)  | Mínimo | Técnico | Media |  |
| (**R48**)  | Mínimo | Técnico | Media |  |
| (**R49**)  | Mínimo | Técnico | Media |  |
| (**R50**)  | Mínimo | Técnico | Media |  |
| (**R51**)  | Mínimo | Técnico | Media |  |
| (**R52**)  | Mínimo | Técnico | Media |  |
| (**R53**)  | Mínimo | Técnico | Media |  |
| (**R54**)  | Mínimo | Técnico | Media |  |
| (**R55**)  | Mínimo | Técnico | Media |  |
| (**R56**)  | Mínimo | Técnico | Media |  |
| (**R57**)  | Mínimo | Técnico | Media |  |
| (**R58**)  | Mínimo | Técnico | Media |  |
| (**R59**)  | Mínimo | Técnico | Media |  |
| (**R60**)  | Mínimo | Técnico | Media |  |
| (**R61**)  | Mínimo | Técnico | Media |  |
| (**R62**)  | Mínimo | Técnico | Media |  |
| (**R63**)  | Mínimo | Técnico | Media |  |
| (**R64**)  | Mínimo | Técnico | Media |  |
| (**R65**)  | Mínimo | Técnico | Media |  |
| (**R66**)  | Mínimo | Técnico | Media |  |
| (**R67**)  | Mínimo | Técnico | Media |  |
| (**R68**)  | Mínimo | Técnico | Media |  |
