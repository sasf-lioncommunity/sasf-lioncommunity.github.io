# SASF — DID (Detective Investigation Division)

Repositorio del sitio estático del Detective Investigation Division (DID) — San Andreas State Forces (SASF).

> Aviso: Este repositorio contiene páginas y recursos marcados como confidenciales. Su contenido es de uso interno y restringido a agentes autorizados.

## Contenido relevante

-   `index.html` — Página informativa del DID (confidencial) destinada a agentes autorizados.
-   `404.html` — Página de error 404 compatible con GitHub Pages.
-   `images/` — Recursos gráficos (se asume que `favicon.svg` y `did.webp` existen aquí).
-   `reports/` — Carpeta con informes (NO se listan ni se incluyen detalles aquí por motivos de confidencialidad). No referenciar estos archivos en documentación pública.

## Propósito

Este repositorio aloja una página estática de presentación y recursos internos del DID. Las páginas `did.html` y `404.html` están diseñadas con un estilo oscuro y confidencial inspirado en los informes operativos.

Nota importante: No publiques ni compartas material sensible del directorio `reports/` fuera de los canales oficiales del SASF.

## Previsualizar localmente

Para ver el sitio localmente (servidor HTTP simple), puedes usar Python (si está instalado). Desde la raíz del repositorio ejecuta:

```powershell
# sirve archivos en http://localhost:8000
python -m http.server 8000
```

Luego abre en tu navegador `http://localhost:8000/index.html` o `http://localhost:8000/404.html`.

Alternativamente, simplemente abre los archivos `index.html` o `404.html` con el navegador (ruta `file:///...`) para una vista previa rápida.

## Publicación en GitHub Pages

º
Si este repositorio está configurado para GitHub Pages (branch `main` o `gh-pages`), `404.html` será usado por GitHub Pages como página de error. Ten en cuenta la naturaleza confidencial de `index.html` — si no quieres que sea pública, no lo publiques en Pages o añade controles de acceso fuera de GitHub Pages.

## Seguridad y recomendaciones

-   Evita incluir credenciales, claves, o información personal sensible en el repositorio.
-   Si necesitas restringir acceso a páginas o archivos, considera moverlos a un repositorio privado o usar un servidor con autenticación.
-   Añade un `robots.txt` o meta `noindex` si no quieres que buscadores indexen el contenido.

## Contacto

Para cuestiones sobre el mantenimiento de este repositorio o sobre la seguridad de su contenido, consulta con el responsable del DID o el equipo de seguridad del SASF.
