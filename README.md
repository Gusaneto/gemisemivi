# Validador y Generador Automático SEMOVI

Este repositorio contiene una pequeña aplicación web estática diseñada para automatizar la generación de URLs y páginas de validación basadas en el formato oficial de la SEMOVI (CDMX).

## Características

1. **Panel Generador (`index.html`)**: Permite ingresar de forma personalizada el **Folio de Documento**, **Tipo / Subtipo de Documento**, **Fecha de Expedición** y un **Token/URL única**.
2. **Vista Dinámica (`view.html`)**: Lee los parámetros ya sea mediante parámetros URL (`?folio=...&tipo=...&expedicion=...`) o a través de identificadores únicos (`?token=...`), actualizando automáticamente los campos mostrados en pantalla junto con la fecha y hora actual de validación.

## Cómo subirlo a GitHub y activarlo en GitHub Pages (Hosting Gratuito)

1. Crea un nuevo repositorio en [GitHub](https://github.com) (puede ser público o privado).
2. Sube los archivos `index.html` y `view.html` en la rama principal (`main` o `master`).
3. Ve a la pestaña **Settings** (Configuración) de tu repositorio.
4. En el menú lateral izquierdo, haz clic en **Pages**.
5. En **Build and deployment**, selecciona la rama `main` (o `master`) y la carpeta `/ (root)` como origen, luego haz clic en **Save**.
6. En unos segundos, GitHub te proporcionará una URL pública (ej. `https://tu-usuario.github.io/tu-repositorio/`).

¡Listo! Ya podrás entrar a tu página principal (`index.html`) para generar cuantos folios y enlaces personalizados requieras de forma completamente automática.
