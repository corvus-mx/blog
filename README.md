# HorseWriter Blog

Blog profesional de Alejandro - Ghostwriter y Copywriter con 5 años de experiencia.

## 🚀 Características

- **Astro** - Framework moderno para sitios web estáticos
- **Tailwind CSS** - Estilos utilitarios para diseño responsive
- **MDX** - Soporte para contenido Markdown con componentes
- **Diseño responsive** - Optimizado para todos los dispositivos
- **SEO optimizado** - Meta tags y estructura semántica

## 📝 Contenido

El blog incluye diferentes tipos de contenido:

- **Relatos** - Historias creativas y narrativas
- **Cuentos** - Narrativas cortas con mensaje
- **Crónicas** - Experiencias personales y profesionales
- **Artículos** - Contenido educativo sobre escritura y copywriting

## 🛠️ Desarrollo

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo
npm run dev

# Build para producción
npm run build

# Preview del build
npm run preview
```

## 📁 Estructura del proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   └── PostCard.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       ├── about.astro
│       ├── posts.astro
│       └── posts/
│           ├── [slug].astro
│           └── *.md
└── package.json
```

## 🎨 Personalización

El blog utiliza un sistema de colores personalizado:

- **Navy**: #1e3a8a (Azul principal)
- **Sand**: #f5deb3 (Dorado/arena para acentos)
- **Dark BG**: #0f172a (Fondo oscuro)
- **Card BG**: #1e293b (Fondo de tarjetas)

## 📱 Responsive Design

El diseño está optimizado para:
- Mobile (320px+)
- Tablet (768px+)
- Desktop (1024px+)

## 🚀 Deploy en Netlify

El proyecto está configurado para deploy automático en Netlify con:
- Build command: `npm run build`
- Publish directory: `dist`