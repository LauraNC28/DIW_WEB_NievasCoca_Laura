# Proyecto de Blog de Cocina

Este proyecto consiste en la creación de una página web para un blog de cocina con las siguientes secciones:

* **Página de Aterrizaje:** Página de inicio del blog.
* **Página de Inicio:** Lista de recetas destacadas.
* **Recetas:** Sección con todas las recetas del blog.
* **Foro:** Espacio para que los usuarios compartan consejos y preguntas sobre cocina.
* **Sobre Mí:** Información sobre el autor del blog.
* **Contacto:** Formulario de contacto para comunicarse con el autor.
* **Cuenta:** Páginas de inicio de sesión y creación de cuentas.

## Propósito

El objetivo principal de este proyecto es crear una plataforma en línea donde los usuarios puedan encontrar recetas de cocina, interactuar con otros amantes de la cocina y aprender sobre el mundo culinario.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

* `html/`: Contiene los archivos HTML para todas las páginas del blog.
* `css/`: Contiene los archivos CSS compilados para los estilos de las páginas.
    * `main.css`: Archivo CSS principal que contiene todos los estilos compilados.
    * `main.css.map`: Archivo de mapa de origen para depurar estilos SCSS en el navegador.
* `sass/`: Contiene los archivos SCSS para los estilos de las páginas.
    * `componentes/`: Contiene estilos para componentes reutilizables.
    * `global/`: Contiene estilos globales para el proyecto.
    * `pages/`: Contiene estilos específicos para cada página.
    * `main.scss`: El archivo principal SCSS que importa todos los demás archivos SCSS.
* `assets/`: Contiene los recursos estáticos del proyecto.
    * `css/`: Contiene archivos CSS.
    * `webfonts/`: Contiene las fuentes web utilizadas en el proyecto.
* `media/`: Contiene archivos multimedia como imágenes.
    * `img/`: Contiene las imágenes utilizadas en el blog.
* `index.html`: La página principal del sitio web.
* `node_modules/`: Contiene las dependencias instaladas con npm.
* `.gitignore`: Especifica los archivos y carpetas que deben ignorarse en el control de versiones (Git).
* `package-lock.json`: Contiene información detallada sobre las dependencias instaladas.
* `package.json`: Contiene información sobre el proyecto y sus dependencias.
* `README.md`: Este archivo, que proporciona información sobre el proyecto.

## Configuración del Entorno

Para ejecutar este proyecto, necesitarás tener instalado lo siguiente:

* Un navegador web moderno (como Chrome, Firefox o Safari).
* Un editor de código (como VS Code, Sublime Text o Atom).
* Node.js y npm (si deseas compilar los archivos SCSS).

Se recomienda utilizar Node.js y Parcel.

### Instalación de Dependencias

1. Asegúrate de tener Node.js y npm instalados en tu sistema.
2. Abre una terminal en la raíz del proyecto y ejecuta el siguiente comando para instalar las dependencias:

    ```bash
    npm install
    ```