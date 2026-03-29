# Deploy Centros Dentales

## Opción 1 – GitHub + Vercel (automático)

```bash
# 1. Crea el repo en GitHub (en https://github.com/new con nombre: centros-dentales)
# 2. Desde esta carpeta:
cd centros-dentales-web
git remote add origin https://github.com/juanjobarbancho/centros-dentales.git
git push -u origin main
```
Vercel desplegará automáticamente en cuanto detecte el push (tienes la integración activa).

## Opción 2 – Vercel CLI directo (más rápido)

```bash
cd centros-dentales-web
npx vercel --prod
# Sigue las instrucciones (elige tu equipo "juanjo's projects", proyecto "centros-dentales")
```

El sitio estará en: **https://centros-dentales.vercel.app**
