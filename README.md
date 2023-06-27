# Learn Git and GitHub From Zero

## Aprende Git &amp; GitHub desde 0

# Qué es Git 

* Git es un sistema de control de versiones que se utiliza para el seguimiento de cambios en archivos.
* Es una herramienta fundamental en el desarrollo de software colaborativo.

# Conceptos 

# Repositorio  

Es un espacio donde se guardan todos los archivos y la historia de cambios del proyecto

## Repositorio local

En tu propia máquina 

## Repositorio remoto 

En un servidor

# Comando para crear un nuevo repositorio

```
git init
```

# Commit 

### Es un conjunto de cambios realizados en el repositorio en un momento específico.
### Cada commit tiene un identificador único y guarda información sobre quién hizo el cambio, cuándo se hizo y qué archivos se modificaron


# Ramas (Branches)

### Es una línea de desarrollo que permite trabajar en funcionalidades o correcciones de errores sin afectar la rama principal **(main o master)**

# Etiquetas (Tags): 

## Sirven para marcar versiones o hitos importantes en el desarrollo del proyecto
## Las etiquetas son inmutables y proporcionan una referencia fácil de usar para acceder a versiones específicas

# Comando para crear una etiqueta

```
git tag
```

# Comandos 

# Clonar un repositorio

```
git clone <url>
```

# Añadir un archivo específico al área de preparación (staging area)

```
git add <archivo>
```

# Añadir todos los archivos modificados al área de preparación (staging area)

```
git add .
```

# Crear un nuevo commit con los cambios en el área de preparación

```
git commit -m "<mensaje>"
```

# Ver el estado actual del repositorio, incluyendo los archivos modificados, los archivos en el área de preparación y los commits pendientes de enviar

```
git status
```

# Obtener los últimos cambios del repositorio remoto 

```
git pull
```

# Envía tus commits locales al repositorio remoto

```
git push
```

# Muestra una lista de las ramas existentes en el repositorio. La rama activa se muestra resaltada

```
git branch
```

# Cambiar de rama

```
git checkout <rama>
```

# Crear rama

```
git checkout -b nueva-rama
```

# Ver registro de los commits realizados en el repositorio

```
git log
```

# Agrega un nuevo repositorio remoto

```
git remote add <url>
```


#  Comandos avanzados

# Eliminar una rama local después de fusionar los cambios en otra rama

```
git branch -d <rama>
```

# Eliminar una rama local incluso si no se han fusionado todos los cambios en otra rama
```
git branch -D <rama>
```

# Guarda temporalmente los cambios locales sin realizar un commit
```
git stash
```

# Ver lista de los stash existentes en el repositorio
```
git stash list
```
# Aplica el stash más reciente y restaura los cambios guardados en el directorio de trabajo actual
```
git stash apply
```

# Aplica el stash más reciente y elimina automáticamente el stash
```
git stash pop
```

#  Aplica los cambios de un commit específico a la rama actual
```
git cherry-pick <commit>
```

# Reescribe el historial de commits para que parezca que la rama actual se ha bifurcado desde la rama especificada en lugar del punto de bifurcación original
```
git rebase <rama>
```

# Deshace los commits posteriores al commit especificado, conservando los cambios en el área de preparación
```
git reset <commit>
```

# Obtiene los últimos cambios del repositorio remoto sin fusionarlos automáticamente
```
git fetch
```

# Muestra las diferencias entre los cambios realizados y el estado actual del repositorio
```
git diff
```

# Muestra quién modificó cada línea de un archivo y en qué commit se realizó el cambio
```
git blame <archivo>
```

# Permite realizar una búsqueda binaria para encontrar el commit que introdujo un bug.
```
git bisect
```

# Muestra un registro detallado de las referencias de Git, incluyendo los cambios de rama y los cambios de HEAD
```
git reflog
```

# Permite trabajar con submódulos, que son repositorios Git dentro de otro repositorio Git.
```
git submodule
```

# Crea un nuevo commit que revierte los cambios introducidos por un commit específico.
```
git revert <commit>
```
