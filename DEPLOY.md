# Instrucciones para Publicar en GitHub Pages

Este sitio está listo para ser publicado en GitHub Pages. Sigue estos pasos:

## Opción 1: Configurar GitHub Pages desde la Interfaz Web (Recomendado)

1. Ve a tu repositorio en GitHub:
   https://github.com/fedesantamarina/Direccion-de-Proyectos-de-Tecnologia-Informatica

2. Haz clic en **Settings** (Configuración)

3. En el menú lateral izquierdo, busca **Pages**

4. En la sección **Build and deployment**:
   - **Source**: Selecciona "Deploy from a branch"
   - **Branch**: Selecciona `claude/create-course-content-site-011CUoRJgQEesf3qEicJbCKo`
   - **Folder**: Selecciona `/ (root)`

5. Haz clic en **Save**

6. Espera unos minutos. GitHub Pages construirá tu sitio.

7. Tu sitio estará disponible en:
   https://fedesantamarina.github.io/Direccion-de-Proyectos-de-Tecnologia-Informatica/

## Opción 2: Merge a Main y Publicar desde Main

Si prefieres publicar desde la rama `main`:

1. Ve a GitHub y crea un Pull Request desde:
   `claude/create-course-content-site-011CUoRJgQEesf3qEicJbCKo` → `main`

2. Revisa los cambios y haz merge

3. Configura GitHub Pages para publicar desde `main`:
   - Settings → Pages
   - Branch: `main`
   - Folder: `/ (root)`
   - Save

## Verificación

Una vez configurado, puedes verificar el estado de tu deployment en:
- Settings → Pages
- O en la pestaña **Actions** del repositorio

## Acceso al Sitio

Una vez publicado, el sitio estará disponible en:
**https://fedesantamarina.github.io/Direccion-de-Proyectos-de-Tecnologia-Informatica/**

### URLs directas a las clases:
- Página principal: `/index.html`
- Clase 1: `/clase-01.html`
- Clase 2: `/clase-02.html`
- ... y así sucesivamente

## Notas Importantes

- El sitio es completamente estático (HTML/CSS/JavaScript)
- No requiere servidor backend
- Los diagramas Mermaid se cargan desde CDN
- Es totalmente responsivo y funciona en móviles

## Actualizar el Sitio

Para actualizar el contenido:
1. Haz cambios en los archivos HTML/CSS
2. Commit y push a la rama configurada
3. GitHub Pages se actualizará automáticamente

---

**¿Preguntas?** Consulta la documentación oficial: https://docs.github.com/pages
