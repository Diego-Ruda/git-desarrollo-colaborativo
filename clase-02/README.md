# Clase 02 - Git Desarrollo Colaborativo

## .gitignore
Me permite indicar los archivos o carpetas que quiero que no formen parte del repositorio. Por ejemplo archivos de log durante desarroll. archivos temporales, variables de entorno etc.

**Se crea el archivo .gitignore dentro de la raiz del proyecto.**

## .gitkeep
Ayuda a git a versionar carpetas que quiero que sean parte del repositorio pero estan vacias.

**Se crea el archivo .hitkeep dentro de la carpeta que quiero que git versione**

# RAMAS (BRANCHES)

Las ramas me permiten trabajar en diferentes partes del proyecto de manera auxiliar sin afectar las funcionalidad (codigo fuente que ya funciona)

### Lister ramas locales

```sh
git branch
```

## Lister ramas remotas

```sh
git branch -a
```