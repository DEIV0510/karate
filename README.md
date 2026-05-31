# 🥋🌿 ¡Ganbatte! — Liga Antioqueña de KarateDo

Página web de **apoyo** (mobile-first) para desearle suerte a 4 competidores de karate de la **Liga Antioqueña de KarateDo**: **Sara, Coscu, Paniagua y Daniel**.

> _« Por un ser humano mejor »_ · Orgullo paisa, Antioquia 🇨🇴

Fusiona la identidad de la Liga (**verde + negro**, como el logo) con un estilo **kawaii** (mascotas tiernas, pétalos, todo redondito) y las **fotos reales** del equipo.

## ✨ Qué incluye

- **Hero** con el logo, el lema y un sello de orgullo paisa.
- **Tarjeta de cada competidor** con su foto, su mascota kawaii, cinturón y botón de "¡Ánimo!" (los vítores se guardan en el navegador).
- **Galería del equipo** dentro y fuera del tatami.
- **Medidor de energía** interactivo (toca el corazón 💚).
- Valores del karate en kanji (礼 勇 忍 心).
- Animaciones suaves que respetan `prefers-reduced-motion`.

## 🚀 Cómo verla

**Opción rápida:** abre `index.html` en cualquier navegador (ideal en el celular).

**Con servidor local** (Node.js):

```bash
node server.js
# luego abre http://localhost:5193/
```

## 🌐 Publicar en GitHub Pages

1. En GitHub: **Settings → Pages**.
2. En *Source* elige la rama `main` y la carpeta `/ (root)`.
3. Guarda. En un minuto estará en `https://deiv0510.github.io/karate/`.

## 🛠️ Tecnología

HTML + CSS + JavaScript puro, en un solo archivo (`index.html`). Sin frameworks ni build. Fuentes: Baloo 2, Mochiy Pop One y Nunito (Google Fonts).

```
Karate-Kawaii/
├── index.html      # la página completa
├── img/            # logo y fotos del equipo
├── server.js       # mini servidor estático para verla en local
└── README.md
```

---

Hecho con mucho cariño para el equipo. ¡Pase lo que pase, ya son campeones! 🥇💚
