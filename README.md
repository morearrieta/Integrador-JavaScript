Integrador Frontend
Proyecto de Sistema de Gestión de Pedidos para una empresa de Comidas
 
-->Descripción
   La aplicación permite al usuario:

   - **Buscar productos por nombre** usando una barra de búsqueda en la cabecera.
   - **Agregar productos** mediante un modal que se activa al hacer clic en el botón "Agregar elemento".
   - **Filtrar productos** por categorías desde un menú lateral.
   - **Visualizar los productos** en una tienda organizada en tarjetas.

-->Estructura del Proyecto
 HTML
  - El archivo `index.html` define la estructura básica de la página, incluyendo:
    - Un **header** con una barra de búsqueda y un botón para agregar productos.
    - Un **aside** con una lista de categorías.
    - Una **sección principal** donde se muestran los productos.
    - Un **modal** para agregar o modificar productos.

--> CSS
  - El archivo `style.css` se encarga del estilo de la aplicación:
     - Estilo general del **header**, la **barra de búsqueda** y los **botones**.
     - Diseño responsivo para el **contenedor de productos** y el **modal**.
     - Estilos específicos para listas, tarjetas de productos y el modal emergente.

-->JavaScript
  -El archivo `main.js` maneja la funcionalidad principal de la aplicación:

- **Módulos Importados**:
  - `renderCategories`: Función para renderizar las categorías disponibles.
  - `handleSearchProductByName`: Función que ejecuta la búsqueda de productos.
  - `openModal`: Muestra el modal para añadir o modificar un producto.
  - `handleGetProductToStore`: Carga los productos en la tienda.

- **Variables Globales**:
  - `categoriaActiva`: Representa la categoría seleccionada.
  - `productoActivo`: Representa el producto que está siendo visualizado o modificado.

- **Eventos**:
  - **Agregar Producto**: Al hacer clic en el botón "Agregar elemento", se abre un modal.
  - **Buscar Producto**: Al hacer clic en el botón de búsqueda, se ejecuta la búsqueda de productos por nombre.

Instalación y Uso

1. Clona el repositorio o descarga los archivos.
2. Descomprimir el archivo zip.
3. Abrir carepta con visual studio code
4. Abre el archivo `index.html` en un navegador.
5. Interactúa con la aplicación: busca productos, agrégalos o modifícalos mediante el modal.

Paginas utilizadas
- Iconos de Google Fonts (Material Symbols)
- Tipografías de Google Fonts: **Rubik** y **Varela**

