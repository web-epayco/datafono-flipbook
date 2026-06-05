# Guía de uso del datáfono — ePayco

Flipbook interactivo de la guía del datáfono ePayco.

## Ver online

Publicado en **GitHub Pages**: `https://<tu-usuario>.github.io/datafono-flipbook/`

## Estructura

```
datafono-flipbook/
├── index.html      ← Flipbook (todo en un archivo)
├── pages/
│   ├── page-01.png
│   ├── ...
│   └── page-18.png
└── README.md
```

## Publicar en GitHub Pages

1. Crea un repo en GitHub (puede ser privado o público).
2. Sube todos los archivos:
   ```bash
   git init
   git add .
   git commit -m "feat: flipbook guía datáfono"
   git remote add origin https://github.com/<usuario>/datafono-flipbook.git
   git push -u origin main
   ```
3. En el repo → **Settings → Pages → Source: Deploy from a branch → main / (root)**.
4. En ~1 minuto el flipbook estará en `https://<usuario>.github.io/datafono-flipbook/`.

## Usar en WordPress

Sube la carpeta completa por FTP/SFTP a tu hosting y enlaza con un botón o embed:

```html
<iframe src="https://tu-dominio.com/ruta/datafono-flipbook/" 
        width="100%" height="700" frameborder="0" allowfullscreen></iframe>
```

## Controles

| Acción | Descripción |
|--------|-------------|
| Clic en borde de página / arrastrar | Voltear página |
| ← → ↑ ↓ | Navegar con teclado |
| `Home` / `End` | Primera / última página |
| `+` / `-` | Zoom |
| Miniaturas inferiores | Ir a página directamente |
