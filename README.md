# caiomsouzarpackage

This package was created for the Experto en Data Science de U-Tad, Modulo 7. It is an example of a R Package<BR><BR>

Ejercicio extra (2 puntos)<BR>
Crea un paquete de R con dos o tres funciones tontas. Una de ellas tiene que llamarse suma.dos.numeros y tiene que aceptar dos parámetros: los números que quiero sumar. Luego súbelo a Github.<BR>
Para puntuar en este ejercicio, me tienes que pasar una versión del siguiente código,

```
library(devtools) 
install_github("url del paquete")
library("nombre del paquete")
suma.dos.numeros(2,2)
suma.dos.numeros(2.5)
￼?suma.dos.numeros
remove.packages("nombre del paquete")
```

que instale tu paquete, ejecute lo que me interesa y lo elimine después.<BR><BR>

```

# Install devtools
install.packages("devtools")

# Load devtools
library("devtools")

# Install caiomsouzarpackage
# https://github.com/caiomsouza/caiomsouzarpackage
devtools::install_github("caiomsouza/caiomsouzarpackage")

#Load caiomsouzarpackage
library("caiomsouzarpackage")

# cat_function doc
?cat_function

# suma.dos.numeros doc
?suma.dos.numeros

# Try suma.dos.numeros
suma.dos.numeros(2,2) 
suma.dos.numeros(2,8) 
suma.dos.numeros(2.5)
suma.dos.numeros(2.8)


# Remove caiomsouzarpackage
remove.packages("caiomsouzarpackage")

```

Links:<BR>
http://cran.r-project.org/doc/contrib/Leisch-CreatingPackages.pdf<BR>
http://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/<BR>
http://wesmckinney.com/blog/<BR>
http://www.sr.bham.ac.uk/~ajrs/R/r-function_list.html<BR>
