# Iruña Partner Challenge

Web app con los horarios, WODs y equipos del **Iruña Partner Challenge** (CrossFit Iruña).

- 📅 **Horarios**: timeline completo por WOD, heat y categoría
- 🏋️ **WODs**: los 4 workouts (Minnie, Pluto, Goofy, Mickey) con versión RX / SC
- 👥 **Equipos**: selecciona tu equipo y consulta tu ficha con tus horarios
- 📱 **PWA**: instalable en el móvil y funciona offline una vez cargada

## Tecnología

HTML + CSS + JavaScript vanilla en un solo fichero. Sin dependencias ni build. Service worker con caché offline y manifest para instalación.

## Publicar en GitHub Pages

1. Sube este contenido a un repositorio
2. En el repositorio: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**
3. En 1-2 minutos estará disponible en `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

> El service worker y el manifest usan rutas relativas, así que funciona tanto en la raíz de un dominio como en una subruta de GitHub Pages.

## Instalar como app

- **Android (Chrome)**: al abrir la web aparece el banner "Añadir a pantalla de inicio", o menú ⋮ → *Instalar aplicación*
- **iPhone (Safari)**: botón compartir → *Añadir a pantalla de inicio*

---

Herramienta diseñada por [DigitalWorkApps](https://digitalworkapps.netlify.app)
