# a28185.github.io

# 1. Descripción del proyecto
Este sitio web ha sido diseñado para promocionar un evento ficticio de voleibol abierto al público organizado por una entidad local. El objetivo es presentar la información esencial (qué, cuándo y dónde) de forma clara, atractiva y totalmente accesible desde cualquier dispositivo.

# 2. Estructura y Diseño con Bootstrap 5
La web se ha construido utilizando Bootstrap 5 vía CDN , empleando una estructura responsive que se adapta a móvil, tablet y escritorio.

#   Secciones y Grid:
  - Navbar: Menú de navegación fijo en la parte superior.
  - Hero Section: Banner principal con el título del evento y llamada a la acción.
  - Sección de Información (Grid): Estructura de 2 columnas en escritorio (col-md-6) que pasan a 1 columna en móvil
  - Sección de Actividades (Grid): Uso de 3 columnas (col-lg-4) para mostrar los diferentes talleres o charlas.
  - Footer: Pie de página con datos de contacto y redes sociales.

#   Componentes Bootstrap Utilizados
    Se han implementado los siguientes componentes de la documentación oficial:
    - Cards: Para presentar de forma visual los ponentes o actividades.
    - Buttons: Estilizados con clases de Bootstrap para la interacción del usuario.
    
# 3. Gestión de Versiones (GitHub)
El desarrollo se ha gestionado siguiendo un flujo de trabajo profesional mediante ramas:
- Rama Principal (main): Contiene la versión estable y final del proyecto.
- Rama Secundaria (desarrollo/feature): Utilizada para la construcción de los componentes antes de la fusión final.

# Historial de Commits Significativos
1. Commit 1: Estructura básica HTML5, enlace a CDN de Bootstrap e implementación de Navbar y Hero.
2. Commit 2: Creación de las dos secciones principales de contenido utilizando el sistema de Grid (rows y cols).
3. Commit 3: Inserción de componentes (Cards/Accordion), estilos CSS propios para ajustes visuales y Footer.

Nota: La fusión de la rama secundaria se realizó mediante un Pull Request correctamente finalizado.

# 4. Dificultades y Soluciones
- Dificultad: Ajustar el comportamiento de las columnas en tablets para que no se viera amontonado.
- Solución: Ejemplo: Se utilizaron los breakpoints intermedios de Bootstrap (col-sm o col-md) para asegurar una lectura cómoda.

# 5. Capturas de Pantalla
Las capturas del diseño final se encuentran alojadas en la carpeta /CAPTURAS de este repositorio, cumpliendo con los criterios de legibilidad exigidos.



# Plus Optativo Realizado
- Instalación y uso de GitHub Desktop para la gestión del repositorio.
- Vinculación de Visual Studio Code con la cuenta de GitHub para realizar los commits directamente desde el editor.
