https://addons.mozilla.org/en-US/firefox/addon/styl-us/

```css
/* Dos crímenes en uno, carga Roman Elegance y encima de una ruta absoluta */

@font-face {
    font-family: 'RomanElegance';
    src: url('https://crujera.galnod.com/stylus/RomanElegance-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
}

@font-face {
    font-family: 'RomanElegance';
    src: url('https://crujera.galnod.com/stylus/RomanElegance-Bold.ttf') format('truetype');
    font-weight: bold;
    font-style: normal;
}

@font-face {
    font-family: 'RomanElegance';
    src: url('https://crujera.galnod.com/stylus/RomanElegance-Italic.ttf') format('truetype');
    font-weight: normal;
    font-style: italic;
}

@font-face {
    font-family: 'RomanElegance';
    src: url('https://crujera.galnod.com/stylus/RomanElegance-BoldItalic.ttf') format('truetype');
    font-weight: bold;
    font-style: italic;
}

* {
    font-family: 'RomanElegance', serif !important;
}

```
