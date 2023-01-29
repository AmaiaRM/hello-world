# hello-world

Un repositorio para empezar a usar Github y Github Actions con Java

## ¿Como probar en el cloud?

[![](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/gitt-3-pat/hello-world)

## Comandos git básicos

```
git clone https://github.com/gitt-3-pat/hello-world
git status
git add .
git commit -m "TU MENSAJE"
git push

git checkout -b feature/1
git checkout main
```

## Referencias

- https://git-scm.com/

Git clone:
Como su nombre indica, este comando clona el repositorio al que apunta en un nuevo directorio local. De esta forma, todo el contenido el repositorio previamente “forkeado” y remoto se copiará en el directorio /tmp de nuestro equipo local.
 

Git status:
Comprueba el estado actual del directorio en el que se trabaja. Permite observar los cambios que se han realizado (creación de archivos) e informa sobre la falta de confirmación de archivos modificados.
 

Git add:
Añade el archivo especificado (sobre el que se ha realizado alguna modificación) al área de preparación. Los cambios se guardan en un “borrador” y no se registran en el directorio hasta que se ejecuta la confirmación definitiva con git commit.(Se pueden añadir todos los cambios con “gitt add .”.)
 

Git commit:
Registra todos los cambios realizados y guardados en el área de preparación (borrador) en el repositorio de trabajo.
 

Git push:
Se carga el contenido desde el directorio local sobre el que se trabaja al directorio remoto de tal forma que el resto de usuarios puedan observar las modificaciones hechas sobre el repositorio.
 

En definitiva, los cambios en GitHub funcionan en 3 pasos:
-	Git add: se añaden como borrador en el repositorio local
-	Git commit: se confirma el borrador y se registran dichos cambios en el repositorio local
-	Git push: se cargan los cambios desde el repositorio local al repositorio remoto

Git checkout:
Permite desplazarte entre las diferentes versiones de código de un repositorio, tanto entre ramas como archivos y confirmaciones. Una de las ventajas de Git es el desarrollo mediante ramas. Si se desea probar cambios o intentar solucionar errores, se genera una nueva rama para alojarlos de tal forma que el “código prueba” no desestabilice el principal. Y “git checkout” permite desplazarte sobre estas ramas creadas.
 
Otro comando interesante es “git branch” que indica la rama sobre la que se está trabajando. En nuestro caso, como no hemos creado ninguna rama extra, seguimos sobre la principal.


(se incluyen capturas de los logs en el archvo pdf pr1_amaia)
 

