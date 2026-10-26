# Portafolio — Daniel Alberto Fernández Botero

Sitio personal de **Daniel Alberto Fernández Botero**, desarrollador Full Stack e ingeniero de sistemas en Cartagena, Colombia. Una sola página estática, sin frameworks ni build: HTML, CSS y JavaScript puro, publicada en GitHub Pages.

[![Deploy](https://github.com/danielfernandezb/portafolio-daniel/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/danielfernandezb/portafolio-daniel/actions/workflows/deploy-pages.yml)
[![Demo en vivo](https://img.shields.io/badge/demo-en%20vivo-c9f27c?style=for-the-badge&labelColor=101a2b)](https://danielfernandezb.github.io/portafolio-daniel/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=101a2b)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=101a2b)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=101a2b&labelColor=101a2b)](#)

**Demo:** https://danielfernandezb.github.io/portafolio-daniel/

---

## Qué contiene

| Sección | Contenido |
| --- | --- |
| Inicio | Presentación, propuesta de valor y llamadas a la acción |
| Proyectos | Casos reales con enlace al sitio en producción |
| Perfil | Trayectoria, formación y datos de contacto profesionales |
| Tecnologías | Shopify, React, Angular, SQL, VPS, Python y más |
| Experiencia | Línea de tiempo 2020 — 2026 |
| Contacto | LinkedIn, GitHub y teléfono |

## Proyectos enlazados

- [Melissa Oficial](https://melissaoficial.com.co/) — e-commerce Shopify
- [Route Store CTG](https://routestorectg.com/) — e-commerce Shopify
- [Sandalias Colombia](https://sandaliascolombia.com.co/) — e-commerce multimarca
- [Hyam Food](https://hyamfood.com/) — aplicación web (Angular / React)
- Landing pages: [Ipanema](https://ipanema.com.co/) · [Azaleia](https://azaleia.com.co/) · [Rider](https://rider.com.co/) · [Zaxy](https://zaxy.com.co/)

## Cómo verlo en local

No requiere instalación de dependencias. Clona el repositorio y abre `index.html`:

```bash
git clone https://github.com/danielfernandezb/portafolio-daniel.git
cd portafolio-daniel
```

Con doble clic en `index.html` funciona. Si prefieres servirlo por HTTP:

```bash
python -m http.server 8000
# luego abre http://localhost:8000
```

## Estructura

```
portafolio-daniel/
├── index.html   # Todo el sitio: estilos, contenido y script
└── README.md
```

## Detalles técnicos

- **Sin dependencias**: cero npm, cero bundler, carga instantánea.
- **Diseño responsive** con `clamp()` y media queries (corte principal en 760 px).
- **Accesibilidad**: HTML semántico, `lang="es"`, `aria-label` en navegación y enlaces externos, foco visible y soporte de `prefers-reduced-motion`.
- **SEO**: `meta description`, `theme-color`, `preconnect` de fuentes y títulos descriptivos.
- **Despliegue**: GitHub Pages (build legacy) desde la rama `main`.

## Autor

**Daniel Alberto Fernández Botero** — Desarrollador Full Stack · Ingeniero de Sistemas
Cartagena, Colombia · [LinkedIn](https://www.linkedin.com/in/daniel-fern%C3%A1ndez-100552263/) · [GitHub](https://github.com/danielfernandezb)
