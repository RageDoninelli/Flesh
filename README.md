# ÚLTIMA SEÑAL 1.0 — LAS ÚLTIMAS 72 HORAS

PWA de rol individual en español, campaña original de supervivencia zombi.

## Instalación en GitHub Pages
1. **Antes de reemplazar Alfa 0.2**, abre la versión publicada y exporta su JSON desde Respaldo.
2. Extrae el ZIP y sube **los archivos dentro de `ultima_senal_1_0/`** a la raíz del repositorio `Flesh`, reemplazando los anteriores.
3. En GitHub: Settings > Pages > Deploy from branch > main > /(root).
4. Visita https://ragedoninelli.github.io/Flesh/ y verifica que aparezca `1.0 · CAMPAÑA`.
5. Si persiste la interfaz vieja, cierra todas las pestañas, vuelve a cargar y espera que se actualice el service worker. No borres los datos del sitio sin exportar antes.
6. Importa el JSON si necesitas recuperar la ficha o el inventario de la Alfa.

## Incluye
- Campaña original con ocho hitos narrativos y múltiples rutas, desenlace y epílogo.
- Motor de decisiones, pruebas D10, combate por turnos, heridas, energía, XP, inventario, consumibles y fabricación.
- Personaje personalizable y asignación de atributos de **reglas originales simplificadas**.
- Guardado automático, exportación/importación JSON, migración conservadora de Alfa 0.1/0.2 y bitácora TXT.
- PWA instalable, caché offline y sin dependencias de red.

## Limitaciones importantes
- **No es una transcripción ni implementación certificada de Unisystem.** El PDF de referencia está escaneado, sin texto extraíble, y no se ha completado una verificación visual exhaustiva de todas sus reglas. El combate, dificultades, puntos, energía y progresión son reglas originales explícitamente etiquetadas.
- Las escenas son narrativas preescritas y ramificadas: no hay generación libre de escenas ni Director de Juego IA.
- La campaña tiene un final definido; no es un mundo abierto infinito.
- La migración Alfa conserva nombre, concepto, notas seleccionadas, inventario y diario, pero **reinicia el recorrido de campaña**; no puede traducir escenas antiguas 1:1. Los atributos anteriores estaban sin asignación oficial y se inicializan en 1.
- La aplicación se ha sometido a validación de sintaxis y estructura; falta validación manual exhaustiva en diferentes dispositivos Android.

## Seguridad de partidas
Nunca borres los datos de navegación ni desinstales la PWA antes de exportar el respaldo JSON. `localStorage` es local a cada origen y navegador.
