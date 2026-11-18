# Páginas públicas · GGG Nova Supps

Páginas que se abren desde los enlaces de WhatsApp de la app Nova Negocio:

- `pedido/` · página para que los distribuidores armen su pedido (`?l=<enlace>`, demostración `?demo=1`).
- `rastreo/` · rastreo del pedido (`?t=<token>`) y `rastreo/reparto.html` para el repartidor.
- `Nova-Supps/…` · redirecciones desde las direcciones anteriores, para que los enlaces ya enviados sigan funcionando.

Solo contienen la clave *publishable* de Supabase, pública por diseño: los permisos los deciden las reglas de la base (RLS).
El código de la app vive en el repositorio privado `Nova-Supps`; los cambios a estas páginas se hacen ahí y se copian aquí.
