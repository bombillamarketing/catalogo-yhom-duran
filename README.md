# Catálogo Yhom Durán

Catálogo de motos con financiamiento semanal de Yhom Durán (Barquisimeto).

- **Página publicada:** https://bombillamarketing.github.io/catalogo-yhom-duran/
- **Datos editables (Google Sheets):** https://docs.google.com/spreadsheets/d/1sOo5hTTupoKEGwS-i71Lc8mWfvkygHMlNqapthiSeag/edit
- **Carpeta para fotos (Google Drive):** https://drive.google.com/drive/folders/1FBYdL8B-FXAp9D1J3yow0cCwtJsN0DfT

## Cómo se actualiza

La página lee la hoja de Google Sheets cada vez que alguien la abre. Para cambiar precios, fotos, horario, recaudos o preguntas frecuentes, se edita la hoja; no hace falta tocar este repositorio. La pestaña **Cómo usar** de la hoja explica cada columna.

Si la hoja no responde (por ejemplo, si deja de estar compartida), la página muestra los datos que trae incluidos en `index.html`, que son los del día en que se publicó.

## Requisitos de la hoja

- Compartida como **Cualquier persona con el enlace: Lector**.
- Pestañas con estos nombres exactos: `Motos`, `Ajustes`, `Recaudos`, `Preguntas`.
- No cambiar los títulos de la fila 1.

## Cambiar de hoja

Si algún día se usa otra hoja (por ejemplo, una copia), cambia el ID en esta línea de `index.html`:

```js
var SHEET_ID='1sOo5hTTupoKEGwS-i71Lc8mWfvkygHMlNqapthiSeag';
```

El ID es la parte del enlace de la hoja que va entre `/d/` y `/edit`.
