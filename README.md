 ```
  ____  _     _                           
/ ___|(_)___| |_ ___ _ __ ___   __ _ ___    ____  _       _ _        _           
\___ \| / __| __/ _ \ '_ ` _ \ / _` / __|  |  _ \(_) __ _(_) |_ __ _| | ___  ___ 
  ___) | \__ \ ||  __/ | | | | | (_| \__ \  | | | | |/ _` | | __/ _` | |/ _ \/ __|
|____/|_|___/\__\___|_| |_| |_|\__,_|___/  | |_| | | (_| | | || (_| | |  __/\__ \
                                            |____/|_|\__, |_|\__\__,_|_|\___||___/
                                                    |___/                        
```

## Las guías resueltas:

Las guías resueltas:
En cada directorio i-guia vas a encontrar el archivo i-sol.pdf que no es otra cosa que la última actualización de la guía i-ésima. Sin necesidad de compilar nada. Los archivos son largos como para andar scrolleando todo el tiempo, usá los links, que para algo los puse. Así que en el índice, pie de página y referencias podés hacer doble click para saltar y algún que otro easter egg.

¡Una estrellita 🌟 al repo es siempre bienvenida! (^_^)/

Idea
Si bien hay muchos buenos apuntes por ahí. La idea es que en este repo haya un apunte dinámico, uno que se pueda ir curando y modificando junto con las guías de nuevos cuatrimestres. Vas a tener que laburar! Un apunte con sección ejercicios de parciales que vaya creciendo y mejorando cuatrimestre a cuatrimestre, curados y escritos por el alumnado de Sistemas Digitales.

¡Esto está para que cualquier individuo, con ganas de contribuir, pueda hacerlo!

Estructura del repo

En los directorios i-guia:

i-sol.pdf: PDF con los ejercicios correspondientes a los temas de la guía i-ésima. El que seguramente estás buscando, a menos que quieras contribuir.
i-sol.tex: Archivo que se debe compilar para obtener el archivo i-sol.pdf que uno quiera ver. En este se inyecta todo el código que está en los directorios, teoria-i, ejercicios-i, ejercicios-i-extra
directorio teoria-i: Contiene a teoria-i.tex
directorio ejercicios-i: Contiene los ejercicios de la i-ésima guía. Se nombran ej-j-i.tex con j, el número del ejercicio e i el de la guía.
directorio ejercicios-i-extra: Contiene los ejercicios extras, de clase y/o parciales de los temas de la i-ésima guía. Se nombran ej-extra-j-i.tex con j, el número del ejercicio e i el de la guía.

En la carpeta macros:
Ahí están los archivos necesarios para compilar los ejercicios.
preamble-general.tex: El preambulo con los paquetes necesarios para los comandos usados. -indice.tex: El índice, código para generar los links dentro del pdf y saltar directo a los ejercicios mejorando la navegación de los pdf.
definiciones.tex: Las definiciones, macros para que los comandos de LaTeX sean un poco más agradables y se pueda leer el código en leguaje más natural.
y algunas cositas más...

Si querés contribuir no hace falta codear ni saber LaTeX, podés marcar algún error que pueda haber en un ejercicio por ejemplo.
Ahí podés comentarnos por el grupo de Telegram o mail así lo solucionamos y aumentamos la calidad del trabajo. Si sabés un poco de LaTeX, ya vas a estar bien, porque hay muchísimos ejercicios con los comandos para que copies y pegues.

Para contribuir al código directamente tenés que:

Tener instalado Git
Tener instalado LaTeX
Tener cuenta de GitHub
Metete en el grupo de Telegram si necesitás ayuda con alguno de esos pasos. La idea es que te capacites para poder vos también mantener el repo vivo y actualizado.
Compilar
Para compilar los archivos de LaTeX una vez que fueron modificados:

Con la terminal, entrar a la carpeta de la guía que quieras compilar, por ejemplo la guía 1.
$ cd sistemasDigitales/1-guia/
$ pdflatex 1-sol.tex
Eso debería actualizar el archivo 1-sol.pdf con los cambios que hubieras realizado. [grupo de Telegram](https://t.me/+1znt2GV1i8cwMTNh)Luego tenés que hacer una pull request para actualizar el repositorio con tu aporte!


Metete en el [grupo de Telegram](https://t.me/+1znt2GV1i8cwMTNh) si necesitás ayuda con alguno de esos pasos. La idea es que te capacites para poder vos también mantener el repo vivo y actualizado, porque yo ya hice mi parte y me da paja mantener esto sin ayuda.
Podés usar el código como quieras siguiendo esta licencia: [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

Este es el _apunte único_
"Un Apunte para gobernarlos a todos, un Apunte para encontrarlos, Un Apunte para atraerlos a todos y atarlos en las tinieblas"

¡Una estrellita 🌟 al repo es siempre bienvenida! (^_^)/
