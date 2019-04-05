1) ¿Qué es GitHub?
GitHub [1] es un sitio web y un servicio basado en la nube que permite a los programadores, de manera colaborativa,  (como desarrolladores de aplicaciones, por ejemplo) la administración y almacenamiento de su código, al igual que posibilita mantener un registro y control de cualquier cambio que se ejecute sobre el mismo. Su  funcionamiento se encuentra basado en el sistema de control de versiones (Git),  que permite, precisamente, llevar un registro y administrar cualquier cambio que se realice sobre el código, a partir de la bifurcación y fusión. La primera hace posible que el programador duplique parte del código fuente para hacer cambios de manera segura sin alterar éste. Cuando los cambios funcionan de manera correcta, se puede aplicar la fusión para trasladar dichas modificaciones al código principal.

2) ¿Qué es un Branch?
Un branch o rama [2] es una forma de organización de la plataforma GitHub. Puede ser definido como un conjunto único de cambios o modificaciones que se hacen al proyecto sin alterar el código principal (master). El empleo de ramas resulta sumamente útil, sobre todo en el trabajo colaborativo, porque al no afectar el código principal, permiten al programador probar nuevas funcionalidades y cambios para el mismo y que, una vez que se tenga certeza que funcionan correctamente, pueden ser fácilmente incorporados a la rama principal para que se visualice dichas modificaciones en la funcionalidad del código. 

3) ¿Qué es un commit?
Consiste en la actualización de los archivos que están siendo creados en git, logrando que los cambios que se hayan hecho sean guardados.

4) ¿Qué se entiende cuando se dice que un archivo está “staged”?
Los archivos en este estado han sido modificados y están preparados para ser guardados, con el estado actual, en el próximo commit.

5) ¿Qué hace el comando git checkout?
El comando git checkout se utiliza para la creación de nuevas ramas, o bien, para cambiar entre ellas (movilización entre ramas). Para crear un nuevo branch, se hace la siguiente sentencia:
command git checkout -b <”nombre del branch”>

Por su parte, para cambiar de una rama a otra, se indica la siguiente instrucción:

git checkout <”nombre del branch”>

6) ¿Qué hace el comando git stash?
Este comando permite guardar temporalmente un archivo, para poder trabajar en alguna otra parte del código sin tener que preparar y actualizar ese archivo temporal.

7) ¿Qué hace el comando git add?
Permite indexar archivos nuevos o los que han sido modificados y de esta forma git los tomará en cuenta a la hora de indicar su estado y una posible actualización de los archivos.

8) ¿Qué es Pytest?
Pytest es una herramienta para Python, un marco de referencia que permite realizar códigos de prueba bajo el lenguaje Python. Es sumamente utilizado en la industria por diversas ventajas:
Su sintaxis es muy simple y fácil de comprender.
Puede correr pruebas en paralelo.
Puede correr una prueba en específico o un subgrupo de pruebas.
Puede omitir pruebas.
Detecta automáticamente una prueba.

9) Bajo el contexto de Pytest, ¿qué es un “assert”?
Un assert es una función de pytest que permite verificar expectativas o valores en pruebas de python. Por medio de introspección, pytest puede inferir el valor actual, el valor esperado y la operación utilizada con un assert, y devuelve un mensaje de error con su explicación y el tiempo de error. 

10) ¿Qué es Flake 8?
Flake8 es una librería de Python que funciona para revisar el código en busca de errores de sintaxis y de forma; también permite revisar la “complejidad ciclomática” del código. Este término se refiere al número de caminos independiente que tiene el código base,en otras palabras, es una medida cuantitativa de la complejidad lógica de un programa.
