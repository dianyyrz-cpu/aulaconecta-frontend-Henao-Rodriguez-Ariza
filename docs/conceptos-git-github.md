# Conceptos básicos de Git y GitHub

## ¿Qué es Git?

Git es un sistema de control de versiones que permite registrar los cambios realizados en un proyecto a lo largo del tiempo. Gracias a él, es posible recuperar versiones anteriores, trabajar de forma organizada y colaborar con otras personas sin perder información.

---

## ¿Qué es GitHub?

GitHub es una plataforma en la nube que utiliza Git para almacenar repositorios. Facilita el trabajo colaborativo, ya que permite compartir proyectos, administrar cambios, revisar código mediante Pull Requests y mantener un historial de todas las modificaciones realizadas.

---

## Diferencias entre Git y GitHub

| Git | GitHub |
|------|---------|
| Es un sistema de control de versiones. | Es una plataforma que aloja repositorios Git. |
| Funciona de manera local en el computador. | Funciona en la nube y permite compartir proyectos. |
| Registra el historial de cambios. | Facilita la colaboración entre varios desarrolladores. |
| Puede utilizarse sin conexión a Internet. | Requiere conexión para sincronizar los cambios con el repositorio remoto. |

---

## Conceptos importantes

### Repositorio

Es el espacio donde se almacenan todos los archivos de un proyecto junto con su historial de cambios. Puede encontrarse de forma local en un computador o alojado en plataformas como GitHub.

### Commit

Es un registro de los cambios realizados en el proyecto. Cada commit guarda una versión específica del trabajo y debe incluir un mensaje que describa claramente la modificación realizada.

### Rama (Branch)

Es una copia independiente de la línea principal de desarrollo. Permite trabajar en nuevas funciones o realizar cambios sin afectar directamente la rama principal del proyecto.

### Merge

Es el proceso mediante el cual se unen los cambios realizados en una rama con otra, normalmente integrando una rama de trabajo en la rama principal después de haber sido revisada.

### Pull Request

Es una solicitud para que los cambios realizados en una rama sean revisados antes de incorporarlos a otra rama. Facilita la colaboración y el control de calidad del proyecto.

### Fork

Es una copia de un repositorio que se crea en otra cuenta de GitHub. Se utiliza principalmente cuando se desea contribuir a proyectos de terceros sin modificar el repositorio original.

### Clone

Es una copia completa de un repositorio remoto en el computador local. Incluye todos los archivos y el historial de cambios del proyecto.

### Push

Es la acción de enviar los commits realizados en el repositorio local hacia el repositorio remoto en GitHub.

### Pull

Es la acción de descargar e integrar en el repositorio local los cambios realizados por otros colaboradores en el repositorio remoto.

### Conflicto

Ocurre cuando dos personas modifican la misma parte de un archivo y Git no puede decidir automáticamente cuál cambio conservar. En ese caso, el conflicto debe resolverse manualmente.

---

# Secuencia recomendada de trabajo

El equipo acordó seguir el siguiente flujo para desarrollar el proyecto:

1. Crear o clonar el repositorio.
2. Crear una rama para trabajar en una nueva tarea.
3. Realizar los cambios necesarios.
4. Preparar los archivos con `git add`.
5. Registrar los cambios mediante un commit con un mensaje descriptivo.
6. Enviar los cambios al repositorio remoto con `git push`.
7. Crear un Pull Request para solicitar la revisión.
8. Atender las observaciones realizadas por el revisor, si las hay.
9. Fusionar los cambios con la rama principal mediante un Merge.

---

# Riesgos que evita cada paso

| Paso | Riesgo que evita |
|------|------------------|
| Crear una rama | Evita modificar directamente la rama principal. |
| Realizar commits frecuentes | Reduce la pérdida de trabajo y facilita volver a versiones anteriores. |
| Enviar cambios con Push | Permite que todo el equipo tenga acceso a la versión más reciente. |
| Crear un Pull Request | Evita integrar cambios sin revisión previa. |
| Realizar la revisión | Ayuda a detectar errores antes de incorporarlos al proyecto. |
| Hacer Merge únicamente después de aprobar la revisión | Mantiene la estabilidad de la rama principal. |

---

# Conclusión

Git y GitHub son herramientas fundamentales para el desarrollo colaborativo de software. Su uso permite organizar el trabajo del equipo, mantener un historial de cambios, reducir errores y facilitar la integración de nuevas funcionalidades de forma segura y ordenada.
