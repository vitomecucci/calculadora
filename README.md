# 🧮 Calculadora PWA

Una calculadora moderna, oscura y rápida. Funciona **offline** y se puede instalar en el celular como app nativa.

## 📱 Instalar en el celular

Una vez publicada en GitHub Pages, abrí la URL en tu celular y:

- **Android (Chrome):** aparece un banner "Agregar a pantalla de inicio" o tocá el menú ⋮ → *Instalar app*
- **iPhone (Safari):** tocá el botón compartir → *Agregar a pantalla de inicio*

---

## 🚀 Publicar en GitHub Pages (paso a paso)

### 1. Crear el repositorio

1. Entrá a [github.com](https://github.com) e iniciá sesión
2. Hacé clic en **New repository** (botón verde)
3. Poné un nombre, ej: `calculadora`
4. Dejalo **Public**
5. Hacé clic en **Create repository**

### 2. Subir los archivos

Una vez creado el repo, GitHub te muestra opciones. Usá la opción **"uploading an existing file"**:

1. Arrastrá estos archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
2. Hacé clic en **Commit changes**

### 3. Activar GitHub Pages

1. Ir a **Settings** del repo (arriba a la derecha)
2. En el menú lateral, hacer clic en **Pages**
3. En *Branch*, seleccionar `main` y carpeta `/ (root)`
4. Hacer clic en **Save**

En ~1 minuto tu app estará disponible en:
```
https://TU_USUARIO.github.io/calculadora/
```

---

## ✨ Funcionalidades

- Operaciones básicas: suma, resta, multiplicación, división
- Porcentaje
- Preview del resultado en tiempo real
- Funciona sin internet (Service Worker)
- Instalable como PWA en Android e iOS
- Teclado físico compatible

---

Hecho con HTML, CSS y JS puro. Sin dependencias. 🖤
