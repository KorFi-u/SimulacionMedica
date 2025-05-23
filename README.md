# SimulacionMedica

# Estudiante
- Bastian Fabian Erasmo Umaña Miranda
- Seccion: 1

# Diagrama de Caso de Uso
## Correccion del Diagrama 💯
- 1.- **No aplica `<<include>>` o `<<extend>>`.**
- 2.- **El administrador no deberia de notificar cambio por correo cuando aprueba la reserva, deberia ser una respuesta que envia solo el sistema opcionalmente.**
- 3.- **En el diagrama se utiliza asociaciones de un diagrama de clase, como la flecha en blanco en donde deberia ir un `<<extend>>`.**
- 4.- **Al reservar una sala el sistema no deberia de responderle al usuario con "Consultar disponibilidad externa".**
- 5.- **El estudiante no deberia de poder eliminar el historial de reservas.**
- 6.- **El Estudiante no deberia de poder ver el historial de otras personas.**
## Justificación de Errores
Al no tener aplicados los `<<include>>` y `<<extend>>` no se pueden identificar bien las asociaciones dentro del diagrama, como si el envio de una notificacion es opcional o obligatoria. 
Ademas se puede notar que el administrador puede notificar un cambio por correo, el cual deberia ser una accion que realize solo el actor SistemaNotificaciones (de manera opcional).
Las asociaciones dentro del diagrama deberian ser con flechas de color negro y los `<<extend>>` con interlinea.
Al reservar una sala el sistema deberia enviarle una notificacion al usuario de que la reserva se realizo exitosamente.
Solo el administrador deberia poder eliminar el historial de reservas (de manera opcional).
Solo el administrador deberia de poder ver el historial de otras personas en el sistema.

# Diagrama de Clases
## Correccion del Diagrama 💯
- 1.- **La clase de usuario no deberia llamarse de esa manera ya que usuario es todo el que usa el sistema sea administrador o no**
- 2.- ****
## Justificación de Errores

# Diagrama de Implementacion
## Correccion del Diagrama 💯
## Justificación de Errores

# Diagrama Corregido
- Caso de Uso:
- ![casodeuso drawio](https://github.com/user-attachments/assets/3c08bee0-150f-4c07-9072-d0cd24d2be56)
---
