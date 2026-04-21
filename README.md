# Canallacom

Sitio web estático servido desde GitHub Pages.

## Estructura

```
canallacom/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/          ← imágenes y recursos estáticos
```

## Desarrollo local

1. Instalar la extensión **Live Server** en VS Code (ya incluida en este workspace).
2. Abrir `index.html` y hacer clic en **Go Live** en la barra de estado.

O bien, desde la terminal:

```bash
npx live-server .
```

## Publicar en GitHub Pages

1. Crear un repositorio en GitHub (público o privado con Pages habilitado).
2. Subir los archivos:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/canallacom.git
git push -u origin main
```

3. En GitHub: **Settings → Pages → Source → Branch: main / (root)** → Save.
4. El sitio estará disponible en `https://TU_USUARIO.github.io/canallacom/` en unos minutos.
