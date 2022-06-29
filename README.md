Semestre I - 2022
# Sopa de Letras
## OBJETIVOS
1.	Desarrollar las capacidades de abstracción mediante el análisis e interpretación del problema
2.	Aplicar los conocimientos y fundamentos de la programación en la resolución del proyecto final.
# ESPECIFICACIONES
Se requiere un sistema que pueda resolver una sopa de letras.
Para este sistema primeramente se desplegará un menú con las siguientes opciones.
Presione el número de la opción
1 Cargar sopa de letras
2 Cargar valores a buscar
3 Resolver sopa de letras
4 Salir
1) Si se selecciona la opción uno el sistema deberá pedir el tamaño NxM de la sopa de letras luego notificar al usuario que se están cargando los datos desde el portapapeles y así mismo obtener los datos desde el portapapeles, los datos no siempre llegan secuencialmente como se esperan, sino que pueden llegar, con espacios extras o en varias líneas, para lo cual se deberá formatear este valor para luego almacenarlo en la matriz NxM
Ejemplo de datos que se obtendrán del portapapeles en el archivo adjunto Sopa de Letras 11x10
Se validará que la cantidad de datos (caracteres) obtenidos coincida con el tamaño del tablero caso contrario se mostrará un mensaje de error y se retorna al menú principal.
2) Si se selecciona la opción dos el sistema deberá pedir el tamaño N de la cantidad de elementos a buscar el cual será almacenado en una lista (Array), luego procederá a pedir si desea cargar los valores por teclado o del portapapeles.
Considerar que si se pide por teclado se pedirá todos los valores a buscar separados por coma (,) luego el sistema pedirá si desea seguir ingresando los valores.
Si es del portapapeles tendrá que hacer el respectivo formateo.
3) Si se selecciona la opción tres el sistema deberá proceder a validar que previamente se tenga cargado el tablero con letras y al menos un valor en la lista de búsqueda.
Luego procederá a mostrar 2 tableros de sopas de letras, uno sin resolver y otro con los datos resueltos.
Si una palabra no se encontrara en la sopa de letras deberá mostrarse al final que palabras no se encontraron.
4) Si se selecciona la opción cuatro el sistema deberá proceder a terminar la ejecución antes mostrando un mensaje de Gracias por usar el sistema.



