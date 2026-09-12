# 🎨 Rincón Infantil de Actividades (PWA)

App web infantil con matemáticas, sopa de letras, crucigramas, pizarra de dibujo
y generador de cuentos. Funciona **sin internet** una vez instalada (PWA).

## 📁 Contenido

| Archivo | Descripción |
|---|---|
| `index.html` | La aplicación completa |
| `manifest.json` | Configuración de la PWA (nombre, iconos, colores) |
| `sw.js` | Service worker (caché offline) |
| `icons/` | Iconos de la app (192px, 512px, maskable) |

## 🚀 Cómo publicarla en GitHub Pages

1. Crea una cuenta en [github.com](https://github.com) (es gratis).
2. Clic en **"New repository"** (botón verde) y nómbrala `rincon-infantil`.
   - Marca **Public**.
   - NO marques "Add a README".
3. Entra al repositorio → botón **"Add file"** → **"Upload files"**.
4. Arrastra el **contenido** de esta carpeta (index.html, manifest.json, sw.js
   y la carpeta icons) a la zona de carga. Oprime **"Commit changes"**.
5. Ve a **Settings** → **Pages** (menú izquierdo).
6. En **Source** elige: rama `main` y carpeta `/ (root)` → **Save**.
7. Espera 2-5 minutos. Tu app estará en:
   `https://TU-USUARIO.github.io/rincon-infantil/`

## 📲 Instalar la app

Abre la URL en Chrome/Edge (en PC o celular) → menú (⋮) →
**"Instalar app"** o **"Agregar a pantalla de inicio"**.

## 📸 Screenshots

La carpeta `screenshots/` contiene imágenes promocionales que ya están
registradas en `manifest.json` (mejora la instalación y el puntaje en PWABuilder).
