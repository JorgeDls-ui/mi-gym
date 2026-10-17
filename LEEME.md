# Mi Gym v1.5 — cómo instalarla

## Probar en la PC
Abre `index.html` con doble clic (Chrome o Edge). Se ve la app, pero así no guarda datos de forma fiable ni se instala. Para usarla de verdad hay que publicarla (paso siguiente).

## Publicar gratis en GitHub Pages (una sola vez)
1. Crea una cuenta en github.com (o entra a la tuya).
2. Arriba a la derecha **+** → **New repository** → nombre `mi-gym` → **Public** → **Create repository**.
3. En la página del repositorio vacío toca **uploading an existing file**.
4. Abre esta carpeta en el Explorador, selecciona TODO (`index.html`, `manifest.json`, `sw.js`, `LEEME.md` y la carpeta `icons`) y arrástralo a la página. Verifica que aparezcan archivos como `icons/splash/...` → **Commit changes**.
5. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → **Save**.
6. En 1–2 minutos tu app queda en `https://TU-USUARIO.github.io/mi-gym/` (recarga la página de Settings → Pages para ver el enlace).

## Instalar en el iPhone
1. Abre esa dirección en **Safari** (no en Chrome ni dentro de otra app).
2. Botón **Compartir** (cuadro con flecha) → **Agregar a inicio** → **Agregar**.
3. Abre la app **desde el ícono nuevo**, no desde Safari. Safari y la app instalada guardan datos por separado.
4. La primera vez ábrela con internet. Después funciona sin conexión.
5. En la app: **Ajustes** → revisa unidad (kg/lb) y si quieres activar RIR.

## Temporizador de descanso (apagado por defecto)
Si prefieres que la app cuente el descanso, actívalo en **Ajustes → Temporizador de descanso**. Entonces:
- Deja la pantalla encendida: si bloqueas el iPhone o cambias de app, el aviso de descanso no suena hasta que vuelvas.
- El iPhone no vibra desde una app web; al terminar el descanso suena un pitido y la pantalla destella.

## Respaldos (importante)
Los datos viven solo en el teléfono. Si borras el ícono o el iPhone libera espacio, se pierden.
La app te avisa cuando toca respaldar: **Exportar** → guárdalo en **Archivos → iCloud Drive**.

## Pasar datos entre teléfono y PC
Ajustes → **Exportar respaldo** (en el iPhone guárdalo en Archivos/iCloud o mándalo por AirDrop) → en el otro dispositivo Ajustes → **Importar y combinar**.

## Actualizar a una versión nueva
Sube los archivos nuevos al mismo repositorio (**Add file → Upload files**, reemplazando). Abre la app con internet; se actualiza sola en la siguiente apertura. Tus datos no se borran.
