# Voz Escolar | Colegio Valle Central

Prototipo de una plataforma institucional para reportar y dar seguimiento a problemas de infraestructura, convivencia, limpieza y seguridad.

## Incluye

- Portada institucional con propuesta de valor para dirección y coordinación.
- Centro de reportes con categorías, ubicación, descripción y opción anónima.
- Panel de seguimiento con estados, estadísticas y filtros.
- Recursos de convivencia y ruta de apoyo.
- Página institucional con beneficios para dirección, coordinación y comunidad.
- Flujo de registro docente, inicio de sesión y perfil docente de demostración.
- Diseño adaptable para teléfono, tablet y escritorio.

## Ejecutar localmente

Abre `index.html` en el navegador o sirve la carpeta con:

```powershell
python -m http.server 8000
```

Visita `http://localhost:8000`.

## Páginas

```text
.
├── index.html       # Presentación principal
├── reportes.html    # Registro y seguimiento de incidencias
├── recursos.html    # Convivencia y bienestar
├── contacto.html    # Propuesta institucional
├── login.html       # Acceso docente de demostración
├── perfil.html      # Perfil docente
├── docente.html     # Ficha docente
└── README.md
```

`Restaurante.html` conserva la URL anterior y redirige a `index.html`.

Los reportes de demostración se guardan en `localStorage` cuando el navegador lo permite y funcionan en memoria al abrir los archivos directamente.

## Importante sobre el prototipo

El formulario de acceso y los reportes son prototipos front-end. Antes de usarlo con estudiantes o docentes, debe conectarse a autenticación real, una base de datos segura, HTTPS, control de permisos, notificaciones y un panel administrativo con responsables. El botón del MEP dirige al sitio oficial para trámites y consultas institucionales.

## Publicar en GitHub Pages

1. Sube los archivos a la rama `main` del repositorio.
2. Ve a **Settings > Pages**.
3. Selecciona `Deploy from a branch`, rama `main` y carpeta `/root`.
4. Guarda y abre la URL generada por GitHub Pages.
