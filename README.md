# Última Señal — Alfa 0.1

PWA de supervivencia narrativa **no oficial**. Prototipo original para jugar en solitario. No incluye ilustraciones, texto narrativo ni tablas reproducidas del manual.

## Instalación en GitHub Pages
1. Extrae el ZIP.
2. Sube **los archivos contenidos en la carpeta** a la raíz de tu repositorio (no la carpeta contenedora).
3. En GitHub: Settings → Pages → Deploy from a branch → main / (root) → Save.
4. Visita la URL de Pages por HTTPS. En Android/Chrome abre el menú y selecciona «Instalar aplicación» o «Añadir a pantalla de inicio» cuando esté disponible.
5. Abre la web una vez con conexión para precargar el modo sin conexión.

## Guardados
- `localStorage` con clave `ultima_senal_save_v1`, esquema `1`.
- Exportación JSON e importación validada.
- Antes de importar se crea copia de la partida anterior con prefijo `ultima_senal_preimport_`.
- No borres datos del sitio al actualizar. Exporta JSON antes de reemplazar archivos.
- La disponibilidad del almacenamiento depende del navegador y del dispositivo: exportar regularmente es indispensable.

## Límites deliberados
- Atributos nombrados pero sin valores ni puntos, hasta revisar reglas oficiales.
- La prueba D10 del prólogo (6 o más) es una **mecánica narrativa provisional**, no una afirmación sobre Unisystem.
- No hay combate oficial, heridas, habilidades, poderes, ni campaña extensa todavía.
- El final del prólogo permite volver a jugar; la campaña extensa se añadirá en versiones futuras.

## Archivos
`index.html`, `styles.css`, `app.js`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png`.
