Ejercicio 4: CSS2 - Movilidad Erasmus
Lo primero que hemos realizado en esta práctica ha sido maquetar la estructura general de la página, centrándonos principalmente en la cabecera y el pie de página.


(CSS)
Cabecera 
Hemos empezado por el contenedor principal de la cabecera, al que le hemos aplicado las siguientes propiedades:

-display: flex: para que los elementos interiores se distribuyan de forma horizontal.

-justify-content: space-between: para que un bloque se quede al principio y el otro al final.

-align-items: center: para que todo el contenido quede centrado verticalmente.

-padding: 0 25px 0 50px: para ajustar los espacios laterales (50px por la izquierda y 25px por la derecha).

Además, a la clase .cabecera__marca le hemos dado color y la hemos puesto en negrita para que destaque.

En cuanto al menú de navegación, también le hemos puesto display: flex para que sus elementos se coloquen en horizontal. Hemos quitado los puntos de la lista con list-style: none y hemos separado cada opción con un gap: 10px.

A los enlaces generales les quitamos el formato por defecto usando text-decoration: none y les pusimos un tamaño de letra más pequeño. Como excepción, seleccionamos el tercer hijo de la lista para aplicarle un subrayado normal, y a la opción activa de "Solicitud" le añadimos un subrayado amarillo (usando un borde inferior) y la pusimos en negrita.

Pie de página
Para el pie de página hemos seguido la misma lógica que arriba. Le hemos aplicado display: flex, justify-content: center y align-items: center a la clase .pie para centrar todo el bloque. Finalmente, a la clase .pie__lista le pusimos otro flexbox y la decoramos con el mismo estilo de enlaces que usamos en el menú principal