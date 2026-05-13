## Tarea 1:
- **¿Qué es un fork?** 
   Un fork es una copia personal de un repo de otra persona que se guarda en tu propia cuenta de GitHub en modo "online". Permite experimentar, realizar cambios y proponer mejoras libremente sin afectar el proyecto original.
- **¿Para qué sirve "upstream"?**
   "Upstream" hace referencia al repositorio original desde el cual se creó el fork.
 ### Capturas obligatorias
![captura 1](capturas/captura1.png)
![captura 2](capturas/captura2.png)

## Tarea 2:
- **¿Por qué la rama parte de dev y no de main?**
   La razón principal por la que no partes directamente de main es para proteger la estabilidad del proyecto, en main solo debe haber versiones del código que ya han sido probadas y aprobadas. "Dev" es la rama donde se van juntando todas las carácterísticas nuevas que el equipo está desarrollando y si algo sale mal mientras juntas dos carácterísticas o funciones nuevas, se rompe dev, pero tu versión de producción (main) sigue intacta y funcionando para los clientes.
 ### Capturas obligatorias
![captura 3](capturas/captura3.png) 

## Tarea 3:
- **¿Qué es un conflicto en Git?**
  Un conflicto en Git es básicamente cuando se producen dos cambios que chocan frontalmente y Git no tiene forma de saber cuál es el "correcto", y ahí es el programador o los programadores los que deciden cual es el cambio correcto, no lo hace Git de manera automática.
- **¿Por qué se produce en la práctica de laboratorio?**
  Porque se ha modificado a la vez, en dos ramas distintas, la misma línea de código, la "description" de la opción 3 de la app.

## Tarea 4:
- **¿Qué revisaste en la pestaña Files changed y por qué es útil hacerlo antes de mergear?**
   La pestaña Files changed es, esencialmente, el qué se ha añadido o borrado antes de que tu código pase a formar parte del proyecto, es decir, la diferencia entre lo que había y lo que he puesto. Se marca en verde lo que se añade y en rojo lo que se borra. Y es útil hacerlo antes de mergear porque un pequeño error en una rama feature es fácil de arreglar. Si ese error llega a main, puede romper la aplicación para todos los usuarios. Revisar en el Pull Request es tu última red de seguridad antes de la fusión con el código principal.
   ### Capturas obligatorias
![captura 4](capturas/captura4.png) 

  


