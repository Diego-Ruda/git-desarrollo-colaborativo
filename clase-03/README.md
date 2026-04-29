# Clase 03 - Bit desarrollo colaborativo

## Borrado una rama
`
```sh
git branch -d <nombre-de-la-rama> # Si la rama ya esta en alguna otra rama fusionada
git branch -D <nombre-de-la-rama> #Fuerzo el borrado a pesar de que el contenido de esa rama no este en otro lado
```

## Clonado de un repositorio 
Si quiero que la carpeta .git exista en mi local, necesito clonar el repositorio

```sh
git clone <link github>
```

# Arreglar un mensaje de commit o agregar en un commit un archivo que me olvide

```sh
git commit --amend -m "mensaje descriptivo"
```

# Trabajando colaborativamente
Una perosna va a tener que crear el repositotio y agregar a todos los colaboradores en ese repositorio

## Trear la metadata (actualizar la carpeta .git)

```sh
git fetch
```

## Traer metadata y cambios

```sh
git pull
git pull origin maxi
```

## Ver ramas locales y remotas

```sh
git branch -av
```

# Alias en git

```sh
git config --global alias.l "log --oneline"
git config --global alias.s "status --short"
git config --global alias.c "commit -m"
git config --global alias.ll "log --oneline --decorate --all --graph"
```

# Git Resets
Es una fomra de borrar commits, tengo 3 tipos de resets

## Resets Soft
En este caso si hago un resets de tipo soft los cambios que estan dentro del commits pasan a la area de staging area

```sh
git reset --soft <numero-hash>
```
## Resets mixed (Default)
En este caso si hago un resets de tipo mixed (default) los cambios que estan dentro del  commits pasan al working directory

```sh
git reset --mixed <numero-hash>
git reset <numero-hash>
```

## Resets Hard (Destructivo)
En este caso si hago un resets de tipo hard los cambios que estan dentro del commits se pierden los cmabios

```sh
git reset --hard <numero-hash>
```