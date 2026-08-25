# Startup Landing Template

Template visual construido con Next.js 16, React 19, TypeScript y Tailwind CSS 4.

## Requisitos

- Node.js 22 (la versión fijada en `.node-version` es 22.23.2)
- pnpm 11.23.0

## Desarrollo local

```bash
pnpm install
pnpm run dev
```

La aplicación estará disponible en [http://localhost:3000](http://localhost:3000).

## Scripts

```bash
pnpm run dev
pnpm run lint
pnpm run typecheck
pnpm run build
pnpm run start
```

## Rutas incluidas

- `/`: landing page
- `/blog`: listado de artículos MDX
- `/blog/[slug]`: artículo MDX
- `/login`: formulario visual con validación local
- `/signup`: formulario visual con validación local

Los formularios de autenticación no están conectados a un backend.

## Servicios y contenido externo

No se requieren variables de entorno. El contenido del blog reside en `data/blogs` y se compila con Content Collections. Algunas imágenes se cargan desde Aceternity Assets, Unsplash y Pravatar; la tipografía Inter se integra mediante `next/font/google`.
