# INDEX Revistas

Una herramienta de **INDEX**.

Herramienta web para encontrar revistas científicas afines a un artículo, con cuartil SCImago 2025,
cobertura en Scopus hasta 2026, APC, idioma y región.

## Archivos
- `index.html`: la aplicación completa (HTML, CSS y JavaScript en un solo archivo).
- `data.json`: catálogo de 44 837 revistas (SCImago Journal Rank 2025 y DOAJ al 23 sep 2026), con sitios web y temas de OpenAlex.
- `topics.json`: 4 516 temas de investigación de OpenAlex con sus palabras clave, usados para identificar el tema del artículo.

## Publicar en GitHub Pages
1. Crea un repositorio público y sube estos archivos a la raíz.
2. En Settings → Pages, elige la rama `main` y la carpeta `/ (root)`.
3. La web queda en `https://<tu-usuario>.github.io/<repositorio>/`.

## Fuentes de datos
- SCImago Journal & Country Rank (https://www.scimagojr.com). Revisar sus términos de uso antes de cualquier uso comercial.
- Directory of Open Access Journals, DOAJ (https://doaj.org), datos CC0.
- OpenAlex (https://openalex.org), datos CC0, vía el proyecto JournalScope (https://github.com/narassima/JournalFinder).
