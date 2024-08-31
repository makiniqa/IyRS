# IyRS
Apuntes y resúmenes de la materia Informática y Relaciones Sociales, 2° cuatrimestre 2024.
Abierto a la colaboración <3

## Código para colaborar
- Si subís tus apuntes de clase, ponelos (dentro de `apuntes de clase`) dentro de una carpeta con tu nombre, alias, o una palabra que te represente, para que no se mezclen
- Si subís tus resúmenes, ponelos dentro de la carpeta `resúmenes`, luego dentro de la carpeta correspondiente a la unidad del texto,
y luego dentro de la carpeta `obligatorios`, `recomendados` o `complementarios`. Si la carpeta no existe, creala. Recomendado poner tu nombre, alias, o una palabra que te represente
entre paréntesis al final del nombre del archivo, para que no se mezclen si varias personas suben del mismo
- No subir textos de la materia que tengan copyright
- Textos de la materia, especialmente recomendados o complementarios que te hayan gustado, y/o textos que te gusten que tengan que ver con el contenido de la materia
 (cuya licencia lo permita) se pueden subir a la carpeta `textos`
- A la carpeta `misc` podés subirse archivos de texto con links a material interesante, pensamientos, etc, lo que quieras

## Soy sociólogx, no sé usar git
Primero hacete una cuenta de github.

Para subir archivos tenés dos opciones: la fácil es usar el botón de Add file, parándote primero en la carpeta que corresponda.

Pero si querés tener el repositorio descargado en tu compu, o querés jugar a ser hacker, podés usar git:
- Instalá git. Instrucciones [acá](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git).
- Ahora vamos a clonar el repositorio. [¿Qué es un repositorio?](https://es.wikipedia.org/wiki/Repositorio_(contenido_digital) 
- Antes de empezar, vas a tener que conocer un par de comandos básicos. Una aclaración, yo no uso Windows; entiendo que estos comandos funcionan en git bash pero si no es así vas a tener que buscar porque nidea men
    - para moverte de carpeta en carpeta, vas a usar [cd](https://en.wikipedia.org/wiki/Cd_(command). Ej: `cd Documents/`
    - podés moverte a la carpeta superior con `cd ..` 
    - para ver los archivos que tiene la carpeta en la que estás parade, vas a usar [ls](https://en.wikipedia.org/wiki/Ls)
- Abrí tu terminal de git, dirigite a la carpeta donde quieras guardar esto, y pone `git clone git@github.com:makiniqa/IyRS.git`
- Listo, ya la tenés copiada localmente. 
- Para subir, vas a poner `git add nombre-del-archivo`, siempre que estés parade dentro de la carpeta. Ojo que cuando recién clonás no te mueve automáticamente adentro de la carpeta.
- Ahora vamos a commitear los cambios con `git commit -m "frase que describa lo que cambiaste"`.
- En cualquier momento podés ver qué archivos agregaste, cuáles no, cuáles son nuevos y cuáles modificados con `git status`
- Antes de subir los cambios, traete los cambios que hayan hecho otras personas con `git pull`. Así evitamos que los cambios entren en conflicto (no deberían, pero porlas).
- Último paso: para subir los cambios poné `git push`.
- Listo! A menos que te haya tirado algún mensaje de error, los cambios deberían verse reflejados acá.
- Como mencioné antes, siempre que quieras traerte los cambios que hayan hecho otras personas a tu máquina, le das `git pull`

