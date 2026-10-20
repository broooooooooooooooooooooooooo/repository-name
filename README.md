# DiscordOS

Aplicación web de chat comunitario con interfaz original y diseño adaptable. Esta primera entrega es una demo frontend: no necesita compilación, claves API ni dependencias externas.

## Probarla
- Abre `index.html` en un navegador moderno.
- También puedes activar GitHub Pages en **Settings → Pages**, seleccionar `main` y la carpeta raíz.
- Crea servidores y canales, escribe mensajes, edita tu perfil, reacciona a mensajes y cambia de tema.
- Los datos se guardan en el almacenamiento local del navegador.

## Incluido
- Diseño adaptable para ordenador y móvil.
- Servidores y canales de texto.
- Envío, edición y eliminación de mensajes propios.
- Reacciones, búsqueda en el canal, perfil editable.
- Tema claro/oscuro y exportación/restablecimiento de datos.

## Importante
Esta es una demo local. No tiene todavía autenticación real, chat entre distintos usuarios/dispositivos, llamadas de voz, permisos de moderación ni subida real de archivos. Los usuarios iniciales son ejemplos.

## Siguiente etapa: Supabase + Auth0
1. Crear tablas para perfiles, servidores, membresías, canales y mensajes.
2. Habilitar Row Level Security (RLS) y probar políticas para limitar cada acción a los miembros autorizados.
3. Activar Supabase Realtime para mensajes y presencia.
4. Configurar Auth0 y su integración de identidad con Supabase.
5. Añadir adjuntos con Supabase Storage y límites de acceso.

No guardes secretos ni claves de servicio en archivos públicos ni en el frontend. Solo deben publicarse claves expresamente diseñadas para cliente, con RLS configurado y probado.

## Estructura
- `index.html`: estructura de la aplicación.
- `styles.css`: estilos y diseño responsive.
- `app.js`: comportamiento y persistencia local.

## Hoja de ruta
- [ ] Autenticación real y perfiles sincronizados.
- [ ] Mensajes en tiempo real entre usuarios.
- [ ] Roles, permisos e invitaciones.
- [ ] Mensajes directos, menciones y moderación.
- [ ] Adjuntos seguros.
- [ ] Voz mediante un proveedor WebRTC.
- [ ] Pruebas automatizadas y límites contra abuso.

La marca y los recursos visuales de esta demo son propios; no se incluyen assets propietarios de otras plataformas.