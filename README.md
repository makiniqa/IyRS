# IyRS
Apuntes y resúmenes de la materia Informática y Relaciones Sociales, 2° cuatrimestre 2024.

Abierto a la colaboración <3

![No sabemos tanto pero lo ke sabemos se comparte](https://instagram.faep14-3.fna.fbcdn.net/v/t51.2885-15/57034864_2059891234133231_7850106499234263585_n.jpg?stp=dst-jpg_e35_p640x640_sh0.08&efg=eyJ2ZW5jb2RlX3RhZyI6ImltYWdlX3VybGdlbi4xMDgweDExMjYuc2RyLmYyODg1LmRlZmF1bHRfaW1hZ2UifQ&_nc_ht=instagram.faep14-3.fna.fbcdn.net&_nc_cat=111&_nc_ohc=3zFZ8dT4PDMQ7kNvgFLpAFp&edm=ANTKIIoBAAAA&ccb=7-5&oh=00_AYBvsCz0mey9O6hQFLSdWASnnQCcmIno_n2zGLGd3ZYPcA&oe=66D94295&_nc_sid=d885a2)

(cred. [skuichisaurio](https://www.instagram.com/skuichisaurio/))


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
Bueno primero y principal si lográs vencer la paja de guglear te aseguro que hay tutoriales mucho mejores en internet. Pero sino: 

Primero hacete una cuenta de github. Después pasame tu nombre de usuario y te hago colaborador.

Para subir archivos tenés dos opciones: la fácil es usar el botón de Add file, parándote primero en la carpeta que corresponda.

Pero si querés tener el repositorio descargado en tu compu, o querés jugar a ser hacker, podés usar git:
- Instalá git. Instrucciones [acá](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git).
- Ahora vamos a clonar el repositorio. [¿Qué es un repositorio?](https://docs.github.com/es/repositories/creating-and-managing-repositories/about-repositories)
- Antes de empezar, vas a tener que conocer un par de comandos básicos. Una aclaración, yo no uso Windows; entiendo que estos comandos funcionan en git bash pero si no es así vas a tener que buscar porque nidea men
    - para moverte de carpeta en carpeta, vas a usar [cd](https://es.wikipedia.org/wiki/Chdir). Ej: `cd Documents/`
    - podés moverte a la carpeta superior con `cd ..` 
    - para ver los archivos que tiene la carpeta en la que estás parade, vas a usar [ls](https://es.wikipedia.org/wiki/Ls)
- Abrí tu terminal de git, dirigite a la carpeta donde quieras guardar esto, y poné

  `git clone git@github.com:makiniqa/IyRS.git`
- Listo, ya la tenés copiada localmente. 
- Para subir, vas a poner `git add nombre-del-archivo`, siempre que estés parade dentro de la carpeta. Ojo que cuando recién clonás no te mueve automáticamente adentro de la carpeta.
- Ahora vamos a commitear los cambios con `git commit -m "frase que describa lo que cambiaste"`.
- En cualquier momento podés ver qué archivos agregaste, cuáles no, cuáles son nuevos y cuáles modificados con `git status`
- Antes de subir los cambios, traete los cambios que hayan hecho otras personas con `git pull`. Así evitamos que los cambios entren en conflicto (no deberían, pero porlas).
- Último paso: para subir los cambios poné `git push`.
- Listo! A menos que te haya tirado algún mensaje de error, los cambios deberían verse reflejados acá.
- Como mencioné antes, siempre que quieras traerte los cambios que hayan hecho otras personas a tu máquina, le das `git pull`

