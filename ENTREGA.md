# Entrega del Trabajo Práctico Integrador

## Datos del participante
- Nombre y apellido: Luca Moizello
- Curso: Introducción a Git y GitHub para la Gestión de Proyectos Digitales
- Fecha de entrega: 2026-09-10

## Enlaces
- Repositorio de GitHub: https://github.com/lucamoizello26-ctrl/tp-integrador-git-moizello-luca
- Issue: https://github.com/lucamoizello26-ctrl/tp-integrador-git-moizello-luca/issues/1
- Pull request: https://github.com/lucamoizello26-ctrl/tp-integrador-git-moizello-luca/pull/2

## Comandos principales utilizados
- `git init`: Inicialización del repositorio local.
- `git status`: Verificación del estado de los archivos.
- `git add`: Preparación de cambios en el área de staging.
- `git commit`: Registro formal de los cambios en el historial.
- `git log --oneline`: Visualización resumida del historial de commits.
- `git remote add origin`: Vinculación del repositorio local con GitHub.
- `git remote -v`: Verificación de la URL del repositorio remoto.
- `git push`: Envío de cambios al repositorio remoto.
- `git branch`: Listado y verificación de ramas.
- `git switch` (o `git checkout`): Cambio entre ramas.
- `git merge`: Integración de ramas localmente.
- `git pull`: Sincronización de cambios desde el remoto hacia el local.

## Descripción del proceso
El desarrollo del proyecto inició con la creación y organización de la estructura local en Git Bash. Posteriormente, se inicializó el repositorio con `git init` y se registraron los commits de los archivos base (`README.md`, `ENTREGA.md`, `index.html` y `styles.css`). Luego, se publicó el proyecto en un repositorio público de GitHub y se creó una issue para planificar una mejora en la documentación. Finalmente, se creó una rama de trabajo `mejora-readme` para solventar dicha issue, enviando los cambios mediante una Pull Request que fue integrada satisfactoriamente.

## Dificultades encontradas
Al momento de enlazar el repositorio local con el remoto surgió una duda sobre el nombre de la rama principal (`main` vs `master`), la cual se solucionó asegurando el cambio de nombre mediante `git branch -M main` antes del primer push.

## Reflexión final
El uso de Git y GitHub permite mantener un control estricto de las versiones de un proyecto, facilitando el trabajo colaborativo de forma ordenada y la trazabilidad de cada cambio implementado.
