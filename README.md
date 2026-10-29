# FútbolClub Pro ⚽

**Plataforma web en desarrollo para la gestión de clubes y escuelas deportivas.**

**Laravel · PHP · Livewire · MySQL/SQLite · Testing · Arquitectura multi-club**

> **Estado:** MVP en evolución. Este repositorio es una presentación pública del proyecto; **no contiene su código fuente ni datos de usuarios**.

## El proyecto

FútbolClub Pro busca simplificar el trabajo cotidiano de clubes, escuelas y entrenadores mediante una herramienta centralizada para organizar jugadores, categorías, eventos, convocatorias y asistencias.

El objetivo es construir una aplicación mantenible y adaptable a múltiples instituciones, con controles de acceso según el club y la función de cada usuario.

## Funcionalidades desarrolladas

- **Organización institucional:** clubes, sedes, categorías y jugadores.
- **Gestión de actividades:** entrenamientos, partidos y reuniones, con estados y filtros de consulta.
- **Convocatorias:** preparación y seguimiento de invitaciones a las actividades.
- **Confirmaciones de asistencia (RSVP):** respuestas a través de enlaces individuales.
- **Registro deportivo:** asistencia y datos relacionados con entrenamientos o partidos.
- **Trabajo en equipo:** gestión de personal e invitaciones para colaborar en un club.
- **Vínculos familiares:** gestión de responsables de jugadores.

Las funcionalidades descritas están respaldadas por componentes y rutas en el repositorio privado. Su disponibilidad en una instalación pública o comercial **no está anunciada**.

## Enfoque de ingeniería

### Arquitectura multi-club

El proyecto utiliza un contexto de club activo y políticas de autorización para limitar el acceso a información y operaciones de cada institución.

### Calidad y pruebas

Incluye pruebas automatizadas con PHPUnit para autenticación, permisos, aislamiento de datos, gestión de eventos, convocatorias y asistencia. En una ejecución **local** realizada el 29 de octubre de 2026 se registraron **408 pruebas aprobadas y 1.270 aserciones** (captura de consola). Estas cifras corresponden a esa ejecución local, no a la cantidad de pruebas del entorno de GitHub Actions.

### Integración continua (CI)

El **29 de octubre de 2026**, GitHub Actions ejecutó satisfactoriamente la suite automatizada sobre la rama principal `main` en **PHP 8.2, 8.3 y 8.4**. El flujo prepara el entorno PHP, instala dependencias con Composer, compila los recursos frontend con Vite y ejecuta `php artisan test`.

Este control se activa automáticamente al incorporar cambios en `main` y también se utiliza para revisar Pull Requests. Los resultados de CI corresponden al código disponible en el momento de cada ejecución; no garantizan ausencia de errores.

### Desarrollo incremental

El trabajo se organiza en módulos y mejoras progresivas, con atención a la validación de datos, el mantenimiento del código y las reglas de negocio.

## Tecnologías

- PHP 8.2+ y Laravel 12
- Livewire 3, Livewire Volt y Blade
- Eloquent ORM y bases de datos relacionales
- Spatie Laravel Permission y políticas de autorización
- PHPUnit, Git y GitHub
- Vite, JavaScript y Tailwind CSS

## Estado y próximos pasos

El producto continúa en desarrollo. Los módulos económicos, como cuotas, cobros e integraciones de pago, **no se presentan como funciones operativas** en este momento.

Los próximos objetivos incluyen continuar ampliando las pruebas y su automatización, revisar los controles de privacidad y seguir mejorando la experiencia de entrenadores y administradores.

## Código fuente y privacidad

El código principal se conserva en un repositorio **privado** porque se está evaluando su posible uso comercial.

Esta presentación no publica lógica de negocio interna, implementaciones, bases de datos, información de menores, fotografías de usuarios ni enlaces privados de confirmación.

## Autor

**Gabriel Molina** — Técnico Superior en Programación · Desarrollador backend PHP/Laravel.

- [GitHub](https://github.com/Jgmdevelopers)
- [LinkedIn](https://www.linkedin.com/in/gabriel-molina-ush/)

---

*Presentación informativa de un proyecto propio en evolución. No constituye una demostración en vivo ni una promesa de disponibilidad comercial.*
