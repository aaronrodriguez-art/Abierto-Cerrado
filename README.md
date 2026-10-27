# Abierto-Cerrado
Principio abierto-cerrado de SOLID 

Este principio se aplica permitiendo agregar nuevas funciones sin tener que modificar el código que ya está hecho y funcionando

- Tenemos una clase base llamada `Producto` que maneja lo general (el nombre y el precio) Esa clase se deja quieta y no se toca
- Si queremos agregar nuevos tipos de productos, como un producto `Fisico` (que lleva peso) o uno `Digital` (que lleva ruta de archivo), simplemente creamos clases que hereden `Producto`. 
