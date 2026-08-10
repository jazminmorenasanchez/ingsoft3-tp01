# Evidencias — TP1

## 1. Push directo a main rechazado

Protegimos la rama main para que no se pueda modificar directamente. Todo cambio se desarrolla en una rama aparte, se sube esa rama a GitHub y se abre un Pull Request contra main, si es correcto se realiza el merge. En un equipo, ese Pull Request puede requerir aprobación de otros desarrolladores, en este TP individual no exige aprobaciones porque las aprobaciones deben ser hechas por alguien distinto de quien lo solicito, pero igualmente obliga a pasar por el proceso de revisión y merge. Tambien activamos que el dueño del repositorio no pueda modificar directamente el main.

## 2. El PR de la rama B no se puede mergear: conflicto

Lo que buscamos ahora es simular el conflicto entre dos personas, para eso creamos dos ramas que trabajan exactamente en la misma linea. primero trabajamos con la A, hacemos el pull request pero no relizamos el merge, luego con la B lo mismo, modificacmos la misma linea y relizamos el pull request. Una vez hecho esto hacemos el merge de A. Ahora al volver a la rama B nos encontramos el conflicto y vemos que no podemos hacer el merge sin antes resolver el conflicto.

## 3. El PR de la rama B no se puede mergear: marcadores

luego de apretar resolver conflicts, nos topamos con las tres lineas de marcadores y las dos versiones de las lineas, elegi una que fue la B y borre el resto, aprete commit merge y quedo.

