# comanditos_denuevo

## aca voy a guardar los comandos basicos de github

---

# Comanditos

## Comandos de la compu

```bash
cd carpeta # para cambiar de carpetas
cd #para cambiar a la carpeta raiz de la pc (/home/fjalampidis)
cd - # para cambiar a la carpeta donde estabas antes
```

```bash
ls # para enlistar los archivos y carpetas
ls -a # para enlistar los archivos y carpetas includas las ocultas (son las que tienen un punto adelante, ej .git)
```

```bash
pwd # para ver en que carpeta estoy
```

```bash
rm archivo # para eliminar un archivo
rm -r carpeta # para eliminar una carpeta
```

```bash
code . # para abrir en visual studio code la caperta actual

code nombrearchivo # para abrir un archivo en especifico en vsc

code .. #para abrir la carpeta anterior en vsc
```

```bash
touch archivo # para crear un archivo
mkdir carpeta # para crear una carpeta
```

```bash
sudo cualquier-comando-de-arriba # para ejecutar como administrador
```

## Comandos de git

```bash
git init # iniciar un repositorio en la carpeta en donde estas
```

```bash
git status # muestra el estado acutal del repositorio
```

- Esta el _repositorio local_ (el que esta en tu computadora) y esta el _repositorio remoto_ (el que esta en github)

```bash
git clone link-del-repositorio # para clonar/descargar un repositorio de github
```

```bash
git add archivo # agrega archivos para que git observe si cambio o no el archivo. Tambien agrega cualquier cambio para cuando hagas un commit.
```

- commit en espanol es confirmacion. Es una version del codigo.

```bash
git commit -m "titulo o mensaje del commit (la version) del codigo"
```

```bash
git push # para subir los cambios a github
```

```bash
git branch # permite ver todas las ramas que hay en el repositorio local
```

```bash
git checkout -b "nombre-de-la-rama" # para crear una rama y moverte a ella
```

```bash
git log --oneline #para ver el historial de commits en el repositorio actual. --oneline muestra un resumen de commit
```

```bash
git push --set-upstream origin ramita # paa subir los cambios de una rama nueva. Este comando se usa solamente cuando se crea una rama, el resto de veces utilizar git push
```

```bash
git switch main # para cambiar de rama solamente
```

```bash
git pull # para actualizar los cambios de github
```
