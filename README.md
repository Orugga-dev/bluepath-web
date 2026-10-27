# Bluepath · sitio web

Landing page de Bluepath, red curada de gobernanza y talento senior para el ecosistema emprendedor de LatAm.

## Qué hay acá

- `index.html`: la página completa, en un solo archivo. Sin librerías; la única dependencia externa es la tipografía Inter desde Google Fonts. Las fotos y el logotipo van embebidos.
- `brand/`: logotipo horizontal e isotipo (SVG y PNG) en sus variantes, las fotos de los fundadores y el manual de marca en texto (`MANUAL_DE_MARCA.md`) con la paleta, la tipografía y los tokens.

## Cómo se edita

Todo el contenido está en `index.html`, sección por sección, con los textos tal cual se leen. Los colores y tamaños salen de las variables definidas al inicio del `<style>` (`--teal`, `--ink`, etc.); cambiar un color ahí lo cambia en toda la página. La página tiene modo claro y oscuro según la preferencia del visitante.

## Publicación

El sitio se sirve con GitHub Pages desde la rama `main`. Cuando haya dominio propio, se agrega un archivo `CNAME` con el dominio y se apunta el DNS a GitHub Pages.

## Pendientes

- Correo de contacto: reemplazar los marcadores `[correo]` en la sección Hablemos y en el pie.
- Formulario: hoy es de muestra (no envía). Conectarlo a un servicio como Formspree, o reemplazarlo por un link a una agenda.
- Dominio y archivo `CNAME`.
- Logos de partners en Quiénes somos, cuando estén confirmados.
