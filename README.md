## Ejercicio A
Una escuela tiene una planta con 120 alumnos repartidos en 4 divisiones A, B, C y D, los datos más reelevantes que la misma registra son nombre, apellido, género, edad y altura. Este año se propuso que la foto de fin de año sea con todos los alumnos formados en filas separados por división adentro del salón de actos, sin embargo el mismo no es muy alto por lo cuale s necesario ordenar por altura a los alumnos de mayor a menor para que todos salgan en la foto.

## Objetivo
Crear un sistema para que los datos proveídos en el file alumnos.json pasen por la siguiente lógica de servicio:
- Agrupar a los alumnos en su respectiva división. { "divisiones" : [ { "A" : [ ], "B" : [ ], "C" : [ ], "D" : [ ] } ] }
- Ordenar de mayor a menor por altura.

## Condiciones excluyentes
- El lenguaje dependerá del perfil que se está buscando.
- En el caso que el lenguaje aplique a POO aplicar las principales características para demostrar un diseño robusto.
- Subir a un repositorio público al que los técnicos de Opendev tengan acceso.

## Deseable no excluyente
- Crear un servicio REST donde el json se envíe por Body, en caso de no ir por este camino se puede utilizar el mismo desde adentro del proyecto (como file o cadena caractéres).
- Que el resultado sea la respuesta de un servicio REST, en caso de ir por este camino sólo imprimir por consola el resultado.
- Desplegar en algúna PaaS gratuita como heroku.com, fly.io u otra la app en forma temporal.
