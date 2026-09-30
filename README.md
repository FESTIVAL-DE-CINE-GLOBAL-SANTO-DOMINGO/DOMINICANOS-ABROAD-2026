# Encuentro con la diáspora cinematográfica dominicana

Symphony Space, Nueva York · 24 de septiembre de 2026.

**Preparado por ODLC.**

## Nombre y descripción para GitHub

Nombre del repositorio: `ENCUENTRO-DIASPORA-NUEVA-YORK-24-09-2026`

Descripción:

> Relatoría, propuestas y presentaciones del encuentro con la diáspora cinematográfica dominicana en Symphony Space, Nueva York, el 24 de septiembre de 2026.

## Publicar

1. Crea un repositorio nuevo con ese nombre, separado de los reportes anteriores.
2. Descomprime el ZIP y abre la carpeta del sitio.
3. En GitHub, pulsa **uploading an existing file** o **Add file → Upload files**.
4. Sube el contenido de la carpeta: `index.html`, `assets`, `documentos`, `README.md` y `.nojekyll`. El index debe quedar en la raíz del repositorio.
5. Guarda con **Commit changes** en `main`.
6. Si GitHub no permite subir `.nojekyll`, créalo mediante **Add file → Create new file**. Escribe `.nojekyll` como nombre y `# Sitio estático` como contenido.
7. En **Settings → Pages**, elige **Deploy from a branch**, **main**, **/(root)** y pulsa **Save**.
8. Abre el enlace que GitHub muestre cuando termine el despliegue.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Archivos

```text
index.html
assets/
  registro.png
  ley-cine.png
documentos/
  relatoria-encuentro-diaspora.docx
  registro-encuentro-diaspora.pdf
  impacto-ley-108-10.pdf
README.md
.nojekyll
```

Los estilos y las funciones están incluidos en el HTML. Los documentos y las portadas se cargan desde sus carpetas, por lo que hay que subirlas también. No hay instalación ni compilación. Se puede abrir el index directamente en el navegador.

## Contenido

La página contiene la relatoría completa, incluidos datos generales, apertura, encuesta, balance institucional, tabla de indicadores, panel de seis participantes, intervención del Dr. Leonel Fernández, preguntas y respuestas, conclusiones, propuestas, compromisos y transcripción.

Las dos presentaciones originales están disponibles para consulta y descarga: registro de participantes (9 páginas) y balance de la Ley núm. 108-10 (11 páginas). Los tres documentos originales se copiaron sin modificar su contenido.

La fecha completa procede de la presentación del registro. La cifra de 103 corresponde a personas únicas registradas, no a asistencia comprobada. El sitio mantiene las respuestas posteriores identificadas como tales, conforme al Word, y no las presenta como intervenciones grabadas.

El texto conserva las cifras y atribuciones de cada fuente. La relatoría y la presentación difieren en el tamaño del tanque de agua (65,000 y 60,500 pies cuadrados, respectivamente); el sitio no sustituye esas cifras ni las mezcla. Del mismo modo, se conserva la referencia a un participante sin identificar en la síntesis aunque la transcripción nombre a Edwin Altemar Pérez en esa pregunta. Estas observaciones se documentan aquí para futuras revisiones del responsable editorial.

El contenido no constituye una nueva comprobación de cifras, normativa ni declaraciones. Los títulos de navegación y la introducción se añadieron para organizar la lectura, sin modificar la transcripción ni las respuestas del documento.

## Diseño y actualización

Estilo institucional en azul y dorado, párrafos justificados en escritorio e impresión, lectura móvil con alineación a la izquierda, navegación por secciones y crédito «Preparado por ODLC».

Para corregir el texto, abre `index.html` en GitHub, pulsa el lápiz y edita conservando las etiquetas HTML. Guarda con **Commit changes**. Los estilos están en `<style>` y las funciones en `<script>`.

El botón **Imprimir / PDF** imprime la relatoría web. Para imprimir una presentación, abre su PDF y utiliza el control de impresión del visor. En móvil los PDF pueden abrirse en la aplicación o visor configurado en el dispositivo.

Se incluyen título, descripción y Open Graph. Al conocer el enlace público definitivo pueden añadirse `canonical` y `og:url`. No utiliza cookies, analítica ni bibliotecas externas.
