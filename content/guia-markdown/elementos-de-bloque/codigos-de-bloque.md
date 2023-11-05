---
title: "Códigos de Bloque en Markdown"
---

Los códigos de bloque permiten que el texto sea presentado como código fuente, sin ser procesado por Markdown. Esto es especialmente útil para la documentación de software o tutoriales de programación.

Para crear un bloque de código, envuelve tu texto entre tres comillas invertidas (```). También puedes especificar el lenguaje de programación después de las comillas invertidas para la sintaxis de resaltado.

Ejemplo de bloque de código sin especificar lenguaje (En los ejemplos se deja un espacio en la tercera comilla invertida para no activar el lenguaje):

```
```Markdown
Este texto está dentro de un bloque de código.
`` `
```

Resultado:

```Markdown
Este texto está dentro de un bloque de código.
```


Ejemplo con resaltado de sintaxis para `python`:
```python
```python
def say_hello():
    print("Hola, mundo!")
`` `
```

Resultado (el resaltado real dependerá de tu tema de Hugo):

```python
def say_hello():
    print("Hola, mundo!")
```


Ahora, veamos cómo las [Reglas Horizontales pueden servir →](../reglas-horizontales/) como puntos de pausa o separación entre secciones de contenido.


