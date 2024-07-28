# Proyecto-grupal

Clase 7: Trabajo integrador
Proyecto: Desarrollo de un sitio web para una tienda online
 
Descripción del Proyecto
Desarrollar un sitio web responsivo para una tienda online que permita a los usuarios explorar los productos desde diferentes dispositivos, como computadoras de escritorio, tablets y celulares (3 resoluciones).
 
Características del Sitio Web
Frontend
- Diseño responsivo utilizando Bootstrap para garantizar una experiencia de usuario consistente en diferentes dispositivos y tamaños de pantalla.
- Página principal que muestra los productos destacados y las promociones actuales de la tienda.
- Páginas de categorías que permiten a los usuarios explorar productos por categorías específicas (definan máximo 2 categorías)
- Página de detalles del producto que muestra información detallada sobre un producto seleccionado (pueden trabajar con un máximo de 3 productos por categoría).
 
Git
- Utilización de Git para el control de versiones del código fuente del proyecto.
- Implementación de ramas para trabajar en diferentes características o correcciones de forma aislada.
- Uso de commits descriptivos y mensajes claros para documentar los cambios realizados.
 
Entrega del Proyecto
- Desarrollo del sitio web completo, incluyendo frontend responsivo y optimizado para distintos dispositivos y orientaciones.
- Documentación del código que explique la estructura del proyecto, las decisiones de diseño y las funcionalidades implementadas.
- Implementación de Git para el control de versiones del código y la colaboración entre los miembros del equipo.
 
Resolución:

# Página Web para Peluquería/Barbería

Este proyecto es una página web para una peluquería/barbería, diseñada con HTML5, CSS3, y Bootstrap. Utiliza también Font Awesome para iconos y ofrece una interfaz estilizada y responsiva.

## Descripción

El código HTML de la página comienza con la estructura básica de un documento HTML5 e incluye las secciones necesarias para crear una experiencia de usuario completa y profesional.

### Estructura del Código

- **Estructura HTML5 básica:** La página comienza con la declaración `<!doctype html>`, y etiquetas `<html>`, `<head>`, y `<body>`.
- **Head:** Incluye las etiquetas `<meta>` necesarias para configurar el juego de caracteres a UTF-8 y asegurar la responsividad en dispositivos móviles con `viewport`. Además, se incluyen enlaces a hojas de estilo CSS como Bootstrap y Font Awesome, una hoja de estilos personalizada (`style.css`), y un favicon.
- **Body:** Contiene las siguientes secciones:

  - **Header:** Incluye un `navbar` de Bootstrap con un logo, un botón para colapsar el menú en pantallas pequeñas, y enlaces de navegación a las secciones de "Nosotros", "Productos Destacados", "Categorías", y "Contacto". El `navbar` está fijado en la parte superior de la pantalla y tiene un fondo oscuro.
  - **Carrusel de fotos:** Utilizando Bootstrap, muestra tres imágenes con controles para navegar entre ellas. La sección tiene un margen superior para evitar que el contenido quede oculto detrás del `navbar`.
  - **Productos destacados:** Contiene un título centrado y tres tarjetas (`cards`), cada una mostrando un servicio ofrecido (Afeitado a Navaja, Peinado de Novia, y Coloración). Cada tarjeta incluye una imagen, un título y una descripción breve del servicio.
  - **Logos de métodos de pago:** Muestra un carrusel continuo con logos de diversas opciones de pago disponibles.
  - **Footer:** Incluye enlaces a diferentes secciones de la página y iconos de redes sociales con enlaces a las cuentas de Twitter, Facebook, Instagram, y LinkedIn de la peluquería/barbería. También muestra un mensaje de derechos reservados.

### Scripts

- Enlaces a los archivos JavaScript de Popper.js y Bootstrap, necesarios para algunas funcionalidades de Bootstrap.
- Un archivo de scripts personalizado (`scripts.js`) para cualquier funcionalidad adicional que necesite la página.

## Instalación

1. Clonar el repositorio:
    ```sh
    git clone https://github.com/tu-usuario/peluqueria-barberia.git
    ```
2. Abrir el archivo `index.html` en tu navegador preferido.

## Uso

- Navegar por la página utilizando el menú de navegación.
- Explorar los servicios destacados y los métodos de pago disponibles.
- Contactar a la peluquería/barbería a través de los enlaces de redes sociales.
