# Mesa de práctica — Texas Hold’em

Entrenador local de póker con fichas ficticias. La partida y el rival local se ejecutan en el dispositivo; no hay cuentas, dinero real ni llamadas a servidores.

## Publicar en GitHub Pages
1. Sube **todos los archivos de esta carpeta al nivel raíz del repositorio** (sin crear una carpeta contenedora): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` y `README.md`.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona `main` y la carpeta `/(root)`. Pulsa **Save**.
5. La dirección del sitio será `https://luisosa11.github.io/mesa-de-practica/` cuando GitHub termine de publicarlo.

## Instalar en iPhone
1. Abre la dirección publicada con Safari y espera a que cargue una vez con conexión.
2. Pulsa **Compartir → Añadir a pantalla de inicio**.
3. Deja activada la opción **Abrir como app web** y pulsa **Añadir**.
4. Abre la app una vez más con conexión para que el Service Worker almacene los archivos. Después prueba el modo avión.

## Limitaciones
- Primera versión de entrenamiento heads-up (tú contra un rival local sencillo).
- El rival automático usa reglas heurísticas, no estrategia profesional.
- El entrenador integrado funciona offline y ofrece explicaciones básicas. Para análisis personalizado de ChatGPT, copia el resumen de una mano y tráelo al chat cuando tengas internet.
- Todas las fichas son ficticias.
