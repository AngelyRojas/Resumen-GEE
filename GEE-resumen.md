RESUMEN DE GEE
================
Rojas Aylas Angely
31/1/2022

#GEE(JS)

**Google earth engine nos brinda imagenes satelitales, para lo cual
aprendimos a selecionar y filtrar imágenes**

Como en la plataforma se usa en lenguaje javascripts, primero aprendimos
cómo usarlo, por ejemplo:

**1)Para realizar comentarios en la plataforma de GEE se usa el “//”**

**2)Para crear variables se usa el “var”**

**3)Para imprimir y que aparesca en a consola se usa ” print()“**

**4)Usabamos “typeof()”para saber el tipo de dato**

Luego aprendimos a selecionar y filtrar imagenes

En “buscar” escribimos Landsat 8 collection 1 tier 1 TOA

Luego lo declaramos como:

*var L8 = ee.imagecollection(“el id de la imagen”)*

Luego lo imprimimos, pero limitamos:

*print(L8.limit(5))*

Entonces cargamos la imagen y la filtramos:

*var imagen= ee.immage((L8)*

Usamos “lilterbound” para obtener solo imágenes de una region de
nuestroinerés:

*.lilterbound(lugar)*

Usamos “filterDate” para obtener imagenes solo de un año

*.filterDate(“2012-01-01”,“2012-12-31”)*
