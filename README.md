# 💼 Portafolio Personal

Portafolio web moderno y minimalista construido con Astro, con animaciones fluidas y diseño responsive.

## ✨ Características

- 🚀 **Astro** - Framework web moderno y ultra rápido
- 🎨 **Diseño Minimalista** - Interfaz limpia y profesional
- 📱 **Responsive** - Adaptado a todos los dispositivos
- ⚡ **Animaciones** - Usando GSAP para transiciones suaves
- 🎯 **Smooth Scroll** - Navegación fluida con Lenis
- 🔍 **SEO Optimizado** - Meta tags y estructura semántica
- 🎭 **Iconos Lucide** - Iconos modernos y escalables

## 📁 Estructura del Proyecto

```text
/
├── public/              # Archivos estáticos
├── src/
│   ├── assets/         # Imágenes y recursos
│   ├── components/     # Componentes de Astro
│   │   ├── Profile.astro
│   │   ├── Experience.astro
│   │   ├── Projects.astro
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   └── Header.astro
│   ├── layouts/        # Layouts reutilizables
│   │   └── Layout.astro
│   ├── pages/          # Páginas del sitio
│   │   └── index.astro
│   └── styles/         # Estilos CSS
│       ├── global.css
│       ├── profile.css
│       ├── experience.css
│       ├── projects.css
│       ├── about.css
│       ├── contact.css
│       └── header.css
├── astro.config.mjs    # Configuración de Astro
└── package.json
```

## 🛠️ Tecnologías

- **Framework:** Astro 5.16.6
- **Animaciones:** GSAP 3.14.2
- **Smooth Scroll:** Lenis 1.3.17
- **Iconos:** Lucide Astro 0.562.0
- **Optimización de Imágenes:** Sharp 0.34.5
- **Package Manager:** pnpm

## 🚀 Instalación y Uso

### Prerrequisitos

- Node.js 18+ instalado
- pnpm instalado globalmente

```bash
npm install -g pnpm
```

### Instalación

1. Clona el repositorio:

```bash
git clone <tu-repositorio>
cd portafolio
```

2. Instala las dependencias:

```bash
pnpm install
```

### Comandos Disponibles

| Comando          | Acción                                               |
| :--------------- | :--------------------------------------------------- |
| `pnpm dev`       | Inicia el servidor de desarrollo en `localhost:4321` |
| `pnpm build`     | Construye el sitio para producción en `./dist/`      |
| `pnpm preview`   | Previsualiza la build localmente                     |
| `pnpm astro ...` | Ejecuta comandos de la CLI de Astro                  |

## 🎨 Secciones

El portafolio incluye las siguientes secciones:

- **Profile** - Presentación personal y foto de perfil
- **Experience** - Experiencia laboral y habilidades
- **Projects** - Proyectos destacados con enlaces
- **About** - Información adicional y biografía
- **Contact** - Formulario y enlaces de contacto

## 🌐 Despliegue

Este proyecto puede ser desplegado en cualquier plataforma que soporte sitios estáticos:

- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- [GitHub Pages](https://pages.github.com)
- [Cloudflare Pages](https://pages.cloudflare.com)

### Ejemplo con Vercel:

```bash
pnpm build
vercel deploy --prod
```

## 📝 Personalización

1. **Contenido**: Edita los componentes en `src/components/` para actualizar tu información
2. **Estilos**: Modifica los archivos CSS en `src/styles/` para cambiar colores y diseño
3. **Imágenes**: Añade tus recursos en `src/assets/` o `public/`
4. **Configuración**: Ajusta `astro.config.mjs` según tus necesidades

## 📄 Licencia

Este proyecto está bajo la licencia especificada en el archivo [LICENSE](LICENSE).

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes sugerencias, por favor abre un issue o pull request.

---

Hecho con ❤️ usando [Astro](https://astro.build)
