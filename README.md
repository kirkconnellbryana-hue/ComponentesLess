# 5 Componentes con LESS — Vite MPA

Trabajo 2: Página con 5 componentes UI desarrollados en Vite (MPA) con LESS.

## Características
- ✅ Bundler: **Vite** (MPA — Multi Page Application)
- ✅ CSS: **LESS** con arquitectura modular (un archivo .less por componente)
- ✅ Minificado y optimizado para producción
- ✅ Animaciones con IntersectionObserver
- ✅ Totalmente responsivo

## Componentes (5)
1. **NavBar** — Navegación fija con burger menu y scroll activo
2. **Hero Panel** — Sección principal con blobs animados y estadísticas
3. **Cards** — Grid de 5 tarjetas de blog (mínimo 3 requeridas)
4. **Half Inverted Panel** — Secciones alternadas texto/imagen
5. **Footer** — Pie de página completo con newsletter y columnas

## Arquitectura LESS
```
src/styles/
├── variables.less   → Variables globales y mixins
├── navbar.less      → Componente NavBar
├── hero.less        → Componente Hero Panel
├── cards.less       → Componente Cards
├── half-panel.less  → Componente Half Inverted Panel
├── footer.less      → Componente Footer
└── main.less        → Import general y estilos base
```

## Scripts
```bash
npm install       # Instalar dependencias
npm run dev       # Servidor de desarrollo
npm run build     # Build de producción (dist/)
npm run preview   # Preview del build
```

## Entrega
- 📁 Repositorio: `https://github.com/<usuario>/<repositorio>`
