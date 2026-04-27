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

## Lister ramas locales y remotas

```sh
git branch -a
```

## Otra manera de hacer run commit

    1. Muevo los archivos al staging area
    ```sh
    git add <nombre/archivo>
    ```
    2. Hago un commit

    ```sh
    git commit # Eso abre el nano/vim/vsc para que escribamos el mensaje
    ```
    3. Una vez escrito el mensaje paraconfirmar

    Ctrl + O + Enter (guardar) | Ctrl + X.
    
    
## Creando una rama(Creando una bifurcacion)

```sh
#primera alternativa
git branch feature/ramas #crear una rama
git switch feature/ramas #Me muevo a la rama que indico
# segunda alternativa
git switch -c feature/ramas #crear una rama y moverse a esa rama 
```