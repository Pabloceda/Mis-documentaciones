---
date: 2026-01-16
authors:
  - pablo
categories:
  - Tutorial
tags:
  - MkDocs
  - Documentación
  - Portfolio
readtime: 3
---

# Creando mi Portfolio con Material for MkDocs

En este primer post del blog, comparto cómo he creado este sitio de documentación y portfolio usando Material for MkDocs.

<!-- more -->

## ¿Por qué Material for MkDocs?

Material for MkDocs es una herramienta excelente para crear documentación técnica profesional. Algunas de sus ventajas:

- ✅ **Markdown**: Escribir en Markdown es simple y rápido
- ✅ **Diseño moderno**: Material Design con modo oscuro/claro
- ✅ **Plugins potentes**: Blog, tags, búsqueda, social cards
- ✅ **Gratis**: Deploy gratuito en GitHub Pages

## Configuración Básica

### Instalación

```bash
pip install mkdocs-material
mkdocs new mi-sitio
cd mi-sitio
mkdocs serve
```

### Estructura del Proyecto

```
mi-sitio/
├── docs/
│   ├── index.md
│   └── ...
├── mkdocs.yml
└── venv/
```

## Próximos Pasos

En próximos posts cubriré:

- [ ] Configuración avanzada de plugins
- [ ] Personalización del tema
- [ ] Integración con GitHub Actions
- [ ] Creación de contenido dinámico

!!! tip "Consejo"
    Empieza con la configuración básica y ve añadiendo features gradualmente.

---

¡Gracias por leer! Si tienes preguntas, no dudes en contactarme.
