# Flujo de trabajo del equipo

## Objetivo

Definir una forma de trabajo organizada para que todos los integrantes puedan colaborar en el proyecto sin sobrescribir los cambios de los demás.

---

# Flujo de trabajo acordado

El equipo trabajará siguiendo los siguientes pasos:

1. El responsable del repositorio crea el repositorio en GitHub.
2. Se agregan los colaboradores al repositorio.
3. Cada nueva tarea se desarrolla en una rama independiente.
4. El integrante responsable realiza los cambios correspondientes.
5. Los cambios se guardan mediante commits con mensajes descriptivos.
6. Los cambios se envían al repositorio remoto.
7. Se crea un Pull Request para solicitar la revisión.
8. El revisor analiza los cambios y realiza observaciones si es necesario.
9. El responsable atiende las observaciones y realiza las correcciones.
10. Una vez aprobados los cambios, se realiza el Merge hacia la rama principal (`main`).

---

# Roles del equipo

| Integrante | Usuario de GitHub | Rol |
|------------|-------------------|--------------------------------|
| Diana Rodríguez | dianyyrz-cpu | Responsable del repositorio |
| Juan Henao | DonJuan4-6 | Responsable de la rama |
| Juan Ariza | JunssAriza | Revisor |

---

# Comandos de Git utilizados

| Comando | Función |
|----------|---------|
| `git clone` | Copia el repositorio remoto al computador. |
| `git branch` | Crea o muestra las ramas del proyecto. |
| `git switch` | Cambia de una rama a otra. |
| `git add` | Prepara los archivos para el siguiente commit. |
| `git commit -m` | Guarda los cambios en el historial del proyecto. |
| `git push` | Envía los cambios al repositorio remoto. |
| `git pull` | Descarga e integra los cambios del repositorio remoto. |

---

# Buenas prácticas acordadas

- No realizar cambios directamente sobre la rama `main`.
- Escribir mensajes de commit claros y descriptivos.
- Mantener la documentación actualizada.
- Revisar los cambios antes de aprobar un Pull Request.
- Resolver las observaciones antes de fusionar los cambios.
- Trabajar siempre sobre la versión más reciente del proyecto.

---

# Posibles riesgos y cómo prevenirlos

| Riesgo | Medida preventiva |
|---------|-------------------|
| Sobrescribir el trabajo de otro integrante. | Trabajar en ramas independientes. |
| Perder información. | Realizar commits frecuentes. |
| Integrar errores al proyecto. | Revisar los cambios mediante Pull Request. |
| Conflictos entre versiones. | Sincronizar el repositorio antes de comenzar a trabajar. |

---

# Conclusión

El flujo de trabajo acordado permite que los integrantes colaboren de manera organizada, manteniendo un historial de cambios claro y reduciendo el riesgo de errores durante el desarrollo del proyecto.


# Registro de Comandos
git commit	¿Qué nodo nuevo apareció y dónde quedó apuntando la rama?
Apareció un nuevo nodo (commit) en el historial y la rama actual pasó a apuntar a ese nuevo commit, convirtiéndose en el más reciente.

git branch	¿Qué se creó y sobre qué commit quedó ubicado?
Se creó una nueva rama que quedó ubicada sobre el commit en el que se encontraba HEAD en ese momento, apuntando inicialmente al mismo nodo que la rama actual.

git checkout	¿Qué cambió al moverse a otra rama?	
Cambió la rama activa y HEAD pasó a apuntar a la rama seleccionada, permitiendo trabajar sobre ella sin modificar las demás ramas.

git merge	¿Qué historias de trabajo quedaron integradas?	
Se integraron los cambios de la rama que se estaba fusionando con la rama actual, fusionando el historial y las modificaciones de ambas ramas.
