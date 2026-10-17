# Agenda personal 2027

PWA inicial con estética Dark Academia y módulos para día, notas, proyectos, lecturas, idiomas, gastos y copias de seguridad.

## Publicación
En GitHub abre **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, branch **main**, folder **/(root)** y guarda. La web aparecerá en `https://favimn.github.io/Agenda-2027/` cuando termine la publicación.

## Estado actual y privacidad
- Los registros se guardan en el almacenamiento local del navegador de ese dispositivo.
- Exporta periódicamente una copia JSON desde Datos.
- No hay todavía sincronización entre dispositivos ni inicio de sesión.
- No introduzcas información extremadamente sensible.
- El repositorio contiene código, no tus registros personales.

## Siguiente fase
Configurar Supabase con autenticación y políticas RLS antes de conectar sincronización en la nube. No incluir claves secretas en el repositorio.