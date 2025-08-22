# Actividad: Pull Requests de 10 alumnos

## Objetivo
Cada alumno debe crear su propia página y añadir su tarjeta al `index.html` mediante un **Pull Request**. Al final, el índice muestra 10 tarjetas con links a las páginas individuales.

## Flujo sugerido
1. **Fork** del repositorio.
2. Crear una rama con tu nombre:  
   ```bash
   git checkout -b feature/apellido-nombre
   ```
3. Copiar la plantilla y personalizarla:
   ```bash
   cp alumnos/_TEMPLATE.html alumnos/<tu-usuario-github>.html
   # Edita el HTML con tus datos
   ```
4. Editar `index.html`: reemplaza uno de los *Slot — Libre* por tu tarjeta siguiendo el comentario guía.  
   - Título en formato **“Apellido, Nombre”**.  
   - Enlace a tu archivo en `alumnos/<tu-usuario-github>.html`.  
   - Mantén **orden alfabético por apellido**.
5. Haz commit(s) con mensajes claros (Convencional Commits recomendado) y `push` de tu rama.
6. Abre un **Pull Request** a `main` usando la plantilla incluida.
7. Resuelve observaciones o conflictos si aparecen.

## Criterios de evaluación (ejemplo)
- [ ] Estructura correcta de archivos y rutas.
- [ ] Respeto del orden alfabético en el índice.
- [ ] Calidad de la edición (ortografía, semántica, formato).
- [ ] PR bien redactado con el template.
- [ ] Sin errores de validación HTML (pruébalo en https://validator.w3.org/).

¡Éxitos y a colaborar!
