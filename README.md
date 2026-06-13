# Portafolio profesional

Portafolio de Allan Rodríguez para el curso de Universidad Cenfotec Q2 2026.

## Stack

- Astro 6
- React 19
- Tailwind CSS 4
- TypeScript
- Vercel

## Desarrollo local

```bash
npm install
npm run dev
```

El sitio estará disponible en `http://localhost:4321`.

## Comandos

| Comando | Acción |
| --- | --- |
| `npm run dev` | Inicia el servidor local |
| `npm run check` | Valida Astro y TypeScript |
| `npm run build` | Genera la versión de producción |
| `npm run preview` | Sirve localmente la versión generada |

## Publicación

Vercel detecta Astro automáticamente. Al importar el repositorio
`allroven/portafolio`, no es necesario cambiar el comando de build ni el
directorio de salida.

Después del primer despliegue, agrega `allroven.me` y `www.allroven.me` desde
**Project Settings → Domains**. Vercel mostrará los registros DNS exactos que
deben configurarse con el proveedor del dominio.
