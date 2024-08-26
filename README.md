# 🎉 Sistema de Gestión de Eventos "Las Perlas"

![PERLAS](https://github.com/user-attachments/assets/d76ddbcd-93b1-4532-996a-319b5778e5a6)

## 📚 Información del Proyecto

**Materia:** Sistemas de Información III  
**Docente:** Ing. Jaime Zambrana Chacón  
**Integrantes:** 
- Jonathan Kenny Arias Fernández
- Roider Millares Mano
- Josue Huayllas Salazar
- Yorbin Afriel Mier Cabrera
- Harold Alexis Vargas

# 📅 Proyecto de Sistema de Gestión de Eventos para "Las Perlas"

## 1. Introducción

En la actualidad, la transformación digital se ha convertido en un factor crucial para la competitividad y eficiencia de las empresas. **"Las Perlas"**, un reconocido salón de eventos ubicado en el octavo anillo de la Avenida Virgen de Luján, se enfrenta a un reto común en el sector: la necesidad de modernizar su proceso de reservas para alinearse con las expectativas de los clientes y mejorar la eficiencia operativa.

El proceso actual de reserva de eventos en **"Las Perlas"** requiere que los clientes visiten el salón personalmente para realizar sus solicitudes. Este enfoque no solo limita la accesibilidad para quienes enfrentan dificultades para desplazarse, sino que también impone una carga significativa sobre el personal, que debe gestionar todas las reservas de manera manual. Como resultado, el negocio enfrenta desafíos en términos de rapidez, flexibilidad y satisfacción del cliente.

Para enfrentar estos desafíos, se propone el desarrollo de un sistema de gestión de eventos en línea. Este sistema permitirá a los clientes realizar reservas de manera sencilla y conveniente a través de una plataforma web, eliminando la necesidad de visitas físicas y optimizando el proceso de gestión de reservas. La implementación de esta solución digital no solo mejorará la experiencia del cliente, sino que también permitirá al negocio **"Las Perlas"** operar de manera más eficiente, respondiendo a las demandas de un mercado cada vez más orientado hacia la tecnología.

## 2. Descripción del Proyecto

### 2.1. Planteamiento de la problemática

**"Las Perlas"**, ubicado en el octavo anillo de la Avenida Virgen de Luján, zona Bateón, es un destacado salón de eventos especializado en la organización de graduaciones, cumpleaños, matrimonios y otras celebraciones. Sin embargo, el proceso actual de reservas presenta importantes inconvenientes. En lugar de ofrecer una opción de reserva en línea, los clientes deben acudir físicamente al salón para gestionar sus solicitudes. Este método tradicional resulta ineficiente y presenta varias limitaciones.

La necesidad de desplazarse hasta el local limita la accesibilidad para clientes que enfrentan dificultades para movilizarse o que prefieren realizar reservas desde la comodidad de sus hogares. Además, el proceso manual de gestión de reservas impone una carga significativa sobre el personal, que debe manejar y coordinar todas las solicitudes de forma manual. Esta situación no solo ralentiza el proceso de reserva, sino que también está en desacuerdo con las expectativas de rapidez y flexibilidad que demandan los clientes modernos.

Como resultado, la falta de una solución digital puede llevar a la pérdida de potenciales reservas y a una disminución en la satisfacción del cliente. La imposibilidad de realizar reservas en línea afecta negativamente la experiencia del usuario y limita el crecimiento y la competitividad del negocio en un mercado cada vez más orientado hacia la tecnología y la eficiencia.

### 2.2. Objetivo general

Desarrollar un sistema de gestión de eventos en línea para **"Las Perlas"** que permita a los clientes realizar reservas de manera rápida y conveniente a través de una página web, mejorando la experiencia del cliente y facilitando la administración de las solicitudes de reserva.

### 2.3. Objetivos específicos

- 🎯 **Automatizar el proceso de reserva de eventos:** Crear una plataforma web donde los clientes puedan seleccionar el tipo de evento, la decoración, el número de asistentes, y la fecha deseada, enviando automáticamente la solicitud al administrador.
- 📈 **Mejorar la gestión de reservas:** Dotar al administrador de herramientas que permitan revisar, confirmar o rechazar las reservas de manera eficiente. Además, incluir un sistema de notificaciones para mantener informados a los clientes sobre el estado de sus solicitudes.
- 🌐 **Aumentar la accesibilidad y comodidad para los clientes:** Permitir que los clientes puedan realizar reservas desde cualquier lugar y en cualquier momento, eliminando la necesidad de visitar físicamente el negocio.
- 🔔 **Optimizar la comunicación con los clientes:** Incorporar notificaciones automáticas que informen al cliente sobre la confirmación de la reserva, detalles adicionales del evento, y recordatorios previos al mismo.

### 2.4. Solución propuesta

Se propone desarrollar un sistema de gestión de eventos para **"Las Perlas"** accesible a través de una página web. Este sistema permitirá a los clientes realizar reservas en línea, seleccionando el tipo de evento y la cantidad de asistentes, y enviando la solicitud al administrador del negocio. El administrador podrá gestionar estas reservas de manera eficiente, confirmando o rechazando solicitudes, y notificando automáticamente a los clientes sobre el estado de su reserva. Además, el sistema generará un código QR con los detalles de la reserva y solicitará el pago del 50% del costo del evento dentro de un plazo de tres días para confirmar la reserva de manera definitiva. Esta solución no solo mejorará la experiencia del cliente, sino que también optimizará las operaciones del negocio, aumentando su capacidad para atender a un mayor número de clientes y eventos.

## 5. Product Backlog

### 5.1. Estructura del Product Backlog

| **ID** | **Requerimiento** | **Descripción** | **Tipo** | **Prioridad** |
|--------|-------------------|-----------------|----------|---------------|
| RF-01  | 📅 Selección de tipo de evento | El sistema debe permitir a los clientes seleccionar el tipo de evento desde la página web. | Funcional | Alta |
| RF-02  | 🧮 Ingreso de cantidad de asistentes y fecha | El sistema debe permitir a los clientes ingresar la cantidad de asistentes y la fecha del evento. | Funcional | Alta |
| RF-03  | 📨 Envío de solicitud de reserva | El sistema debe permitir a los clientes enviar una solicitud de reserva que sea recibida por el administrador. | Funcional | Alta |
| RF-04  | 📩 Notificación de estado de solicitud | El sistema debe notificar al cliente sobre el estado de su solicitud de reserva (aceptada o rechazada). | Funcional | Media |
| RF-05  | QR 📊 y Solicitud de Pago | El sistema debe generar un código QR con los detalles de la reserva y la solicitud de pago. | Funcional | Media |
| RF-06  | 🔔 Recordatorio de pago pendiente | El sistema debe enviar un recordatorio al cliente si no se ha realizado el pago dentro de los 3 días. | Funcional | Baja |
| RF-07  | 📋 Gestión de disponibilidad y reservas | El sistema debe permitir al administrador ver la disponibilidad de fechas y gestionar las reservas en función de la capacidad del evento. | Funcional | Alta |
| RNF-01 | 📱 Accesibilidad desde múltiples dispositivos | El sistema debe ser accesible desde cualquier dispositivo con conexión a internet, incluyendo móviles, Tablet y computadoras. | No Funcional | Alta |
| RNF-02 | 🔒 Seguridad de datos | El sistema debe garantizar la seguridad de los datos personales y de pago de los clientes. | No Funcional | Alta |
| RNF-03 | ⏱️ Tiempo de respuesta | El sistema debe responder a las solicitudes de los usuarios en un tiempo máximo de 3 segundos. | No Funcional | Media |
| T01    | ✅ Revisión de Requerimientos | Revisar y confirmar los requerimientos funcionales y no funcionales del Product Backlog. | Tarea Técnica | Alta |
| T02    | 🗂️ Creación de Diagrama de Casos de Uso | Elaborar el diagrama de casos de uso para visualizar las interacciones entre los usuarios y el sistema. | Tarea Técnica | Alta |
| T03    | 🛠️ Modelado de la Base de Datos | Diseñar el modelo de datos de la base de datos, incluyendo tablas, relaciones y atributos. | Tarea Técnica | Alta |
| T04    | 🏗️ Diseño de la Arquitectura del Sistema | Crear un esquema de la arquitectura del sistema que defina la estructura general del proyecto. | Tarea Técnica | Alta |
| T05    | 🖋️ Elaboración de Diagramas UML | Desarrollar diagramas UML detallados: Diagrama de Clases, Diagrama de Secuencia y Diagrama de Despliegue. | Tarea Técnica | Media |
| T06    | ⚙️ Configuración del Entorno de Desarrollo | Preparar el entorno de desarrollo, incluyendo la configuración de herramientas y repositorios. | Tarea Técnica | Alta |
| T07    | 🔄 Revisión del Product Backlog | Revisar y priorizar el Product Backlog para preparar las historias de usuario para el próximo sprint. | Tarea Técnica | Alta |
| T08    | 📅 Planificación del Sprint | Planificar el Sprint 1, asignar tareas y definir el objetivo del sprint. | Tarea Técnica | Alta |
| T09    | 📊 Reunión de Inicio del Sprint | Realizar la reunión de inicio del sprint para discutir el plan de trabajo y establecer expectativas. | Tarea Técnica | Alta |
| UI-01  | 🖥️ Creación de Página de Login | Diseñar y desarrollar la página de login. | Funcional | Alta |
| UI-02  | 🔑 Implementación de Autenticación | Desarrollar la funcionalidad de autenticación para el login. | Funcional | Alta |
| UI-03  | 📝 Creación de Página de Registro | Diseñar y desarrollar la página de registro. | Funcional | Alta |
| UI-04  | 🛡️ Implementación de Registro | Desarrollar la funcionalidad de registro de usuarios. | Funcional | Alta |

### 5.2. Definiciones de Hecho (Definition of Done)

1. **Requisitos Funcionales**: Cada requisito debe ser implementado, probado y validado en el entorno de desarrollo.
2. **Revisión de Código**: El código debe ser revisado y aprobado por otro desarrollador antes de ser integrado.
3. **Pruebas**: Todas las funcionalidades deben ser probadas unitariamente y en conjunto, y los errores identificados deben ser corregidos.
4. **Documentación**: La documentación técnica y de usuario debe estar completa y actualizada.
5. **Despliegue**: El sistema debe ser desplegado en el entorno de pruebas y validado por los usuarios finales.
6. **Aceptación del Usuario**: La funcionalidad debe ser aprobada por el Product Owner o representante del usuario final.

## 6. Entregables

1. **Sistema de Gestión de Eventos**: Plataforma web funcional para la gestión de reservas.
2. **Documentación Técnica**: Documentación detallada del sistema, incluyendo arquitectura, diseño y procedimientos.
3. **Manual de Usuario**: Guía para usuarios finales sobre cómo utilizar la plataforma.
4. **Informe de Pruebas**: Resultados de las pruebas realizadas, incluyendo pruebas unitarias, de integración y de aceptación.

---

*## 7.1 Herramientas Utilizadas

En el desarrollo de este proyecto, hemos empleado una variedad de herramientas y tecnologías para gestionar el frontend, backend, la base de datos y el control de versiones. A continuación, se detallan las herramientas principales:

- **🔧 Angular**: Framework de desarrollo web para construir aplicaciones de una sola página. Angular facilita la creación de aplicaciones ricas y dinámicas mediante el uso de TypeScript y la vinculación bidireccional de datos.

- **🚀 Vercel**: Plataforma para el despliegue de aplicaciones frontend, optimizada para proyectos construidos con frameworks modernos como Angular. Vercel proporciona un proceso de implementación simplificado y una infraestructura escalable para aplicaciones web.

- **🔥 Firebase**: Plataforma que ofrece una suite completa de servicios backend, incluyendo bases de datos en tiempo real, autenticación de usuarios y almacenamiento. En este proyecto, Firebase se utiliza para manejar la autenticación de usuarios y almacenar datos de manera eficiente.

- **🔄 Git**: Sistema de control de versiones distribuido que permite gestionar y rastrear los cambios en el código fuente. Git facilita la colaboración entre los miembros del equipo, asegurando un historial completo de cambios y la capacidad de revertir modificaciones si es necesario.

- **🐙 GitHub**: Plataforma de alojamiento para proyectos que utilizan Git. GitHub proporciona una interfaz web para la gestión de repositorios, facilitando la colaboración en equipo, la revisión de código y la gestión de problemas. En este proyecto, GitHub se usa para alojar el repositorio del código fuente y coordinar el trabajo del equipo.

- **🤖 GitHub Actions**: Herramienta de integración continua y entrega continua (CI/CD) que permite automatizar los flujos de trabajo de desarrollo, incluyendo la construcción, pruebas y despliegue del código. GitHub Actions facilita la automatización de tareas repetitivas y asegura la calidad del código a través de pruebas automatizadas.

- **🌟 Tailwind CSS**: Framework CSS altamente personalizable que permite crear interfaces modernas y responsivas utilizando clases de utilidad predefinidas. Tailwind CSS acelera el proceso de diseño y asegura consistencia visual en todo el proyecto.

- **💻 JavaScript (JS)**: Lenguaje de programación esencial para el desarrollo web, utilizado para crear páginas interactivas y dinámicas. JavaScript maneja la lógica del frontend, mejorando la experiencia del usuario mediante la manipulación del DOM, gestión de eventos e interacción con APIs.

- **📝 Visual Studio Code (VS Code)**: Editor de código fuente robusto y extensible que soporta múltiples lenguajes de programación, incluyendo JavaScript y TypeScript. VS Code ofrece herramientas integradas para la depuración, la gestión de proyectos y la integración con sistemas de control de versiones como Git, optimizando el flujo de trabajo de desarrollo.

