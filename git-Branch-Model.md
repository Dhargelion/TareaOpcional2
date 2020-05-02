# Git branch model
>Nombre:Diego Coraales Vega

Git Branch model son como buenas practicas que deben implementarse al momento de trabajar con ramas de git.
El repositorio vendria a tener 2 ramas principales las cuales no deben eliminarse, las cuales son:

- master
- develop
 
 master sera la rama en la que esta el codigo listo para produccion, en la rama develop es donde estaran los ultimos cambios.
 Cuando en develop se alcanza un punto estable y esta listo para un lanzamiento, todos los cambios se deben fusionar con master. 
 Existen ramas de apoyo que son :
 - feature
 - hotfixes
 - release

 Las ramas feature se usan para crear nuevas caracteristicas, hotfixes se usan para corregir errores, y release cuando se tiene el avance deseado para un lanzamiento