# Curso de GIT AF 82946 – Grupo 85339

- Duración: 20 horas
- Modalidad: On-line
- Fechas: L-03/11/2025 - V-07/11/2025
- Horario: Días 3, 4, 6 y 7 Noviembre 9:00 – 13:30 / Día 5 Noviembre 9:00 – 11:00
- Horario 9:30 – 14:30 hs.

Formador: Alejandro Cerezo
<alce65@hotmail.es>

## Contenidos

- Introducción
- Quick Start
- Aprendiendo a referenciar revisiones y paths
- Herramientas para preparar un buen commit en cualquier situación
- Rescribiendo la historia
- Trabajando en paralelo
- Utilidades
- Configuracion de git
- Subproyectos
- Integración con otras herramientas y entornos
- Buenas prácticas

Desarrollo del curso en la carpeta Oficial -> [repo](https://github.com/IconoTC/GIT-AF-82946-Grupo-85339)

## Desarrollo del curso

### Día 1 (Lunes 3 noviembre 2025)

- Presentación profesor / alumnos
- Introducción: Qué es un SCV y qué un SCV distribuido
- IDE / Editor de código: Visual Studio Code (VSC)
- Instalación de Git
- Terminales
  Configuración inicial
  - Nombre de usuario y correo electrónico
- Primeros pasos con Git

  - Primer repo (init), primer commit: .gitignore / readme.md
  - Anatomía de un repositorio git: working directory, staging area (index o cache) y repositorio (.git)
  - Estados de un archivo: untracked (U), tracked (modified (M), staged (A), committed)

- [Descanso]

- Primeros pasos con Git (2)

  - add/commit/reset y status/log/show - GitGraph
  - Mensajes de commit

- Anatomía de comandos típicos, referencias VS paths

  - HEAD, master, HEAD~1 y otras referencias útiles
  - Referencias por mensaje de commit (:/cadena)

- Integración con otras herramientas y entornos
  - Clientes gráficos
  - Entornos de desarrollo
  - Repositorios remotos: GitHub, GitLab, Bitbucket
    - remotes -> push / pull
    - Clonar un repositorio: clone
- Comprobar el repositorio.
  - git log
  - git show
  - git diff
- Aliases
  - Qué son
  - Cómo crearlos desde el CLI: `git config --global alias.ch checkout`
  - Crearlos editando el fichero de configuración: `git config --global -e`

### Día 2 (Martes 4 noviembre 2025)

- Ficheros Markdown

  - Qué son
  - Sintaxis básica
  - Vista previa en VSC / GitHub / GitLab

- Git internals

  - Estructura de un repositorio git: .git
  - Objetos git: blobs, trees, commits (y tags)
    - Creación y lectura de objetos
    - Creación del árbol de objetos en un primer commit
    - Modificación del árbol de objetos en commits sucesivos
  - Referencias: heads, ramas (tags y remotes)
  - Taller: creación de un repositorio git "a mano"

- [Descanso]

- Herramientas para preparar un buen commit en cualquier situación

  - Operaciones en la Staging Area (Index)
    - Añadir ficheros
    - Eliminar de la Staging Area (Index)
    - Preparar un commit parcial: git add -p
  - Eliminar ficheros: git rm
    - Problemas con .gitignore
  - Cambiar nombre de ficheros: git mv
  - git blame
  - Recapitulando: Git básico

  - Reescribiendo la historia
    - Advertencia
    - git command --amend
      - Ref logs
    - git checkout y git reset (introducción)

<!--
### Día 3 (Miércoles 5 noviembre 2025) - hasta las 11:00

- Reescribiendo la historia (2)
  - git checkout
  - git reset
  - Evolución de git checkout: Nuevos comandos git switch y git restore
    - git checkout a nivel de archivo (restore)
    - git reset a nivel de archivo
  - rebase interactivo
    - edit: modificando un commit
    - squash y fixup: fusionando commits
    - drop: eliminando un commit
- Otros comandos

  - git clean
  - git revert
  - git bisect

- Trabajando en paralelo (?)

  - Ramas
    - Crear y seleccionar
      - Crear desde referencia
    - Ver ramas
    - Borrar ramas
    - Mover y renombrar ramas
  - git stash
 -->

<!--
### Día 4 (Jueves 6 noviembre 2025)

- Trabajando en paralelo (2)
- - Combinación de ramas: Merge y Rebase
    - git merge
      - fast-forward
      - three-way merge
    - git rebase
  - Resolución de conflictos

  - git cherry-pick
  - Patches
    - Creación
    - Aplicación

- Etiquetas (tags)

  - Tags anotadas y tags ligeros
  - Crear, listar, eliminar

- Worktrees
-
- [Descanso]

- Repositorios remotos

  - Repositorios "bare"
  - Clonar repositorios: git clone
  - git remote
  - git push
    - push tags
  - git pull

    - git fetch
    - git merge / git rebase
    - Conflictos

  - Ramas remotas
    - Seguimiento de ramas remotas (tracking branches)
    - Crear ramas locales a partir de ramas remotas: fetch + checkout / switch -c
    - Subir ramas locales a ramas remotas: -u
    - Eliminar ramas remotas
  - Pull requests (GitHub) / Merge requests (GitLab)
    - Flujo de trabajo típico
    - Revisión de código
-->

<!--
### Día 5 (Viernes 7 noviembre 2025)

  - Pull requests (GitHub) / Merge requests (GitLab)
    - Resolución de conflictos en remoto
    - Buenas prácticas:
      - Actualizar la rama con la rama main antes de hacer el merge
      - Resolución de conflictos en local
      - Eliminar la rama una vez hecho el merge

- Flujos de trabajo (workflows)

  - Git Flow
  - GitLab Flow
  - GitHub Flow
    - Ship-Show-Ask

- Buenas prácticas

(Probablemente haya que reducir esta parte)

- GitHub
  - Hosting de Repositorios
    - repositorios públicos y privados; ramas y remotos: push y pull (v.s.)
    - forks
  - Colaboración
    - pull requests: revisión de código y comentarios (v.s.)
    - PR desde ramas y forks
    - Proyectos
      - Tableros (Boards)
      - issues y proyectos; milestones
    - Wikis
    - Gists
  - GitHub CLI
  - GitHub Pages
    - Configuración y uso

- [Descanso]

- GitHub (continuación)
  - GitHub Pages
    - Práctica: publicar una web estática generada con Astro
  - Releases
- Integración continua / Entrega continua (CI/CD)

  - GitHub Actions
    - Introducción
    - Workflow. Partes y sintaxis
    - Configuración y ejecución de un workflow
    - Ejemplo de CI (build y test) de una aplicación JS

(Probablemente haya que reducir esta parte)

- Integración continua / Entrega continua (CI/CD)
  - GitHub Actions (continuación)
    - CD: despliegues
      - Secretos
      - Despliegue en GitHub Pages
    - CD: despliegues de Astro en GitHub Pages
-->
