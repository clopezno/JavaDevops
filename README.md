# JavaDevops
Tareas para crear proyectos Java con buenas prácticas ágiles  Devops con la funcionalidad actions de Github . Maven, cobertura de pruebas, sonarqube.
## Gestion de tareas y flujo de trabajo una rama por tarea en Git hub
- Crear la tarea: título, descripción, asignación a un proyecto junto con su estado "backllog" y estimación temporal e iteración
- Cambiar estado de la tarea en el proyecto "in progress"
- Crear una rama por tarea y configurar el repositorio local para trabajar con la rama remota (fecth, checkout)
- Realizar los cambios en los ficheros del repositorio implicados (commit) en dicha tarea indicando el identificador de la tareas #1
- Cuando esten  realizados todo los cambios (push)
- Cambiar el estado de la tarea a "ready"
- Crear un pullrequest
- Cambiar el estado de la tarea a "In review"
- Revisar  los cambios del pullrequest e integrarlos en la rama principal
- Cerrar la tarea y pasarla a estdo "Done"
  ## Configurar un proceso de desarrollo con Maven
  Definir un proceso de desarrollo de proyectos Java con:
- Estructura estándar de directorios
- Definir pom.xml  para la compilación java 17, pruebas Junit 5 y empaquetado de aplicación Java .jar

