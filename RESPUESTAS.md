# Respuestas Práctica Git y GitHub

## Fase 1
1. Sirven para que Git sepa quién hace cada commit. Luego salen en el historial y en GitHub.
2. Porque la contraseña da acceso a toda la cuenta y no es seguro usarla desde un programa. GitHub pide autorizar desde el navegador con un token, que se puede anular cuando quieras.

## Fase 2
1. Porque es el entorno virtual, pesa mucho y cada uno se lo puede crear en su ordenador.
2. El rojo era que Git veía el archivo pero todavía no lo seguía. si lo cambio después de un commit sale en azul.

## Fase 3
1. Es el nombre que le pone Git al repositorio de GitHub.
2. El commit guarda los cambios en mi ordenador y el push los sube a GitHub.

## Fase 4
1. Porque así se ve mejor lo que hice en cada momento y si algo falla es más fácil encontrar el fallo o deshacerlo.
2. "cambios" o "arreglo", porque no dice qué se cambió ni por qué.

## Fase 5
1. Puedo probar cosas sin estropear main y solo lo junto cuando está listo.
2. Es cuando main no ha cambiado mientras yo trabajaba en la rama así que Git solo mueve main hacia delante y no crea un commit de merge, aqui pasó eso.

## Fase 6
1. Porque las dos ramas habían cambiado la misma línea y Git no sabía cuál dejar, en la fase 5 solo había cambiado una.
2. Me habría quedado con la línea de feature/formato y habría perdido la que puse yo en main.

## Fase 7
1. Para bajarme lo que haya subido otra persona antes de empezar a trabajar y no usar una versión vieja.

## Fase 8
1. Que otra persona puede mirar y comentar los cambios antes de juntarlos, y todo queda guardado en GitHub.
2. Porque la PR va unida a la rama, si hago push a esa rama el commit nuevo sale solo en la PR.

## Fase 9
1. Pop recupera los cambios y borra el stash, apply los recupera pero el stash se queda guardado.

## Fase 10
1. Rollback quita los cambios que aún no he confirmado, amend corrige el último commit, undo commit quita un commit que no he subido y deja los cambios pendientes, revert deshace un commit que ya está en GitHub, creando otro commit nuevo.
2. Porque PyCharm guarda su propio historial de los archivos aparte de Git.

## Fase 11
1. Cuando lo conté, main tenía 20 commits y 3 eran de merge.
2. La validación del rango la hizo el commit "Valida el rango de la nota" y el hash era 2d0b851. 