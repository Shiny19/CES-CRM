Implementación Front-End de CES (CRM Experts)

Avance del Proyecto

Autores:
Juan José Rincón; Alejandro Sierra Garzón; Armando Andrés Hernández

Institución: Politécnico Grancolombiano
Programa: Ingeniería de Software
Curso: Front-End
Profesor: John Alirio Olarte Ramos
Fecha: 30 de septiembre de 2025

Resumen

Este documento presenta el avance del proyecto de desarrollo del sitio web corporativo para la empresa CES — CRM Experts, enfocado en soluciones CRM personalizadas. Se describen las vistas implementadas en la versión inicial, así como las funcionalidades logradas mediante el uso de HTML, CSS y JavaScript. El objetivo principal es construir una interfaz responsive, funcional y orientada a capturar clientes interesados en servicios CRM.

1. Vistas desarrolladas y funcionalidad
   1.1 Página de inicio (index.html)

Objetivo: servir como punto de entrada al sitio y comunicar la propuesta de valor.

Componentes implementados: navegación principal, sección hero, características del servicio, vista previa de planes y pie de página.

Funcionalidad: enlaces funcionales hacia las demás páginas y botones de acción.

1.2 Página de inicio de sesión (login.html)

Objetivo: permitir el acceso de usuarios registrados.

Componentes: formulario con correo y contraseña, botón para inicio con Google (simulado) y enlace para recuperación.

Funcionalidad: validación básica y manejo del formulario mediante JavaScript.

1.3 Página de planes y precios (plans.html)

Objetivo: presentar los planes de servicio ofrecidos.

Componentes: tres tarjetas de planes (Crecimiento, Profesional y Empresas), beneficios y botón de contacto.

Funcionalidad: navegación y diseño responsivo adaptado a dispositivos móviles.

1.4 Página de empresa (about.html)

Objetivo: presentar la identidad, valores y equipo de la compañía.

Componentes: misión, visión, valores corporativos e información del equipo.

Funcionalidad: navegación e información estructurada para fortalecer la confianza del usuario.

1.5 Formulario de contacto (contact.html)

Objetivo: permitir el envío de solicitudes o cotizaciones.

Componentes: formulario con campos obligatorios (nombre, correo, teléfono y mensaje) y selector de tipo de consulta.

Funcionalidad: simulación de envío con retroalimentación visual.

1.6 Componente de chatbot

Objetivo: ofrecer atención al usuario mediante asistente interactivo.

Componentes: ventana emergente y campo de preguntas.

Funcionalidad: respuestas simuladas mediante JavaScript.

2. Estructura del repositorio
   /
   ├─ index.html
   ├─ login.html
   ├─ plans.html
   ├─ about.html
   ├─ contact.html
   └─ assets/
   ├─ css/style.css
   ├─ js/main.js
   └─ images/

3. Estado actual del proyecto

Sitio web estático funcional

Diseño responsivo aplicado

Formularios con validaciones básicas

Interacciones iniciales con JavaScript

Arquitectura modular de archivos

4. Próximos pasos

Integrar iconografía e ilustraciones finales

Mejorar accesibilidad (contrastes, etiquetas ARIA, semántica)

Conectar formularios con backend y servicio de correo

Implementar autenticación real (incluyendo OAuth)

Documentación final con metodología y pruebas UX

Despliegue en hosting y dominio

5. Referencias (se agregarán en la entrega final)

Documentación oficial HTML, CSS y JavaScript

Recursos de diseño UI y accesibilidad

Guías de buenas prácticas para interfaces web

Anexos

Capturas de pantalla de las vistas desarrolladas

Enlace al repositorio: https://github.com/Shiny19/CES-CRM.git