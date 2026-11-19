# El Arte de Trabajar con Claude

Guía práctica en formato libro para usar Claude de forma profesional: fundamentos, técnicas, ejemplos y ejercicios con soluciones.

> Guía **independiente y no oficial**. No está afiliada ni respaldada por Anthropic.

**Leer en línea:** https://hectorescamillamath.github.io/guia-claude/

## Contenido

### Parte I · Fundamentos

1. Conocer a tu colaborador
2. Anatomía de un buen prompt (método C.O.R.E.F.)
3. Técnicas avanzadas
4. El arte de iterar
5. Las herramientas de la app
6. Claude en el trabajo profesional
7. Claude en la educación
8. Ética, honestidad y verificación
9. Biblioteca de plantillas

### Parte II · Nivel 2: Claude como asistente de trabajo

10. Preparar tu equipo (instalación)
11. Organizar documentos
12. Conectar tus aplicaciones (conectores y extensiones)
13. Sincronizar sin perder nada
14. Navegador y control del equipo
15. Automatizar más allá del texto
16. Tareas programadas
17. Seguridad en el nivel 2
18. Conectar Claude con tu GitHub

Apéndices: lista de verificación, glosario, recursos oficiales y reto final.

## Archivos del repositorio

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La guía completa (todo en un solo archivo). |
| `404.html` | Página que aparece si alguien abre un enlace que no existe. |
| `favicon.svg` | Ícono que se ve en la pestaña del navegador. |
| `robots.txt` | Permite que los buscadores encuentren la guía. |
| `.nojekyll` | Le dice a GitHub Pages que publique los archivos tal cual. |
| `.gitignore` | Evita subir archivos basura del sistema. |
| `LICENSE.md` | Licencia CC BY 4.0 y aviso de no afiliación. |
| `README.md` | Este archivo. |

## Publicar en GitHub Pages

### Opción A — Desde el navegador (sin instalar nada)

1. Entra a [github.com](https://github.com), inicia sesión y pulsa **New repository**.
2. Ponle un nombre, por ejemplo `guia-claude`. Elige **Public**. No marques "Add a README". Pulsa **Create repository**.
3. En la página del repositorio vacío, haz clic en **uploading an existing file**.
4. Arrastra **todos** los archivos de esta carpeta.
   - Los archivos `.nojekyll` y `.gitignore` están ocultos. En Windows: Explorador → *Vista* → marca *Elementos ocultos*. En Mac: en Finder pulsa `Cmd + Shift + .`
5. Escribe un mensaje como "Primera versión de la guía" y pulsa **Commit changes**.
6. Ve a **Settings → Pages**.
7. En **Build and deployment → Source**, elige **Deploy from a branch**. En **Branch**, elige `main` y la carpeta `/ (root)`. Pulsa **Save**.
8. Espera 1 o 2 minutos y recarga la página. Arriba aparecerá: *Your site is live at…* Ese es tu enlace.

### Opción B — Con GitHub Desktop (recomendada para actualizar con frecuencia)

1. Instala [GitHub Desktop](https://desktop.github.com) e inicia sesión.
2. **File → Add local repository** y elige esta carpeta. Si te dice que no es un repositorio, pulsa **create a repository**.
3. Pulsa **Publish repository**, desmarca *Keep this code private* y confirma.
4. Activa GitHub Pages como en los pasos 6 a 8 de la opción A.
5. Para actualizar: reemplaza los archivos en la carpeta, escribe un mensaje en GitHub Desktop, pulsa **Commit to main** y luego **Push origin**.

### Actualizar la guía después

Cada vez que cambies `index.html` y lo subas (opción A: *Add file → Upload files*; opción B: *Commit* + *Push*), GitHub Pages publicará la nueva versión en uno o dos minutos. Si no ves los cambios, recarga con `Ctrl + F5` (Windows) o `Cmd + Shift + R` (Mac).

### Dominio propio (opcional)

En **Settings → Pages → Custom domain** puedes poner un dominio tuyo (por ejemplo `guia.tudominio.com`) y configurar un registro CNAME en tu proveedor de dominio que apunte a `TU-USUARIO.github.io`.

## Funciones de la página

- Índice general con tarjetas y un índice lateral con buscador.
- Botones de capítulo anterior y siguiente, barra de progreso de lectura y botón para volver arriba.
- Modo claro u oscuro, diseño adaptado a celular.
- Botón "Copiar" en cada prompt de ejemplo.
- Ejercicios con soluciones desplegables.
- Imprimible o exportable a PDF desde el navegador (`Ctrl/Cmd + P`).

## Licencia

Contenido bajo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Ver `LICENSE.md`.

"Claude" y "Anthropic" son marcas de sus respectivos titulares; se mencionan solo con fines descriptivos. La información sobre funciones del producto puede cambiar: consulta siempre la documentación oficial.
