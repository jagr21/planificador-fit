# ⚡ PowerPlan PRO - Dashboard de Nutrición Inteligente

> **La gestión nutricional de nueva generación para entrenadores y profesionales del fitness.**

PowerPlan PRO es una aplicación web de alto rendimiento diseñada para que coaches y nutricionistas puedan gestionar sus alumnos, planificar dietas basadas en datos biométricos y realizar un seguimiento exhaustivo de macros y calorías con una interfaz ultra-moderna.

![Tecnologías](https://img.shields.io/badge/Tech-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![Supabase](https://img.shields.io/badge/Backend-Supabase-3EC988?style=for-the-badge&logo=supabase)
![JavaScript](https://img.shields.io/badge/Language-JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript)

## ✨ Características Principales

*   **🎯 Gestión Centralizada de Alumnos:** Panel lateral interactivo para alternar entre perfiles de clientes de forma instantánea.
*   **🔥 Calculadora Biométrica Avanzada:** Implementación de la fórmula de *Mifflin-St Jeor* para determinar TMB y GED según actividad y objetivos (Hipertrofia, Definición, Mantenimiento).
*   **🍱 Planificador de Comidas Dinámico:** Interfaz de arrastrar y soltar (en desarrollo) con búsqueda en tiempo real en base de datos nutricional.
*   **📊 Monitor de Macros en Tiempo Real:** Visualización clara de Proteínas, Carbohidratos, Grasas y Balance Hídrico.
*   **📄 Exportación Profesional:** Generador de planes nutricionales en PDF con diseño optimizado para impresión y alta legibilidad.
*   **🌓 Interfaz Glassmorphism:** Estética moderna con efectos de desenfoque, gradientes vibrantes y diseño totalmente *responsive* (Mobile First).

## 🛠️ Stack Tecnológico

*   **Frontend:** HTML5, CSS3 (Tailwind CSS) y JavaScript Vanilla.
*   **Backend as a Service:** [Supabase](https://supabase.com/) (Autenticación, Base de Datos PostgreSQL en tiempo real).
*   **Iconografía:** [Lucide Icons](https://lucide.dev/).
*   **Exportación:** [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/).
*   **Avatares:** [UI Avatars API](https://ui-avatars.com/).

## 🚀 Instalación y Configuración

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/powerplan-pro.git
    ```
2.  **Configura Supabase:**
    *   Crea un proyecto en Supabase.
    *   Ejecuta el script SQL (ubicado en `/sql/setup.sql`) para crear las tablas `profiles`, `comidas`, `suplementos` y `notas`.
    *   Configura las políticas de seguridad (RLS) para que los entrenadores solo vean a sus propios alumnos.
3.  **Variables de Entorno:**
    *   Actualiza las constantes `SUPABASE_URL` y `SUPABASE_KEY` en el archivo `fitness-dashboard.html` con tus credenciales.

## 📱 Vista Previa (Mobile & Desktop)

El dashboard se adapta automáticamente a cualquier dispositivo. En la versión móvil, la gestión de alumnos se despliega mediante un menú lateral inteligente para priorizar la visualización del plan de comidas.

---

## 📝 Notas de Desarrollo

Este proyecto ha sido diseñado priorizando la **Velocidad de Usuario (UX)**. El sistema de *onboarding* detecta nuevos registros y guía al entrenador en la creación de su primer perfil para una experiencia "zero-friction".

---

Desarrollado con ❤️ por [Tu Nombre/Marca]

<!--
[PROMPT_SUGGESTION]¿Puedes crear el archivo setup.sql con las tablas necesarias para que el proyecto funcione en Supabase?[/PROMPT_SUGGESTION]
[PROMPT_SUGGESTION]¿Cómo puedo añadir un gráfico de progreso de peso usando Chart.js en este dashboard?[/PROMPT_SUGGESTION]
-->