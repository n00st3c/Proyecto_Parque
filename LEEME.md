# Sitio de fichas — Parque de La Paloma

## Qué hay aquí
- `index.html` — listado general de las 15 especies (útil como página de inicio)
- `fichas/01-acalifa.html` ... `fichas/15-cheflera.html` — una ficha por especie
- `styles.css` — estilo compartido por todas las páginas
- `fotos/` — carpeta vacía donde debes añadir las fotografías

## Cómo añadir las fotos
Cada ficha busca automáticamente una imagen en `fotos/` con el mismo nombre (slug) que aparece en el nombre del archivo HTML, sin el número. Por ejemplo:

- `fichas/01-acalifa.html` → busca `fotos/acalifa.jpg`
- `fichas/02-flor-de-sangre.html` → busca `fotos/flor-de-sangre.jpg`
- `fichas/06-arbol-del-coral.html` → busca `fotos/arbol-del-coral.jpg`

Mientras no exista la foto, la ficha muestra automáticamente un marcador visual ("Fotografía pendiente"). En cuanto subas el archivo `.jpg` con el nombre correcto a la carpeta `fotos/`, la imagen aparece sola — no hace falta tocar el HTML.

Si prefieres usar `.png` en vez de `.jpg`, dímelo y ajusto las 15 páginas de una vez.

## Cómo subir esto a GitHub
1. Sube el contenido de esta carpeta (`index.html`, `styles.css`, `fichas/`, `fotos/`) a la raíz de tu repositorio `Proyecto_Parque`
2. Activa GitHub Pages apuntando a la rama `main`, carpeta `/ (root)`
3. Cada QR debe apuntar a su URL final, por ejemplo:
   `https://n00st3c.github.io/Proyecto_Parque/fichas/01-acalifa.html`

## Lista completa de URLs para generar los QR
01. fichas/01-acalifa.html
02. fichas/02-flor-de-sangre.html
03. fichas/03-cipres-comun.html
04. fichas/04-cipres-de-arizona.html
05. fichas/05-pata-de-vaca.html
06. fichas/06-arbol-del-coral.html
07. fichas/07-arbol-de-coral-de-los-cafres.html
08. fichas/08-benjamina.html
09. fichas/09-higuera.html
10. fichas/10-laurel-de-indias.html
11. fichas/11-higuera-de-natal.html
12. fichas/12-higuera-herrumbrosa.html
13. fichas/13-jacaranda.html
14. fichas/14-pitosporo.html
15. fichas/15-cheflera.html
