# Materiales — Dev Days Students Madrid 2026

Repositorio para compartir los materiales de las charlas y talleres de [Dev Days Students Madrid 2026](https://githubcopilotdevdaysmadrid.techriders.es/).

Ponentes: podéis añadir aquí el código o repositorio de vuestra sesión y las diapositivas. Así, las personas asistentes podrán consultarlos después del evento.

## Cómo aportar materiales

1. Crea una carpeta en `materiales/` con un nombre corto y descriptivo, por ejemplo `materiales/agentes-con-github-copilot/`.
2. Añade dentro un `README.md` con el título de la sesión, los nombres de las personas ponentes y una breve descripción.
3. Incluye los materiales:
   - Presentación en PDF y, si quieres, también en PowerPoint (`.pptx`).
   - Enlace al repositorio de código, o el código en una subcarpeta `codigo/`.
4. Abre un *pull request* con los cambios. Si no tienes permisos para contribuir directamente, crea un *fork* y abre el *pull request* desde allí.

Estructura sugerida:

```text
materiales/
└── nombre-corto-de-la-sesion/
    ├── README.md
    ├── presentacion.pdf
    ├── presentacion.pptx
    └── codigo/                 # Opcional: código fuente de la sesión
```

Si el código ya está publicado en otro repositorio, basta con añadir su URL en el `README.md` de la sesión; no hace falta copiarlo aquí. Si lo incluyes, sube los archivos del proyecto, no una carpeta `.git` anidada.

## Plantilla para la sesión

Puedes copiar esta plantilla en `materiales/nombre-corto-de-la-sesion/README.md`:

```markdown
# Título de la sesión

- **Ponente(s):** Nombre y apellidos
- **Repositorio:** URL del repositorio o ruta a `codigo/`
- **Presentación:** `presentacion.pdf` (y/o `presentacion.pptx`)

Breve descripción de la sesión y de los materiales.
```

## Antes de enviar el *pull request*

- Comprueba que los enlaces y archivos se pueden abrir.
- No subas credenciales, tokens, datos personales ni información confidencial.
- Comparte únicamente materiales que tengas permiso para publicar.
- Para archivos grandes, añade un enlace de descarga en lugar de subirlos al repositorio.
