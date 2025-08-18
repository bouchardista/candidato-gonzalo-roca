# Landing Page - Candidato Alianza La Libertad Avanza

Landing page moderna y responsive para mostrar información de un candidato de Alianza La Libertad Avanza.

## Características

- 🎨 Diseño moderno con gradiente violeta
- 📱 Totalmente responsive
- ⚡ Construido con Nuxt 3 y Tailwind CSS
- 🎯 SEO optimizado
- 🔧 Fácil de personalizar

## Tecnologías

- **Nuxt 3** - Framework de Vue.js
- **Tailwind CSS** - Framework de CSS
- **Nuxt Icon** - Iconos
- **Vue 3** - Framework de JavaScript

## Instalación

1. Clona el repositorio:
```bash
git clone [URL_DEL_REPO]
cd candidato-landing
```

2. Instala las dependencias:
```bash
npm install
# o
yarn install
```

3. Ejecuta el servidor de desarrollo:
```bash
npm run dev
# o
yarn dev
```

4. Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

## Personalización

### Información del Candidato

Edita el archivo `pages/index.vue` para personalizar:

- **Nombre del candidato**: Reemplaza `[Nombre del Candidato]` y `[Nombre Completo]`
- **Cargo**: Reemplaza `[Cargo]` con el cargo al que se postula
- **Descripción**: Reemplaza los textos entre `[ ]` con la información real
- **Formación y experiencia**: Actualiza con los datos reales
- **Propuestas**: Personaliza cada sección de propuestas
- **Contacto**: Actualiza email, teléfono y dirección

### Imágenes

Coloca las siguientes imágenes en la carpeta `public/`:

- `logo-white.png` - Logo de Alianza La Libertad Avanza (fondo transparente)
- `candidato-foto.jpg` - Foto del candidato (formato cuadrado recomendado)

### Colores

Los colores principales están definidos en `tailwind.config.js`:

- **Primary**: Violeta (gradiente principal)
- **Secondary**: Naranja
- **Accent**: Amarillo dorado (#EFB141)
- **Accent-hover**: Naranja (#E36030)

## Estructura del Proyecto

```
candidato-landing/
├── pages/
│   └── index.vue          # Página principal
├── components/            # Componentes reutilizables
├── public/               # Archivos estáticos
│   ├── logo-white.png
│   └── candidato-foto.jpg
├── assets/               # Assets (CSS, imágenes)
├── nuxt.config.ts        # Configuración de Nuxt
├── tailwind.config.js    # Configuración de Tailwind
└── package.json          # Dependencias
```

## Build para Producción

```bash
npm run build
# o
yarn build
```

## Despliegue

El proyecto se puede desplegar en:

- **Vercel**: Conecta tu repositorio de GitHub
- **Netlify**: Arrastra la carpeta `dist` después del build
- **GitHub Pages**: Configura GitHub Actions
- **Cualquier hosting estático**

## Licencia

Este proyecto es privado para Alianza La Libertad Avanza.

## Soporte

Para soporte técnico, contacta al equipo de desarrollo.
