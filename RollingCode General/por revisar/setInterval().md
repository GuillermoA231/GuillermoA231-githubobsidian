Ejecuta una función cada x tiempo en ms de manera indefinida
```
setInterval(mensaje,tiempoenmilisegundos)
```

puede ser detenido

```
setInterval(() => {

document.write('<p> lorem </p>');

},1000)
```
const idInterval = setInterval(mensaje,200);
