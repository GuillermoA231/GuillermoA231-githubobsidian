## Continuaremos trabajando con el [[DOM]] donde veremos un breve ejemplo del evento [[submit]] en un formulario. Por ultimo veremos que es el [[BOM]] usando el objeto [[window]], realizaremos un [[ejercicioBOM|breve ejercicio]] para utilizar los metodos [[setTimeOut]] y [[setInterval]]


## Menciones
[[|Validaciones HTML]]
[[|Campo Obligatorio "Required"]]
[[Tomar los datos del input?]]onclick
[[DOM|primer Nodo de DOM "document"]]
[[Funciones DOM#onclick|onclick]]
[[onsubmit()]]

## querySelector
Siempre busca un selector de css

## addeventListener
```
element.addeventListener('submit',obtenerDato)
```
Se va a ejecutar la función al ingresar un boton que tenga console.log.

> [!warning] hay que atrapar el mensaje de submit

## Objeto [[event]]

> [!info] console.log(variable.value)
> 	Muestra el contenido de la variable cuando se usan eventos
---
> [!tip] document.querySelector('input').value
> Se almacena el texto del query, extrayendo solamente el texto

[[typeof]]
![[Pasted image 20230411173232.png]]
adivinar números, con el formulario poner el nro 4 y con el search tendria que averiguar si es el que e adivinado


### Resetear los datos de un formulario
### formulario.==reset()==
Necesario invocar si necesito limpiar el formulario

- Necesario usar [[validaciones HTML | validaciones]] para evitar problemas usando los submit


---
---

## BOM

usar [[Funciones BOM|setTimeout]] y [[Funciones BOM|setInterval]]
Para usar esto es necesario declarar una función 
