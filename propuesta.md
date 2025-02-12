% Flota de taxistas «GoTaxi»
% Eduardo Sumariva Salgado
% Curso 2024/2025

# Descripción general del proyecto

Este proyecto consiste en crear una pagina web que brinde a los usuarios la oportunidad de consultar precios para 
poder pedir un taxi, ver disponibilidad y poder realizar reservas para medias/largas distancias.

## Funcionalidad principal de la aplicación

La página web cumpliria los siguientes puntos:

Consultar tarifas: Nos permitiría consultar el precio desde un punto de otro, distancia que hay, tiempo aproximado junto con el precio de dicho viaje.

Reservar viaje: En caso de disponibilidad y distancia minima aceptada para poder realizar dicha reserva, el cliente haría
la reserva, podría hacerla para en el mismo momento en el que la pide, o para una fecha futura.

Servicios especiales: En caso de alguna discapacidad, mudanzas, o cualquier servicio especial fuera de lo habitual, tendremos un apartado adicional dentro de las reservas para poder marcas algunas de estas opciones.

Notificaciones: Una vez realizada la reserva, se notificará al taxista disponible en dicho horario, para que pueda aceptar
o rechazar dicho viaje, en caso de rechazarlo, se notificará al siguiente taxista disponible, una vez aceptado por un taxista, al cliente se le notificará que su viaje ha sido exitosamente aceptado, indicando el número del taxi el cual irá.

Modelo de empresas: Para empresas en las que sus trabajadores necesiten transporte diario, podrán contactar con nosotros para obtener más información y tener a su disposición los taxis que necesite.


## Objetivos generales

* Objetivo: "Gestionar usuarios"
* Casos de uso:  "crear usuarios", "modificar perfil usuario", "eliminar perfil usuarios"

* Objetivo:  "Gestionar taxistas"
* Casos de uso: "crear taxistas", "modificarperfil taxista", "visualizar viajes taxista"

* Objetivo: "Gestionar reservas"
* Casos de uso: "realizar reserva","Recibir notificacion al taxista sobre el viaje", "recibir notificacion al cliente en caso de confirmación"

# Elemento de innovación

API de Google Maps, API geolocation, API OpenAI, Twilio (para enviar SMS), [posible añadido de sistema de pagos]
