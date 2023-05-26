# Document Object Model
## Es un standard y tiene varias versiones ([[Levels]]). La mayoria de los [[Navegador|navegadores]] usan casi por completo el DOM [[Levels|Level 1]]


>[!tip] Es una forma de representar un documento [[HTML]] (o [[XML]]) como un árbol de nodos
---
> [!tip] Utilizando los métodos y propiedades del DOM podremos acceder a los elementos de la página, modificarlo, eliminarlos o añadir nuevos.

![[Pasted image 20230410163810.png]]

## El árbol del DOM
	- los elementos HTML se cnvierten en nodos interrelacionados en el árbol.
	- Los nodos pueden tener nodos hijos (child)
	- Los nodos del mismo nivel son hermanos (sibling)  
	  
	  ![[Pasted image 20230410164024.png]]






## El objeto "document"
	El objeto document se puede usar para acceder a todos los elementos del DOM.
	Por lo tanto si quieres acceder aobjetos en una página HTML, comienza ingresando al document.
```
document.body.innerHTML = "Ejemplo";
```

## Seleccionando elementos
	- Todos los elementos [[HTML]] son objetos, entonces tienen [[propiedades]] y [[Metodos]]
	- El objeto "document" tiene [[metodos]] que te permiten seleccinoar el elemento HTML deseado.
	- Los tres métodos más comunes son:
```
document.getElementById('id');
document.querySelector('#id');
document.getElementsByClassName('classname');
document.querySelector('.classname');
document.getElementsByTagName('tag');
```
### Agregar nodos
>[!tip] Para crear nuevos elementos podemos utilizar el [[metodo]] [[createElement]].
---

> [!tip] Una vez creados los podemos añadir al DOM con [[appendChild]]

![[Pasted image 20230410170417.png]]

### Clonar nodos
> [!tip] También podemos copiar elementos existentes con cloneNode()
---
> [!tip] cloneNode acepta un [[parametro]] [[Variables (javascript) | booleano]]

![[Pasted image 20230410170801.png]]

### Especificar dónde insertar un nodo
> [!tip] con [[insertBefore()]] podemos especificar el elemento delante del cual queremos insertar el nuestro.

![[Pasted image 20230410170902.png]]

> [!tip] para eliminar nodos del DOM podemos utilizar [[removeChild()]].
---
> [!tip] También podemos usar [[replaceChild()]] para sustituirlo por otro que se le pasa como parámetro.
---
> [!tip] tanto [[replaceChild()]] como [[removeChild()]] devuelven el nodo eliminado.

![[Pasted image 20230410171539.png]]







