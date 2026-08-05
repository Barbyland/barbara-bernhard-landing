# Landing profesional de Bárbara Bernhard

Landing estática, responsive y accesible para presentar el perfil profesional de Bárbara Bernhard en QA, Automation Testing y TravelTech.

## Archivos principales

- `index.html`: contenido y estructura semántica.
- `styles.css`: diseño, responsive y estados de foco.
- `script.js`: menú móvil accesible y año dinámico.
- `assets/barbara-bernhard.webp`: fotografía profesional optimizada para web.
- `assets/Barbara_Bernhard_CV_QA_2026_publico_sin_telefono.pdf`: CV público descargable.
- `assets/favicon.png`: favicon con las iniciales BB.

## Ejecutar localmente

La página puede abrirse directamente haciendo doble clic en `index.html`. Para probarla con un servidor local:

```powershell
python -m http.server 8000
```

Luego abrir `http://localhost:8000`.

## Reemplazar la fotografía

Reemplazar `assets/barbara-bernhard.webp` por otra imagen con el mismo nombre. Se recomienda una fotografía cuadrada, de al menos 900 × 900 px y optimizada para web.

## Actualizar el CV

Reemplazar `assets/Barbara_Bernhard_CV_QA_2026_publico_sin_telefono.pdf` conservando exactamente el mismo nombre. La versión pública no debe incluir teléfono ni datos sensibles.

## Cambiar enlaces o textos

Editar `index.html` y buscar la URL o el texto que se desea actualizar. Los enlaces externos incluyen apertura en una nueva pestaña y protección `noopener noreferrer`.

## Publicar en Netlify

1. Iniciar sesión en Netlify.
2. Elegir **Add new site** y luego **Deploy manually**.
3. Arrastrar la carpeta completa `landing profesional personal 2026` al área de publicación.
4. Cuando Netlify entregue la URL pública, abrirla y probar todos los enlaces antes de generar el QR.

No se necesita comando de compilación. El directorio de publicación es la raíz de esta carpeta.

## Publicar en GitHub Pages

1. Crear un repositorio y subir el contenido de esta carpeta a la rama `main`.
2. En el repositorio, abrir **Settings → Pages**.
3. En **Build and deployment**, seleccionar **Deploy from a branch**.
4. Elegir la rama `main` y la carpeta `/ (root)`.
5. Guardar y esperar la URL pública.

## Verificación previa al QR

- Confirmar la descarga del CV público.
- Abrir LinkedIn, GitHub, FARO, Barby Digital y los repositorios.
- Revisar la página en 375 px, 768 px y escritorio.
- Probar navegación completa con teclado y zoom al 200%.
- Ejecutar Lighthouse desde Chrome en las categorías Performance, Accessibility, Best Practices y SEO.
- Generar el QR únicamente con la URL pública definitiva y probarlo desde otro teléfono con datos móviles.
