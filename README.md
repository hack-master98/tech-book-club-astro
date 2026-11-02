# Tech Book Club — Astro

Landing page inspirada en la captura compartida.

## Requisitos
- Node.js 18.17+ (recomendado Node 20+)

## Ejecutar
```bash
npm install
npm run dev
```

Abre la URL local que muestra Astro (normalmente http://localhost:4321).

## Estructura
- `src/pages/index.astro`: página principal.
- `src/layouts/BaseLayout.astro`: HTML base, metadatos y estilos globales.
- `src/components/`: secciones independientes de la landing.
- `src/styles/global.css`: estilos, responsive y animaciones de interacción.

Las fotografías se cargan desde Unsplash mediante URL. Puedes sustituirlas por imágenes propias en `public/` y actualizar las rutas en los componentes.
