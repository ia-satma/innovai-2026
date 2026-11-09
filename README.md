# InnovAI 2026 · 5° Foro de Innovación y Emprendimiento IMEF — landing

Sitio estático. No requiere build.

**Evento:** 3 de diciembre de 2026, 16:00 a 19:20 h · Salón Polivalente, Expedition FEMSA, Tec de Monterrey.
Organizan IMEF Grupo Monterrey y Tecnológico de Monterrey.

## Archivos
- `index.html`: la landing completa (HTML, CSS y JS en un solo archivo; Poppins y JetBrains Mono desde Google Fonts).
- `img/`: logos, fondos, íconos y fotos de ponentes (`img/cut/`, recortes con tratamiento unificado).
- `video/`: semblanzas en video (720p) y sus portadas.
- `server.js`: servidor estático con módulos nativos de Node.js (soporta Range para video).

## Editar contenido
Desde `index.html`:
- Fecha del contador: constantes `INICIO` y `FIN` (hora de Monterrey, UTC-6).
- Programa: bloque `#agenda` (cada fila lleva `data-ini` y `data-fin` para la etiqueta "EN VIVO").
- Semblanzas: objeto `P` en el script.
- Videos: lista `#lista` (cada botón lleva `data-v` con la ruta del MP4).
- Liga de registro: busca `https://www.imefmty.com`.

## Publicar en GitHub Pages
Settings → Pages → Deploy from a branch → rama `main`, carpeta `/ (root)`.

## Usar en Replit
Importa este repositorio desde GitHub. Replit usa `.replit` para correr `npm start` en el puerto 3000.
No hay dependencias que instalar.
