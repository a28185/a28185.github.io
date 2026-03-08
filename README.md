# Torneo de Voleibol Local 2026 🏐

## Descripción del Proyecto
[cite_start]Este proyecto consiste en el diseño y desarrollo de una página web informativa para un **evento deportivo de voleibol** organizado por una entidad local[cite: 2, 7]. [cite_start]La web es estática, responsive y ha sido construida utilizando el framework **Bootstrap 5**[cite: 15, 21].

## Estructura y Secciones (Grid de Bootstrap)
[cite_start]Para garantizar la adaptabilidad en móvil, tablet y escritorio, se ha utilizado el sistema de rejilla (grid) de Bootstrap[cite: 6, 28]:

* [cite_start]**Navbar:** Menú de navegación pegajoso (`sticky-top`) para facilitar el acceso a las secciones[cite: 26].
* [cite_start]**Hero Section:** Cabecera con imagen de impacto y degradado mediante CSS personalizado para presentar el evento[cite: 27, 31].
* [cite_start]**Sección Información:** Uso de `row` con dos columnas de ancho medio (`col-md-6`) para separar los detalles del cronograma[cite: 28].
* [cite_start]**Sección Equipos:** Implementación de `row-cols-1 row-cols-md-2 row-cols-lg-5` para mostrar de forma dinámica 10 equipos inscritos[cite: 28].
* **Sección Premios:** Contenedor de ancho completo para organizar la información de galardones.
* [cite_start]**Footer:** Pie de página con créditos y notas legales[cite: 30].

## Componentes de Bootstrap Usados
[cite_start]Se han integrado los siguientes componentes prediseñados para mejorar la experiencia de usuario[cite: 29, 37]:
1.  [cite_start]**Cards:** Utilizadas para mostrar los nombres de los equipos con sombras (`shadow-sm`)[cite: 29].
2.  [cite_start]**Accordion:** Implementado en la sección de premios para organizar el Top 3 de forma compacta y elegante[cite: 29].
3.  **List Groups:** Para presentar los detalles del evento (ubicación, fecha, hora) de forma limpia.
4.  **Buttons:** Botones de llamada a la acción con clases `btn-primary` y `btn-lg`.

## Historial de Commits (Rama: desarrollo-web)
[cite_start]El desarrollo se gestionó mediante una rama secundaria siguiendo un flujo de trabajo profesional[cite: 16, 40, 77]:

* **Commit 1:** "Migración de estilos internos a archivo CSS externo". [cite_start]Mejora de la organización del código[cite: 38].
* **Commit 2:** "Creada carpeta CAPTURAS e incluida imagen del sitio web". [cite_start]Organización de evidencias[cite: 38, 42].
* **Commit 3:** "Añadido acordeón de Bootstrap para la sección de premios del Top 3". [cite_start]Mejora de componentes complejos[cite: 38].

## Dificultad Encontrada y Solución
[cite_start]**Dificultad:** Durante la migración de estilos al archivo externo `style.css`, el diseño de la web dejó de cargar correctamente[cite: 39].
**Solución:** Se identificó que se habían incluido erróneamente las etiquetas HTML `<style>` dentro del archivo CSS. [cite_start]Tras eliminarlas y verificar el enlace `<link>` en el `index.html`, el diseño volvió a funcionar perfectamente[cite: 39].

---
*Proyecto realizado para la práctica de Diseño Web y Gestión de Archivos.*
