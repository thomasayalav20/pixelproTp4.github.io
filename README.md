# PixelPro — TP4

**Proyecto:** Portal gamer PixelPro · Integrador de Programación Web TP4–TP8.

**Instalación previa:** colocar `PixelPro/` en `C:\xampp\htdocs\`, encender Apache y MySQL, importar `PixelPro/database/schema.sql` en phpMyAdmin y configurar `PixelPro/config/.env` a partir de `.env.example` sin compartir las credenciales. Abrir `http://localhost/PixelPro/`.

## Objetivo

Migrar el sitio a PHP, reutilizar partes comunes y separar estructura, diseño e interactividad.

## Implementación

- `index.php`: portada principal de PixelPro.
- `includes/header.php` y `includes/footer.php`: elementos compartidos entre páginas.
- `includes/nav.php`: navegación reutilizable.
- `todo.css` y `todo.js`: estilos y comportamientos separados del PHP.
- `config/env.php`: lectura de configuración.

## Cómo demostrarlo

1. Abrí `http://localhost/PixelPro/index.php` y mostrá portada y menú.
2. Navegá a Noticias, Blog y Contacto para comprobar que comparten el encabezado.
3. Abrí VS Code y mostrá la carpeta `includes` y una línea `require` que importa header/footer.
4. Mostrá `todo.css` y `todo.js` como archivos independientes.


## Evidencias fotográficas (capturas reales)

Las siguientes imágenes están guardadas en la carpeta **`capturas de limon/capturas ayala tp4/`**. Los enlaces son relativos a este README ubicado en `PixelPro/docs/`. Se respetaron los nombres originales, incluidos los dos espacios del TP5.

### Portada principal de PixelPro

![Portada principal de PixelPro](../capturas%20de%20limon/capturas%20ayala%20tp4/tp4-inicio.png)

### Archivos compartidos PHP

![Archivos compartidos PHP](../capturas%20de%20limon/capturas%20ayala%20tp4/tp4-includes.png)

### Navegación entre páginas

![Navegación entre páginas](../capturas%20de%20limon/capturas%20ayala%20tp4/tp4-navegacion.png)

> Las capturas son evidencia de la instalación local. Antes de publicarlas, revisá que no muestren datos personales o credenciales.
