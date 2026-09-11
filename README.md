# Escudero Cars

Sitio web de concesionaria con catálogo público, vehículos destacados, carrusel 3D y panel privado conectado a Supabase Realtime.

## WhatsApp
+54 9 3541 27-6537

## Panel
Ruta: `/admin.html`
Usuario autorizado: `admin@escuderocars.com`

La contraseña debe crearse en Supabase Authentication y no se almacena en el código.

## Supabase
Proyecto ya configurado en `config.js`. La tabla `public.vehicles` usa RLS: cualquiera puede consultar vehículos, pero solo el usuario autorizado puede crear, editar o eliminar. Los cambios se publican mediante Supabase Realtime.

## Imágenes
Las tres fotos del vehículo están en `assets/auto-1.jpg`, `auto-2.jpg` y `auto-3.jpg`. El logo proporcionado está en `assets/escudero-cars-logo.jpg`.
