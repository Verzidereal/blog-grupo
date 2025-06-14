# Blog grupal con Hugo

## Descripción

Este es un blog estático generado con Hugo, un CMS libre y rápido que permite crear sitios web estáticos con facilidad. El sitio está desplegado en [Vercel](https://vercel.com) para una entrega rápida y segura.

---

## Tecnologías utilizadas

- **CMS:** Hugo (https://gohugo.io)
- **Tema:** Ananke (https://github.com/theNewDynamic/gohugo-theme-ananke)
- **Hosting:** Vercel (https://vercel.com)

---

## Estructura del proyecto

.
├── archetypes/
├── config.toml
├── content/
│ └── posts/
├── layouts/
├── public/
├── static/
├── themes/
│ └── ananke/
├── README.md
└── ...

---

## Instalación local

### Requisitos previos

- Tener instalado [Hugo](https://gohugo.io/getting-started/installing/) (versión >= 0.124.1)
- Git instalado

### Pasos para correr el sitio localmente

```bash
git clone https://github.com/<Verzidereal>/<blog-grupo>.git
cd <blog-grupo>
hugo serve
Luego abre en el navegador http://localhost:1313 para ver el sitio.

Despliegue en Vercel
El proyecto está configurado para desplegarse automáticamente en Vercel desde la rama main.

Configuración en Vercel:

Framework preset: Other

Build command: hugo

Output directory: public

Variable de entorno: HUGO_VERSION = 0.124.1

Este blog es un proyecto grupal donde cada miembro contribuye con una publicación relacionada con ventajas del software libre.

Crear una rama para tu post:

git checkout -b nombre-de-tu-rama
Crear un archivo Markdown para tu post en content/posts/, por ejemplo:

hugo new posts/mi-post.md
Editar el archivo con tu contenido.

Hacer commit y push:

git add content/posts/mi-post.md
git commit -m "Agrega post sobre <tema>"
git push origin nombre-de-tu-rama
Crear un Pull Request para revisión.

Recursos libres para imágenes e iconos
Flaticon (con licencia CC BY)

Unsplash

Contacto
Para dudas o ayuda, contactar a minquizescolar@gmail.com

© 2025 Blog Grupal Hugo
