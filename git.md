# Git Cheatsheet

## Configuración
- **Configurar nombre de usuario**: `git config --global user.name "Tu Nombre"`
- **Configurar correo electrónico**: `git config --global user.email "tu@email.com"`
- **Configurar colorización línea de comando**: `git config --global color.ui auto`

## Creación de Repositorios
- **Inicializar un repositorio nuevo**: `git init`
- **Clonar un repositorio existente**: `git clone URL`

## Estado y Registro
- **Ver el estado de los archivos**: `git status`
- **Ver el historial de confirmaciones**: `git log`

## Operaciones Básicas
- **Añadir cambios al área de preparación**: `git add nombre_archivo`
- **Confirmar cambios**: `git commit -m "Mensaje del commit"`
- **Enviar cambios al repositorio remoto**: `git push`
- **Actualizar el repositorio local**: `git pull`

## Ramas (Branches)
- **Crear una nueva rama**: `git branch nombre_rama`
- **Cambiar a una rama específica**: `git checkout nombre_rama`
- **Crear y cambiar a una nueva rama**: `git checkout -b nombre_rama`
- **Eliminar una rama**: `git branch -d nombre_rama`

## Fusión (Merge)
- **Fusionar una rama en la rama actual**: `git merge nombre_rama`

## Deshacer Cambios
- **Deshacer cambios en un archivo específico**: `git checkout -- nombre_archivo`
- **Deshacer el último commit y mantener los cambios**: `git reset HEAD~1`
- **Deshacer el último commit y descartar los cambios**: `git reset --hard HEAD~1`

## Etiquetado (Tagging)
- **Crear un nuevo tag**: `git tag nombre_tag`
- **Crear un tag anotado con un mensaje**: `git tag -a nombre_tag -m "Mensaje del tag"`
- **Eliminar un tag**: `git tag -d nombre_tag`

## Ignorar Archivos
- **Ignorar archivos específicos**: Crear un archivo `.gitignore` y listar los archivos o patrones de archivos a ignorar.