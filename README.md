# Demo de login con Tailwind CSS

Proyecto de práctica con dos pantallas estáticas de inicio de sesión. El aporte del proyecto es integrar las plantillas HTML con Tailwind CSS 4.1.3 y mostrar cómo generar una hoja de estilos local a partir de las clases usadas en ellas.

## Ver las pantallas

Abre [templates/index.html](templates/index.html) o [templates/login.html](templates/login.html) en tu navegador. El archivo generado `output.css` está incluido para que puedas ver los estilos sin instalar dependencias. Los controles son de demostración y no implementan autenticación.

## Regenerar el CSS

Con Node.js y npm instalados, ejecuta estos comandos desde la raíz del proyecto:

```sh
npm ci
npm run build
```

Usa `npm run watch` para regenerar el CSS mientras editas las plantillas. Tailwind toma `input.css` como entrada, detecta las clases usadas en `templates/` y escribe el resultado en `output.css`.

## Créditos

La pantalla `templates/index.html` se basa en el [ejemplo de inicio de sesión de Flowbite](https://flowbite.com/blocks/marketing/login/) e incluye su logotipo. La procedencia de la segunda plantilla y del SVG de Google incluido en ella está pendiente de confirmar.
