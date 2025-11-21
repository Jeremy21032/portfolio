# 🚀 Portafolio de Jeremy León

Portafolio personal desarrollado con [Astro](https://astro.build), [Tailwind CSS](https://tailwindcss.com) y TypeScript.

## ✨ Características

- ⚡ Astro para máximo rendimiento
- 🎨 Tailwind CSS para estilos
- 🌙 Modo oscuro/claro
- 📱 Totalmente responsive
- 🚀 Optimizado para Vercel
- ⚙️ TypeScript para type safety

## 🛠️ Tecnologías

- **Astro** - Framework web moderno
- **Tailwind CSS** - Framework de CSS utility-first
- **TypeScript** - Tipado estático
- **Vercel** - Hosting y despliegue

## 📦 Instalación

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Preview de producción
npm run preview
```

## 🎯 Personalización

### Información Principal

1. **Hero** (`src/components/Hero.astro`)
   - Nombre: ✅ Ya actualizado a "Jeremy León"
   - Descripción: Actualiza con tu información profesional
   - Redes sociales: Actualiza GitHub, LinkedIn y email

2. **Sobre Mí** (`src/components/AboutMe.astro`)
   - Biografía: Escribe sobre ti, tu experiencia y proyectos destacados

3. **Experiencia** (`src/components/Experience.astro`)
   - Agrega tus trabajos del CV en el array `EXPERIENCE`

4. **Proyectos** (`src/components/Projects.astro`)
   - Agrega tus proyectos en el array `PROJECTS`

### Imágenes

Agrega estas imágenes en `public/`:
- `fotoperfil.webp` - Tu foto de perfil
- `projects/*.webp` - Imágenes de tus proyectos

### Configuración

- `astro.config.mjs` - Actualiza la URL del sitio cuando despliegues

## 📄 CV

Tu CV está en `portfolio/static/Jeremy_León_CV(E).pdf`. Puedes:
- Copiarlo a `porfoliov1/public/` si quieres enlazarlo
- O crear un enlace directo en el Hero o Footer

## 🚀 Despliegue en Vercel

### Opción 1: Desde GitHub

1. Sube tu código a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Importa tu repositorio
4. Vercel detectará automáticamente Astro
5. Haz clic en "Deploy"

### Opción 2: Desde CLI

```bash
npm i -g vercel
vercel
```

## 📝 Estructura del Proyecto

```
porfoliov1/
├── public/          # Archivos estáticos (imágenes, favicon)
├── src/
│   ├── components/  # Componentes Astro
│   │   ├── Hero.astro
│   │   ├── AboutMe.astro
│   │   ├── Experience.astro
│   │   ├── Projects.astro
│   │   └── ...
│   ├── layouts/     # Layouts
│   └── pages/       # Páginas
├── astro.config.mjs # Configuración de Astro
└── package.json
```

## 📚 Documentación

- [Astro Docs](https://docs.astro.build)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [Vercel Docs](https://vercel.com/docs)

## 📞 Soporte

Para más detalles sobre cómo personalizar, revisa `INSTRUCCIONES_PERSONALIZACION.md`

---

**¡Listo para personalizar y desplegar!** 🎉

