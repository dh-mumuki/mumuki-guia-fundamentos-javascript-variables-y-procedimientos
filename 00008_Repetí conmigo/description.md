Llegó el turno de otra estructura de control de flujo: la repetición simple. Que si mal no te acordás, era algo como lo siguiente...

```gobstones
program {
  repeat(4) {
    //...hacer algo...
  }
}
```

... que nos permitía repetir una tarea múltiples veces. En JavaScript también tenemos una estructura similar: el `for`.

Por ejemplo, si queremos tirar los dados 4 veces e imprimir su resultado, podríamos escribir lo siguiente:

```javascript
for(let numero of rango(1, 4)) {
   imprimir("Salió el " + tirarDado())
}
```

> Escribí un programa que dibuje un "cuadrado" de asteriscos de 4 por 4:
>
> ```
> ****
> ****
> ****
> ****
>```