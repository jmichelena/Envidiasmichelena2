# 💍 Invitación Boda Víctor & Lucía — Guía VS Code

## 📁 Estructura de carpetas

```
boda-victor-lucia/
│
├── index.html          ← La invitación (no tocar si no sabes HTML)
├── LEEME.md            ← Este archivo
│
├── fotos/              ← 📸 PON AQUÍ TUS FOTOS
│   ├── foto1.jpg       ← Foto principal (aparece en hero y galería izquierda)
│   ├── foto2.jpg       ← Galería centro
│   └── foto3.jpg       ← Galería derecha
│
└── musica/             ← 🎵 PON AQUÍ TU CANCIÓN
    └── cancion.mp3     ← Tu archivo de música
```

---

## 📸 Cómo agregar tus fotos

1. Abre la carpeta **`fotos/`**
2. Copia tus 3 fotos ahí
3. **Renómbralas exactamente así:**
   - `foto1.jpg` → la foto principal (la que va de fondo y en la galería grande)
   - `foto2.jpg` → segunda foto de galería
   - `foto3.jpg` → tercera foto de galería
4. ✅ Listo — al abrir `index.html` ya aparecen

> 💡 Si tus fotos son `.png` en vez de `.jpg`, abre `index.html` en VS Code
> y cambia las 4 veces que dice `.jpg` por `.png` (Ctrl+H para reemplazar todo)

---

## 🎵 Cómo agregar tu canción

1. Abre la carpeta **`musica/`**
2. Copia tu archivo `.mp3` ahí
3. **Renómbralo exactamente:** `cancion.mp3`
4. ✅ Listo — la música se activa al primer clic en la página

> 💡 Si tu archivo tiene otro nombre (ej: `perfect.mp3`), puedes:
> - Renombrarlo a `cancion.mp3`, **O**
> - Abrir `index.html` y buscar `cancion.mp3` → cambiarlo por tu nombre real

---

## 🌐 Cómo ver la invitación

### Opción A — Abrir directo (fácil)
1. Haz doble clic en `index.html`
2. Se abre en tu navegador ✅

> ⚠️ La música puede NO funcionar así por restricciones del navegador.
> Para música, usa la Opción B.

### Opción B — Con VS Code Live Server (recomendado)
1. Abre VS Code
2. Instala la extensión **"Live Server"** (botón Extensions → buscar Live Server)
3. Clic derecho en `index.html` → **"Open with Live Server"**
4. Se abre en `http://127.0.0.1:5500` con música funcionando ✅

---

## ✏️ Cambios rápidos en VS Code

| Qué cambiar | Cómo encontrarlo |
|---|---|
| Nombres de los novios | Buscar `Víctor` o `Lucía` (Ctrl+F) |
| Fecha | Buscar `12.04.2026` |
| Teléfono WhatsApp | Buscar `hkm4qh` |
| Lugar | Buscar `La Quebrada` |
| Mensaje del formulario | Buscar `Confirmación — Boda` |

---

## 🚀 Cómo compartirlo (subir a internet)

Para que tus invitados puedan verlo desde su celular, sube la carpeta a:

- **[Netlify Drop](https://app.netlify.com/drop)** ← arrastra la carpeta, gratis y fácil ⭐
- **GitHub Pages** ← si sabes usarlo
- **Hosting propio** ← si tienes uno

---

*Hecho con ♡ para Víctor & Lucía · 12.04.2026*
