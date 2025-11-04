# Contenidos

- Introducción
- Quick start
- Aprendiendo a referenciar revisiones y paths
- Git internals
- Herramientas para preparar un buen commit en cualquier situación
- Reescribiendo la historia
- Trabajando en paralelo
- Utilidades
- Configuración de git. hooks
- Sub-proyectos
- Integración con otras herramientas y entornos
- Buenas prácticas

1. INTRODUCCIÓN

   - Qué es un SCV y qué un SCV distribuido
   - Historia de GIT: C, kernel Linux, contexto (SVN, Mercurial, ...)
   - Anatomía de un SCV distribuido | diferencias/parecidos con centralizados
   - Instalación en Windows
   - CheatSheets y Libros recomendados

2. QUICK START

   - Primer repo (init), primer commit
   - Configuración inicial: email y name
   - add/commit y status/log/show
   - Mensajes de commit
   - Anatomía de un repositorio git: staging area, index and cache

3. APRENDIENDO A REFERENCIAR REVISIONES Y PATHS

   - Anatomía de comandos típicos, referencias VS paths
   - HEAD, master, HEAD~1 y otras referencias útiles (tags)
   - Números de commit: SHA1, sub-cadena de SHA1
   - Nombres de tags, de heads y de branches
   - Referencias por mensaje de commit (:/cadena)

   ADD. Git internals

   - Plumbing commands
   - Objetos: blobs, trees, commits, tags

4. HERRAMIENTAS PARA PREPARAR UN BUEN COMMIT EN CUALQUIER SITUACIÓN

   - git add p
   - git rm, git mv
   - git diff
   - git blame | git log string
   - .gitignore

5. REESCRIBIENDO LA HISTORIA

   - amend
   - checkout
   - reset
   - stash
   - git clean n | git clean f
   - revert
   - rebase
   - git bisect

6. TRABAJANDO EN PARALELO

   - branches
     - Crear, borrar, intercambiar
     - Crear desde ref (git checkout b mybranch master~1)
   - tags
     - Crear, usar
   - patches
     - Crear, aplicar
   - remotes:
     - remote v
     - push/pull
     - clones
     - repos bare
     - push branch, push tag
   - Resolución de conflictos
   - merge VS rebase VS cherrypick
   - Pull Request
     - Creación
     - Uso
     - Merging
     - Cierre

7. UTILIDADES

   - GitK, GitG y git gui | git log graph | formato git log
   - IntelliJ

8. CONFIGURACIÓN DE GIT. Hooks

   - .alias
   - gitconfig
     - Editor
     - Coloreado comandos
     - Formato salida comandos
     - Otras opciones
   - Hooks
     - Cómo crear
     - hooks de lado cliente: commits, emails, rebase, ...
     - hooks de lado servidor: prereceive, postreceive, update

9. SUB-PROYECTOS

   - Crear submodules
   - workflow de commits
   - git submodule status recursive
   - git submodule foreach ...

10. INTEGRACIÓN CON OTRAS HERRAMIENTAS Y ENTORNOS

    - SourceTree
    - Github
    - GitLab
    - Bitbucket

11. BUENAS PRÁCTICAS

    - Commits atómicos
    - Commits frecuentes
    - No commits de trabajo a medias
    - Test antes de commit
    - Buenos mensajes de commit
    - Usar branches, feature-branching
    - Workflows
      - Presentar las opciones más usadas
      - Fijar un workflow común
