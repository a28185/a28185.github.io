# Torneo de Voleibol Local 2026

## Descripción del Proyecto
Este proyecto consiste en el diseño y desarrollo de una página web informativa para un **evento deportivo de voleibol** organizado por una entidad local. La web es estática, responsive y ha sido construida utilizando el framework **Bootstrap 5**.

## Estructura y Secciones (Grid de Bootstrap)
Para garantizar la adaptabilidad en móvil, tablet y escritorio, se ha utilizado el sistema de rejilla (grid) de Bootstrap:

* **Navbar:** Menú de navegación pegajoso (`sticky-top`) para facilitar el acceso a las secciones.
* **Hero Section:** Cabecera con imagen de impacto y degradado mediante CSS personalizado para presentar el evento.
* **Sección Información:** Uso de `row` con dos columnas de ancho medio (`col-md-6`) para separar los detalles del cronograma.
* **Sección Equipos:** Implementación de `row-cols-1 row-cols-md-2 row-cols-lg-5` para mostrar de forma dinámica 10 equipos inscritos.
* **Sección Premios:** Contenedor de ancho completo para organizar la información de galardones.
* **Footer:** Pie de página con créditos y notas legales.

## Componentes de Bootstrap Usados
Se han integrado los siguientes componentes prediseñados para mejorar la experiencia de usuario:
1.  **Cards:** Utilizadas para mostrar los nombres de los equipos con sombras (`shadow-sm`).
2.  **Accordion:** Implementado en la sección de premios para organizar el Top 3 de forma compacta y elegante.
3.  **List Groups:** Para presentar los detalles del evento (ubicación, fecha, hora) de forma limpia.
4.  **Buttons:** Botones de llamada a la acción con clases `btn-primary` y `btn-lg`.

## Historial de Commits (Rama: desarrollo-web)
El desarrollo se gestionó mediante una rama secundaria siguiendo un flujo de trabajo profesional:

* **Commit 1:** "Migración de estilos internos a archivo CSS externo". Mejora de la organización del código.
* **Commit 2:** "Creada carpeta CAPTURAS e incluida imagen del sitio web". Organización de evidencias.
* **Commit 3:** "Añadido acordeón de Bootstrap para la sección de premios del Top 3". Mejora de componentes complejos.

## Dificultad Encontrada y Solución
**Dificultad:** Durante la migración de estilos al archivo externo `style.css`, el diseño de la web dejó de cargar correctamente.

**Solución:** Se identificó que se habían incluido erróneamente las etiquetas HTML `<style>` dentro del archivo CSS. Tras eliminarlas y verificar el enlace `<link>` en el `index.html`, el diseño volvió a funcionar perfectamente.

---
*Proyecto realizado para la práctica de Diseño Web y Gestión de Archivos.*
