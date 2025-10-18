# Parcial2-Devsoft

# Juan Sebastian Molina - 408752

# Descripcion de diseño

El proyecto se desarrolló siguiendo una arquitectura en capas que separa responsabilidades entre controladores, servicios, repositorios, modelos y DTOs.
Esto con el fin de tener un código limpio, modular y fácil de mantener.
Se eligió Node.js con Express por su simplicidad y capacidad para implementar APIs REST de forma rápida, cumpliendo con los endpoints definidos.
Los controladores se limitan a recibir y responder solicitudes HTTP, mientras que la lógica de negocio se ubica en los servicios, y el manejo de datos en los repositorios.
Se optó por usar una estructura en memoria para simplificar las pruebas, manteniendo la posibilidad de escalar a una base de datos real sin modificar la arquitectura principal.

## Enlace video 

https://drive.google.com/drive/u/2/folders/1O3C451Ge_BldEGYW4GUkM6AnrnRgbCL2
