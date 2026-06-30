Página de cátedra "Introducción a Moodle" — Universidad de Mendoza
===============================================================

Contenido del repo
- index.html
- styles.css
- tareas.html
- recursos.html
- files/ (colocar PDFs y plantillas aquí)
- assets/logo.png (logo institucional — reemplaza con el archivo adjunto)

Pasos rápidos para publicar en GitHub Pages (repo: angelesarias-sketch/angie70)
1. Clona el repo localmente:
   git clone https://github.com/angelesarias-sketch/angie70.git
   cd angie70

2. Copia los archivos listados arriba en la raíz del repo. Crea las carpetas:
   mkdir -p assets files
   - Coloca el logo que te adjunté en assets/logo.png
   - Coloca silabo.pdf, bibliografia.pdf y cualquier plantilla en files/

3. Añade, commitea y sube:
   git add .
   git commit -m "Página de cátedra: Introducción a Moodle - primera versión"
   git push origin main

   Nota: si tu rama por defecto tiene otro nombre (por ejemplo 'master'), usa ese.

4. Habilitar GitHub Pages:
   - Ve a https://github.com/angelesarias-sketch/angie70/settings/pages
   - En "Source", selecciona la rama (ej. main) y la carpeta (root /).
   - Guarda. Después de unos minutos la página estará disponible en:
     https://angelesarias-sketch.github.io/angie70/

5. Verifica:
   - Abre la URL y comprueba que index.html carga correctamente y que el logo aparece.
   - Si necesitas usar una rama diferente (por ejemplo gh-pages) o un flujo con GitHub Actions, avísame y te doy el workflow.

Consejos y ajustes opcionales
- Si quieres que la página principal sea la carpeta /docs en vez de root, sube los archivos a /docs y selecciona esa carpeta en Settings > Pages.
- Para publicar automáticamente desde main a gh-pages con un workflow, puedo generar un GitHub Action si lo solicitas.
- Si quieres que yo suba los archivos directamente al repo (incluyendo el logo adjunto), dame permiso para escribir y dime la rama objetivo (ej. main). Yo puedo hacer el commit por ti.
