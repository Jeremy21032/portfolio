# 📝 Instrucciones de Personalización - Portafolio Jeremy León

## ✅ Ya Personalizado

- ✅ Nombre: Jeremy León
- ✅ Estructura base lista
- ✅ Componentes actualizados

## 📋 Información que Necesitas Completar

### 1. Hero.astro (`src/components/Hero.astro`)

**Línea 101**: Actualiza la descripción con tu información:
```astro
<p class="...">
  Tu descripción profesional aquí. <strong>Tu especialidad</strong> y ubicación.
</p>
```

**Líneas 108-120**: Actualiza tus redes sociales:
```astro
<SocialPill href="https://github.com/tu-usuario">
  <GitHubIcon class="size-4 md:size-6" />
  GitHub
</SocialPill>
<SocialPill href="https://linkedin.com/in/tu-perfil">
  <LinkedInIcon class="size-4 md:size-6" />
  LinkedIn
</SocialPill>
<SocialPill href="mailto:tu-email@ejemplo.com">
  <MailIcon class="size-4 md:size-6" />
  Contáctame
</SocialPill>
```

### 2. AboutMe.astro (`src/components/AboutMe.astro`)

**Líneas 11-30**: Personaliza tu biografía:
- Tu experiencia profesional
- Proyectos destacados
- Tu pasión por la tecnología
- Logros importantes

### 3. Experience.astro (`src/components/Experience.astro`)

**Líneas 3-20**: Agrega tu experiencia laboral del CV:

```javascript
const EXPERIENCE = [
  {
    date: "Enero 2020 - Presente",
    title: "Desarrollador Full Stack",
    company: "Nombre de la Empresa",
    description: "Descripción detallada de tus responsabilidades y logros...",
    technologies: ["javascript", "typescript", "react", "node", "postgresql"],
  },
  // Agrega más trabajos
];
```

**Tecnologías disponibles para usar:**
- `"javascript"`, `"typescript"`, `"react"`, `"vue"`, `"node"`
- `"azure"`, `"postgresql"`, `"mongodb"`, `"redis"`
- `"golang"`, `"php"`, `"docker"`, `"kubernetes"`
- `"google"`, `"firebase"`, `"gitlab"`, `"html"`, `"css"`, `"joomla"`

### 4. Projects.astro (`src/components/Projects.astro`)

**Líneas 52-70**: Agrega tus proyectos:

```javascript
const PROJECTS = [
  {
    title: "Nombre del Proyecto",
    description: "Descripción del proyecto...",
    link: "https://proyecto.com", // Opcional
    github: "https://github.com/usuario/proyecto", // Opcional
    image: "/projects/nombre-imagen.webp",
    tags: [TAGS.JAVASCRIPT, TAGS.REACT, TAGS.TAILWIND],
  },
];
```

**Tags disponibles:**
- `TAGS.NEXT`, `TAGS.TAILWIND`, `TAGS.JAVASCRIPT`
- `TAGS.HTML`, `TAGS.CSS`, `TAGS.FLUTTER`

### 5. Header.astro (`src/components/Header.astro`)

**Línea 28**: Actualiza el email de contacto:
```astro
url: "mailto:tu-email@ejemplo.com"
```

### 6. Imágenes

Necesitas agregar estas imágenes en `public/`:

- **Foto de perfil**: `public/fotoperfil.webp` (reemplaza la actual)
- **Imagen sobre ti**: `public/yopatines.webp` (opcional, puedes usar otra)
- **Proyectos**: Agrega imágenes en `public/projects/` para cada proyecto

### 7. astro.config.mjs

**Línea 9**: Actualiza con tu URL de Vercel cuando despliegues:
```javascript
site: 'https://tu-dominio.vercel.app'
```

## 🚀 Comandos

```bash
# Instalar dependencias
npm install

# Desarrollo
npm run dev

# Construir para producción
npm run build

# Preview de producción
npm run preview
```

## 📦 Desplegar en Vercel

1. Sube tu código a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Importa tu repositorio
4. Vercel detectará automáticamente que es Astro
5. ¡Listo!

## 📄 CV

Tu CV ya está en `portfolio/static/Jeremy_León_CV(E).pdf`. Puedes:
- Agregarlo a `porfoliov1/public/` si quieres enlazarlo
- O crear un enlace directo en el Hero o Footer

---

**¡Todo listo para personalizar!** Solo completa la información de tu CV en los componentes indicados.

