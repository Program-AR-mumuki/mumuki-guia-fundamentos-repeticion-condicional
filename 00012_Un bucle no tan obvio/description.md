Veamos otro ejemplo de **bucle infinito** (así se llama a esto de los `while` que **no terminan**).

```gobstones
procedure PaLanteYPaTras() {
  while (puedeMover(Norte)) {
    Mover(Norte)
    Poner(Verde)
    Mover(Sur)
  }
}
```

> Escribí el código en el editor y fijate cómo (no) funciona.