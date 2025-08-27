# S&M Minimarket — Deploy en Vercel

Este repositorio contiene el prototipo listo para publicar en Vercel.

## Archivos
- `index.html` — app (catálogo + carrito + checkout por WhatsApp + modo vendedor).
- `logo-sm.png` — coloca tu logo con este nombre junto a `index.html`.
- `vercel.json` — configuración opcional (caché de imágenes y redirección `/index` → `/`).

## Configuración rápida (editar en index.html)
Busca y actualiza:
```js
const STORE_NAME = "S&M Minimarket";
const STORE_WHATSAPP = "51XXXXXXXXX"; // número con código 51
const DELIVERY_FEE = 5.0;
```

## Deploy con GitHub (recomendado)
1. Crea un repo nuevo en GitHub (p.ej., `minimarket-s-m`).
2. Sube los archivos de esta carpeta: `index.html`, `logo-sm.png` y `vercel.json`.
3. En Vercel → **Add New → Project** → Importa tu repo.
   - Framework: **Other**
   - Build Command: *(vacío)*
   - Output Directory: `/`
   - Install Command: *(vacío)*
4. **Deploy**. Abre la URL que te da Vercel.

## Deploy con arrastrar y soltar (sin GitHub)
1. En Vercel → **Add New → Project** → **Deploy Project**.
2. Arrastra la carpeta con estos archivos y suelta para publicar.

## Dominio propio (opcional)
En **Vercel → Project → Settings → Domains → Add**, agrega tu dominio y sigue los pasos de DNS.

¡Listo! :rocket:
