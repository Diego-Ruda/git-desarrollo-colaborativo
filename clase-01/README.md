# Clase 01 - Git Desarrollo Colaborativo

## Crear un repositorio de GIT

```sh
git init
```

## Configurar por primera vez y unica a GIT

```sh
git config --global user.name "Diego Ruda"
git config --global user.email "diegorudaamd18@gmail.com"
```

## Listar configuraciones git para verificar si tengo o no esto configurado

```sh
git config --list
```
## Cambiar de aca en adelante como se va a llamar la rama principal por defecto

```sh
git config --global init.defaultBrach main
```

# Para pasar del workin directory al staging are (index)

```sh
git add <nombre-archivo>
git add README.md
```

## como ver el estado del archivo y en que area esta

```sh
git status
```

## Para pasar del stanging area al local repo

```sh
git commit -m "mensaje descriptivo"
```

## Como ver la lista de commits

```sh
git log # version larga
git log --oneline # version corta
```