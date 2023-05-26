La comunicacion siempre va de manera descendiente.
## COMPONENTE PADRE -> COMPONENTE HIJO

Siempre que un componente quiera enviar información a sus componentes hijos 
Se utiliza un componente especial Llamado
# PROPS
## FUNCION: props solamente cumple la funcion de enviar propiedades/funciones a sus componentes hijos
Podemos cargarlo con todo tipo de información. incluso funciones.
![[Pasted image 20230516173917.png]]
En este caso, imaginemosnos a "props" Como un paquete de "regalos" donde App enviara funciones a Titulos

Entonces, como hacemos esto?
Así
inventamos una "propiedad" dentro de la etiqueta
![[Pasted image 20230516174044.png]]
para testear, enviariamos un string al componente "Titulos.jsx"
![[Pasted image 20230516174131.png]]


## Y quien mando ese componente props? = SIEMPRE ES EL COMPONENTE PADRE A SUS HIJOS

![[Pasted image 20230516174538.png]]
![[Pasted image 20230516174802.png]]
|||
Ahora, como usamos estas propiedades?
tenemos dos tipos de sintaxis
|||
Camino Largo
hay que recibirlos por parametros
![[Pasted image 20230516174822.png]]

Lo unico que no se puede hacer es asignarle al objeto props un nuevo dato, ya que son **INMUTABLES**
![[Pasted image 20230516174902.png]]
|||
Camino Corto
Desestructurar el objeto props
agarro cada una de las propiedades y la dejo en una sola propiedad
En los parametros de la función poner llavecitas, solamente agregar el nombre de las propiedades
![[Pasted image 20230516175102.png]]
Y lo usamos como debe ser
![[Pasted image 20230516175124.png]]

