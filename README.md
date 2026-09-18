# CV Studio — GitHub Pages

Aplicación estática para crear un currículum y anexos documentales desde el navegador.

## Publicación
1. Crear un repositorio público o privado compatible con GitHub Pages.
2. Subir `index.html`, `styles.css` y `app.js` a la raíz.
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. Abrir la dirección que GitHub Pages indique.

## Uso
Completar datos, agregar experiencia/formación/cursos, subir fotografías de documentos, asignar títulos, usar «Recortar» y revisar cada recorte. Descargar PDF. «Guardar proyecto» crea un JSON local para continuar luego; «Abrir proyecto» lo recupera.

## Privacidad y límites
No hay servidor, cuentas ni transmisión de datos por parte de la app. Los datos viven en la pestaña mientras está abierta; exportar el JSON permite conservarlos. La librería jsPDF se carga desde CDN y requiere conexión para generar el PDF. El recorte automático utiliza contraste y puede fallar con fondos complejos: verificar y corregir manualmente. Se aceptan imágenes JPG/PNG y formatos de imagen que el navegador pueda abrir, no PDF como anexo de entrada. Evitar publicar proyectos JSON, cédulas o documentos personales en GitHub. El PDF incluye documentos sensibles solo cuando el usuario los añade; compartir una versión sin anexos cuando no sean necesarios.
