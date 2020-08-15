PREGUNTA 1:
Un control de versiones es un software que permite registrar los cambios realizados durante el desarrollo de un proyecto.
De esta manera, se pueden recuperar versiones justo antes de haber realizado un cambio el cual haya generado algún problema, saber quién y cuándo introdujo alguna modificación y recuperar todo el proyecto en caso de perdida o daño del equipo donde se trabajaba el proyecto.

PREGUNTA 2:
Como indica el texto, tener muchas carpetas con nombres de proyectos con sufijos como "final" o "este si es el último".
Lo cual causa un almacenamiento innecesario y confusión al momento de saber cual de ellos es el proyecto final.
Pero, no usar un control de versiones nos dificulta principalmente a la hora de trabajar un proyecto en equipo, debido a que, no podemos saber quién y cuándo realizó un cambio a algún archivo del proyecto, y de causar una falla, sería dificultuso regresar a la versión cuando todo iba bien.

PREGUNTA 3:
En cuanto a los beneficios tenemos:
- Facilita el trabajo en equipo, ya que podemos compartir un mismo proyecto y realizar cambios en el mismo de manera remota.
- Permite mantener un histórico de las versiones durante el desarrollo del proyecto. Así, poder ir, retroceder o regresar a una versión.
- Saber quién y cuando se realizó un cambio en el proyecto, asi en caso de algún problema, regresar a al versión justo antes del fallo.

PREGUNTA 4:
- Local
    Aquí podemos guardar las versiones del desarrollo de un proyecto en nuestro computador usando los comandos:
        git init
        git add .
        git commit -m ""

- Centralizada
    Aquí todas las versiones del desarrollo de un proyecto están en un único repositorio. Luego cada desarrollador debe pedir una copia local para trabajar en ella y terminado los cambios guardan una nueva version en el repositorio central.


- Distribuida
    Aquí no hay un repositorio central, los desarrolladores tienen una copia del repositorio con todas las versiones y luego pueden entre dos o más desarrolladores sincronizar sus repositorios.