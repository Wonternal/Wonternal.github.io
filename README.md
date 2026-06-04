# Wonternal · Game Hub (Portfolio)

Sitio web de portfolio para presentar los juegos del hub y enlazar a las versiones jugables.

**URL en producción:** [https://wonternal.github.io/](https://wonternal.github.io/)

---

## Publicar en GitHub Pages (gratis)

GitHub Pages hospeda sitios estáticos sin coste. Para que la URL sea `https://wonternal.github.io/` el repositorio **debe llamarse exactamente** `Wonternal.github.io`.

### Subida manual (recomendada si tienes otra cuenta Git en el PC)

1. Inicia sesión en GitHub como **Wonternal**.
2. **New repository** → nombre: `Wonternal.github.io` → Public → Create.
3. **Upload files** → arrastra todo el contenido de la carpeta `portfolio/`:
   - `index.html`
   - `css/`
   - `js/`
   - `README.md`
4. Commit: `Add portfolio site`.
5. Ve a **Settings → Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` → carpeta `/ (root)` → Save
6. En 1–3 minutos estará en **https://wonternal.github.io/**

### Repos de juegos (enlaces del portfolio)

| Juego | Repo | Juego en navegador |
|-------|------|-------------------|
| Chicken Road | [chicken-road](https://github.com/Wonternal/chicken-road) | [wonternal.github.io/chicken-road](https://wonternal.github.io/chicken-road/) |
| Space War | [space-war](https://github.com/Wonternal/space-war) | Solo escritorio (Python) |

**Chicken Road en Pages:** en el repo `chicken-road`, activa Pages igual (rama `main`, root). La URL será `https://wonternal.github.io/chicken-road/`.

**Space War:** no es web; el portfolio enlaza al README de GitHub con instrucciones de instalación.

---

## Personalizar

Edita `index.html` sección **Sobre mí** y el email en los enlaces. La foto de perfil es `portfolioImage.jpg` en la raíz del repo (súbela junto al resto de archivos).

---

## Estructura

```
portfolio/
├── index.html
├── css/style.css
├── js/main.js
└── README.md
```

---

## Licencia

MIT — mismo criterio que los juegos del hub.
