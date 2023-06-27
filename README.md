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
