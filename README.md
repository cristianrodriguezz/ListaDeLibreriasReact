# ListaDeLibreriasReact
Este repositorio es de un readme.md con todas las librerías necesarias y buenas para crear un proyecto de React Js.

# React Libraries 2023

## Crear proyecto

Client Side: Vite
SSR: Next.js
Static: Astro

## Package Manager

Por defecto: npm
Por cambiar o por probar: pnpm

## State Management

- Cosas estáticas o que cambian poco: React Context
- Para estado global general: Zustand
- Redux Toolkit SÓLO para proyectos medio/grandecitos con estados globales complejos
- Para proyectos GRANDES, evitar el estado global y depender de React Query, Apollo, Flux...

## Data Fetching

Tanstack Query/SWR
urlQL

## Routing

- NextJS File System Routing
- React Router (para proyectos con paths complejos o muchas páginass)
- Wouter (smaller alternative, páginas sencillas)

## CSS Styling

- TailwindCSS
- CSS Modules
- Vanilla Extract

## React UI Libraries

- Framer Motion
- Auto Animate

## Charts

- Recharts

## Forms

- https://react-hook-form.com/
- zod (para validaciones)

# Autenticación

- Supabase Auth
- Next Auth
- O probar Lucia Auth/Authjs.dev

# Hosting

Proyectos web:
1. Vercel
2. Netlify

Proyectos web + Workers (Edge Functions):
Especial mención: Cloudflare

Dockerfiles:
1. Railway
2. Fly.io
3. Render

# Testing

Vitest + Playwright + React Testing Library

# Time in React

Menos momento lo que quieras.

1. date-fns
2. dayjs
3. luxon

7 LIBRERÍAS que todo programador de REACT debería conocer:

#1. REACT PDF te permite renderizar PDFs en tu sitio web muy fácilmente:
https://react-pdf.org/

#2. UseAnimations es una colección de iconos con animaciones para mostrar micro interacciones en tu página web.
https://lnkd.in/ejx4K6Xn

#3. React Hot Toast te permite mostrar notificaciones en tu página web de forma bonita y sencilla.
https://lnkd.in/e8UcMuRg

#4. React Day Picker
Renderiza un calendario completo con el que puedes navegar meses y días.
Totalmente personalizable para que encaje con tu estilo de página.
https://lnkd.in/eAin9AYX

#5. FilePond
Un componente para arrastrar y soltar imágenes. Sube de nivel la forma en la que tus usuarios suben imágenes a tu sitio.
También disponible para Vue, Angular y otros frameworks.
https://pqina.nl/filepond/

#6. Luxon
De los creadores de Moment, llega una liviana biblioteca para trabajar con fechas y tiempo en JavaScript.
¡Deja de usar Date y olvida los quebraderos de cabeza!

#7. React Window
Renderiza solo los elementos que se vean de una lista, así mejoras el rendimiento de tu página.
A esta técnica se le llama también "listas virtuales" y así sólo renderizas lo que necesita el usuario.
