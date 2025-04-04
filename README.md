 ```
  ____  _     _                           
/ ___|(_)___| |_ ___ _ __ ___   __ _ ___    ____  _       _ _        _           
\___ \| / __| __/ _ \ '_ ` _ \ / _` / __|  |  _ \(_) __ _(_) |_ __ _| | ___  ___ 
  ___) | \__ \ ||  __/ | | | | | (_| \__ \  | | | | |/ _` | | __/ _` | |/ _ \/ __|
|____/|_|___/\__\___|_| |_| |_|\__,_|___/  | |_| | | (_| | | || (_| | |  __/\__ \
                                            |____/|_|\__, |_|\__\__,_|_|\___||___/
                                                    |___/                        
```
## El repo está discontinuado.
## No estoy manteniéndolo, pero si tenés ganas de revivirlo avisame.
## Suerte `(-_-)/`



## Las guías resueltas:

Las guías resueltas:
En cada directorio i-guia vas a encontrar el archivo i-sol.pdf que no es otra cosa que la última actualización de la guía i-ésima.
*Sin necesidad de compilar nada*.
Los archivos son largos como para andar scrolleando todo el tiempo, *usá los links*, que para algo los puse.
Así que en el índice, pie de página y referencias podés hacer doble click para saltar y algún que otro _easter egg_.

_¡Una estrellita 🌟 al repo es siempre bienvenida! (^_^)/_

# Idea
Si bien hay muchos buenos apuntes por ahí. La idea es que en este repo haya un apunte _dinámico_, uno que se pueda
ir curando y modificando junto con las guías de nuevos cuatrimestres. Vas a tener que laburar!
Un apunte con sección _ejercicios de parciales_ que vaya creciendo y mejorando cuatrimestre a cuatrimestre,
_curados y escritos por los alumnos_.

¡Esto está para que cualquier individuo, con ganas de contribuir, pueda hacerlo!

## Estructura del repo

- En los directorios `i-guia`:
  - `i-sol.pdf`: PDF con los ejercicios correspondientes a los temas de la guía _i-ésima_. El que seguramente estás buscando, a menos que quieras contribuir.
  - `i-sol.tex`: Archivo que se debe compilar para obtener el archivo `i-sol.pdf` que uno quiera ver. En este se inyecta todo el código que está en los directorios, `teoria-i`, `ejercicios-i`, `ejercicios-i-extra`
  - directorio `teoria-i`: Contiene a `teoria-i.tex`
  - directorio `ejercicios-i`: Contiene los ejercicios de la _i-ésima_ guía. Se nombran `ej-j-i.tex` con `j`, el número del ejercicio e `i` el de la guía.
  - (proximamente) directorio `ejercicios-i-extra`: Contiene los ejercicios extras, de clase y/o parciales de los temas de la _i-ésima_ guía. Se nombran `ej-extra-j-i.tex` con `j`, el número del ejercicio e `i` el de la guía.

- En la carpeta `macros`:
  - Ahí están los archivos necesarios para compilar los ejercicios.
    - `preamble-general.tex`: El preambulo con los paquetes necesarios para los comandos usados. -`indice.tex`: El índice, código para generar los links dentro del pdf y saltar directo a los ejercicios mejorando la navegación de los pdf.
    - `definiciones.tex`: Las definiciones, macros para que los comandos de LaTeX sean un poco más agradables y se pueda leer el código en leguaje _más natural_.
    - `encabezado-pie.tex`: Encabezado y pie de página, para darle un poco de 🌠bling-bling 🌠 al apunte y mejor navegación
    - `estructura-ejercicio.tex`: Donde se inyectan los ejercicios dándoloe la estructura que tiene cada PDF.
    - ... y otras yerbas

## Contribuir

Si querés contribuir no hace falta codear ni saber LaTeX, podés marcar algún error que pueda haber en un ejercicio por ejemplo.
Ahí podés comentarnos por el grupo de Telegram o mail así lo solucionamos y aumentamos la calidad del trabajo. Si sabés un poco de LaTeX, ya vas a estar bien, porque hay muchísimos ejercicios con los comandos para que copies y pegues.

_Para contribuir al código directamente tenés que:_

 - Tener instalado Git
 - Tener instalado LaTeX
 - Tener cuenta de GitHub
 - Metete en el grupo de Telegram si necesitás ayuda con alguno de esos pasos. La idea es que te capacites para poder vos también mantener el repo vivo y actualizado.

## Compilar
Para compilar los archivos de LaTeX una vez que fueron modificados:

 - Con la terminal, entrar a la carpeta de la guía que quieras compilar, por ejemplo la guía 1.
```bash
$ cd sistemasDigitales/1-guia/
$ pdflatex 1-sol.tex
```

Eso debería actualizar el archivo 1-sol.pdf con los cambios 
que hubieras realizado. [grupo de Telegram](https://t.me/+X4p0xKnXp0Y3ZThh)Luego tenés que hacer una pull request para actualizar el repositorio con tu aporte!


 - Metete en el [grupo de Telegram](https://t.me/+X4p0xKnXp0Y3ZThh) si necesitás ayuda con alguno de esos pasos. La idea es que te capacites para poder vos también mantener el repo vivo y actualizado, porque yo ya hice mi parte y me da paja mantener esto sin ayuda.
Podés usar el código como quieras siguiendo esta licencia: [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

Este es el _apunte único_
_"Un Apunte para gobernarlos a todos, un Apunte para encontrarlos, Un Apunte para atraerlos a todos y atarlos en las tinieblas"_

¡Una estrellita 🌟 al repo es siempre bienvenida! (^_^)/
