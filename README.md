# Java Bootcamp
## Desafío 1
### Ejercicio 1

**Para este ejercicio se realizaron los siguientes pasos:**

1. Se creó un directorio local con el nombre javabootcamp_desafio1 y se cambió al mismo:
```sh 
mkdir javabootcamp_desafio1 && cd javabootcamp_desafio1
```
2. Se inicializó el repositorio local:
```sh 
git init
```

3. Se cambió el autor y el email a utilizar para el repositorio (dado que no se desea que coincida con el resto de los repositorios):

```sh 
git config --local user.name "Matias"
git config --local user.email "matiterativo@gmail.com"
```

4. Se creó un nuevo archivo llamado README.md:
```sh 
touch README.md
```

5. Se agregó el archivo al stage area y se hizo el primer commit en un solo paso utilizando el modificador -a:
```sh 
git commit -am "Commit inicial: agrega archivo README.md"
```

Con los pasos anteriores se finaliza el Ejercicio 1.

**Para subir los cambios al repositorio remoto se siguieron los siguientes pasos:**

1. Se creó un nuevo repositorio remoto con nombre "javabootcamp_desafio1"

2. Se modificó el nombre de la rama "master" del repositorio local a "main" (utilizada por convención como rama principal en GitHub):
```sh 
git branch -M main
```

3. Se agregó el respositorio remoto creado con la referencia "origin":
```sh
git remote add origin git@github.com:Matiterativo/javabootcamp_desafio1.git
```

4. Se subió la rama main local al repositorio remoto:

```sh
git push origin main
```
***

### Ejercicio 2

**Para este ejercicio se realizaron los siguiente pasos:**

1. Se creó una rama con nombre "ejercicio_2" a partir de la rama "main" y se cambió a la misma:
```sh
git brach ejercicio_2 && git checkout ejercicio_2
```

2. Se modificó el archivo README.md con el contenido actual, explicando la resolución paso a paso del desafío 1 (tanto ejercicio 1 como ejercicio 2)

2. Se hizo un commit en la rama "ejercicio_2":

```sh 
git commit -am "Agrega explicación de resolución del desafío 1, ejercicio 1 y 2"
```

3. Se cambió a la rama "main" y se hizo un merge de la rama "ejercicio_2"

```sh 
git checkout main && git merge ejercicio_2
```

Con los pasos anteriores se finaliza el Ejercicio 1.

Posteriormente se subieron los cambios al repositorio remoto:

```sh 
git push origin main
```
***

Dado que se requiere la entrega de un archivo con el log actual del proyecto, se corre el siguiente comando y se sube el archivo resultante a la carpeta compartida proporcionada:

```sh 
git log --oneline > log_2611023.txt
```
