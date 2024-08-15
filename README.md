# 🎉 Sistema de Gestión de Eventos "Las Perlas"

## 🌟 Planteamiento de la Problemática

La empresa **"Las Perlas"** ofrece servicios de organización de eventos, como graduaciones, cumpleaños, matrimonios y más. Actualmente, los clientes deben acudir personalmente al local para hacer reservas, lo cual puede resultar inconveniente y poco eficiente. Esto no solo limita la accesibilidad para los clientes, sino que también genera una carga adicional para el personal del negocio, que debe gestionar todas las solicitudes de manera manual. Además, este proceso carece de la flexibilidad y rapidez que los clientes modernos esperan, lo que podría llevar a la pérdida de potenciales reservas y a una disminución en la satisfacción del cliente.
##  🌟 Objetivo general:
Desarrollar un sistema de gestión de eventos en línea para "Las Perlas" que permita a los clientes realizar reservas de manera rápida y conveniente a través de una página web, facilitando la administración de las solicitudes de reserva y mejorando la experiencia del cliente.
## 🎯 Objetivos Específicos

1. **🤖 Automatizar el proceso de reserva de eventos**: Implementar una plataforma web donde los clientes puedan seleccionar el tipo de evento, la decoración, el número de asistentes y la fecha deseada, enviando automáticamente la solicitud al administrador.
2. **🔄 Mejorar la gestión de reservas**: Proveer al administrador del sistema herramientas para revisar, confirmar o rechazar las reservas de manera eficiente, con un sistema de notificaciones que informe a los clientes sobre el estado de su solicitud.
3. **👥 Aumentar la accesibilidad y comodidad para los clientes**: Permitir que los clientes puedan realizar reservas desde cualquier lugar y en cualquier momento, eliminando la necesidad de visitar físicamente el negocio.
4. **📈 Optimizar la comunicación con los clientes**: Incorporar notificaciones automáticas que informen al cliente sobre la confirmación de la reserva, detalles adicionales del evento y recordatorios previos al mismo.

## 💡 Solución Propuesta

Se propone el desarrollo de un sistema de gestión de eventos para **"Las Perlas"** que funcione a través de una página web. El sistema permitirá a los clientes realizar reservas en línea, seleccionando el tipo de evento, la decoración y la cantidad de asistentes, y enviando su solicitud al administrador del negocio. El administrador podrá gestionar las reservas de manera eficiente, confirmando o rechazando solicitudes, y notificando automáticamente a los clientes sobre el estado de su reserva. Esto no solo mejorará la experiencia del cliente, sino que también optimizará las operaciones del negocio, aumentando su capacidad para atender a un mayor número de clientes y eventos.

## 📋 Requerimientos del Sistema

| ID     | Requerimiento                              | Descripción                                                                 | Prioridad | Tipo         |
|--------|--------------------------------------------|-----------------------------------------------------------------------------|-----------|--------------|
| RQ-01  | Registro de Usuarios                       | Permitir que los clientes se registren y creen una cuenta para realizar reservas. | Alta      | Funcional    |
| RQ-02  | Inicio de Sesión                           | Permitir que los usuarios registrados inicien sesión en su cuenta.        | Alta      | Funcional    |
| RQ-03  | Selección de Tipo de Evento                | Los clientes deben poder seleccionar el tipo de evento al hacer una reserva. | Alta      | Funcional    |
| RQ-04  | Personalización de Decoración              | Permitir a los clientes seleccionar opciones de decoración para su evento. | Media     | Funcional    |
| RQ-05  | Especificación de Número de Asistentes     | El cliente debe poder indicar el número de asistentes esperados.          | Alta      | Funcional    |
| RQ-06  | Selección de Fecha y Hora                  | El cliente debe poder seleccionar la fecha y hora para su evento.        | Alta      | Funcional    |
| RQ-07  | Solicitud de Reserva                       | Permitir al cliente enviar una solicitud de reserva.                      | Alta      | Funcional    |
| RQ-08  | Confirmación de Reserva por el Administrador | El administrador debe poder revisar y aprobar o rechazar las solicitudes. | Alta      | Funcional    |
| RQ-09  | Notificaciones Automáticas                 | Enviar notificaciones automáticas al cliente sobre el estado de su reserva. | Alta      | Funcional    |
| RQ-10  | Visualización de Reservas Confirmadas      | Permitir a los clientes visualizar sus reservas confirmadas.              | Alta      | Funcional    |
| RQ-11  | Gestión de Calendario                      | El administrador debe tener acceso a un calendario con todas las reservas. | Media     | Funcional    |
| RQ-12  | Reportes de Reservas                       | Generar reportes de reservas que el administrador pueda consultar.        | Baja      | Funcional    |
| RQ-13  | Interfaz de Usuario Intuitiva              | La interfaz debe ser intuitiva y fácil de usar para los clientes.        | Alta      | No Funcional |
| RQ-14  | Seguridad de Datos                         | Los datos de los usuarios deben estar protegidos con medidas de seguridad. | Alta      | No Funcional |
| RQ-15  | Escalabilidad                              | El sistema debe ser escalable para manejar un número creciente de usuarios.| Media     | No Funcional |

## 📊 Historias de Usuario

| ID    | Historia de Usuario                                     | Criterios de Aceptación                                                                                       | Prioridad | Estimación (Días) |
|-------|--------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-----------|--------------------|
| HU-01 | 👤 Registro e Inicio de Sesión                         | El sistema permite registrar un nuevo usuario y permite iniciar sesión con credenciales válidas.               | Alta      | 3                  |
| HU-02 | 📅 Selección de Evento y Decoración                   | El sistema muestra opciones de tipo de evento, decoración, y permite seleccionar fecha y hora.                 | Alta      | 4                  |
| HU-03 | 📝 Solicitud de Reserva                                | El sistema permite enviar la solicitud de reserva y el cliente recibe confirmación de envío.                   | Alta      | 2                  |
| HU-04 | ✅ Confirmación de Reserva por el Administrador        | El sistema muestra solicitudes de reserva pendientes y permite al administrador aprobar o rechazar.            | Alta      | 3                  |
| HU-05 | 🔔 Notificaciones Automáticas                           | El sistema envía notificaciones automáticas sobre el estado de la reserva al cliente.                          | Alta      | 2                  |
| HU-06 | 📅 Gestión de Reservas Confirmadas                     | El sistema muestra un calendario con todas las reservas confirmadas.                                          | Media     | 3                  |
| HU-07 | 📊 Generación de Reportes de Reservas                 | El sistema permite generar reportes en PDF o Excel, filtrables por fecha y tipo de evento.                    | Baja      | 3                  |
| HU-08 | 📱 Acceso desde Dispositivos Móviles                  | La página web es completamente responsiva y funcional en dispositivos móviles.                                | Alta      | 3                  |

## 📊 Diagrama de la Base de Datos

![Diagrama de la Base de Datos]!
![PERLAS](https://github.com/user-attachments/assets/8e447be5-302f-46dd-9b41-57cdb3079431)


## 📝 Bitácora

| Fecha       | Acción Realizada                  | Descripción                                 |
|-------------|-----------------------------------|---------------------------------------------|
| 2024-08-15  | Creación de la tabla `Bitacora`  | Se agregó la tabla para llevar control de cambios y registro de movimientos en el sistema. |

---


