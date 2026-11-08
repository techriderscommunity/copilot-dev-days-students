# Dev Days Students Madrid 2026 — Materiales

Presentaciones y repositorios de las charlas y talleres de **Dev Days Students Madrid 2026**.

[Web del evento](https://githubcopilotdevdaysmadrid.techriders.es/)

## Índice de materiales

Entrad en el enlace de vuestra sesión para consultar o añadir sus materiales. Las siete carpetas ya están preparadas; las presentaciones y los repositorios están pendientes de aportación por parte de los ponentes.

### Sesiones

- [Arantxa Delgado Ruiz — GitHub te representa: cómo mostrar lo que sabes hacer](<./Arantxa Delgado Ruiz - GitHub te representa - cómo mostrar lo que sabes hacer/>)
- [Manuel Fernandez — De prompts a contexto: cómo conseguir que los agentes de IA programen mejor sin quemar tokens](<./Manuel Fernandez - De prompts a contexto - cómo conseguir que los agentes de IA programen mejor sin quemar tokens/>)
- [Máximo Fernández Núñez — Agentes: cuando el LLM no es lo importante](<./Máximo Fernández Núñez - Agentes - cuando el LLM no es lo importante/>)
- [Antonio Leiva — Lo que Copilot no sabe hacer (todavía): MCP explicado con demos](<./Antonio Leiva - Lo que Copilot no sabe hacer (todavía) - MCP explicado con demos/>)
- [Raúl Antón y Mariano de la Fuente — Tu primer día como desarrollador… y tu compañero es GitHub Copilot](<./Raúl Antón y Mariano de la Fuente - Tu primer día como desarrollador y tu compañero es GitHub Copilot/>)

### Workshops

- [Rodrigo Liberoff y Borja Piris de Castro — Squad: Equipos de Agentes IA para Cualquier Proyecto con GitHub Copilot](<./Rodrigo Liberoff y Borja Piris de Castro - Squad - Equipos de Agentes IA para Cualquier Proyecto con GitHub Copilot/>)
- [Dachi Gogotchuri — Developer-centered AI engineering: build software with security, quality and governance](<./Dachi Gogotchuri - Developer-centered AI engineering - build software with security, quality and governance/>)

## Ponentes: subid los materiales a vuestra carpeta

No tenéis que crear carpetas ni copiar plantillas: **buscad vuestra sesión en el índice y utilizad la carpeta que ya está preparada**.

Cada carpeta sigue el formato `Nombre del ponente - Sesión` y contiene un `README.md` con los datos de la charla o el taller. Algunos signos de puntuación de los títulos se han sustituido u omitido en los nombres de carpeta para que sean compatibles con Windows.

1. Añadid vuestra presentación a esa carpeta, preferiblemente como `presentacion.pptx`. Podéis incluir también `presentacion.pdf`.
2. Contadnos en el `README.md` de vuestra sesión un breve resumen: en 2–3 frases, explicad de qué trata y qué se llevará quien consulte los materiales. Sustituid también los campos pendientes por el enlace a la presentación y la URL pública del repositorio con el código o las demos.
3. Enviad los cambios mediante un pull request siguiendo las instrucciones de abajo.

El resultado será:

```text
Nombre del ponente - Sesión/
├── README.md          # Datos de la sesión y enlaces a los materiales
├── presentacion.pptx  # Presentación aportada por el ponente
└── presentacion.pdf   # Opcional
```

**El repositorio de código se queda en vuestra cuenta.** Aquí solo tenéis que enlazarlo; no hace falta copiarlo ni transferirlo a la organización. Si la presentación es demasiado grande para subirla a GitHub, añadid un enlace público de descarga en el `README.md` de la sesión.

## Cómo enviar los cambios

### Si tenéis permisos de escritura

Clonad este repositorio y cread una rama para vuestra aportación:

```bash
git clone https://github.com/techriderscommunity/copilot-dev-days-students.git
cd copilot-dev-days-students
git switch -c materiales-mi-sesion
```

Añadid la presentación y editad el `README.md` dentro de vuestra carpeta. Después, guardad y subid los cambios, sustituyendo el nombre de carpeta del ejemplo por el vuestro:

```bash
git add -- "Nombre del ponente - Sesión"
git commit -m "docs: añadir materiales de mi sesión"
git push -u origin materiales-mi-sesion
```

En GitHub, abrid un **pull request hacia `main`** con el título `Materiales: Nombre del ponente - Sesión`. La organización revisará e incorporará la aportación.

### Si no tenéis permisos de escritura

Podéis clonar un repositorio público, pero **para subir cambios directamente necesitáis permisos de escritura**.

Si no los tenéis:

1. Haced **Fork** de [este repositorio del evento](https://github.com/techriderscommunity/copilot-dev-days-students) en vuestra cuenta.
2. Clonad vuestro fork en lugar del repositorio de la organización.
3. Seguid los mismos pasos de arriba: rama, materiales en vuestra carpeta, commit y push.
4. Desde vuestro fork, pulsad **Contribute → Open pull request**, con destino `techriderscommunity/copilot-dev-days-students`, rama `main`.

El fork es del repositorio del evento, no del repositorio de vuestra demo. No hace falta que la organización os añada como colaboradores para enviar un pull request desde un fork.

## Antes de enviarlo

- Comprobad que la presentación abre y que los enlaces son accesibles sin solicitar permisos.
- Sustituid los campos pendientes del `README.md` de vuestra sesión.
- Compartid únicamente materiales que tengáis permiso para publicar.
- No subáis credenciales, tokens, datos personales ni información confidencial.
- No incluyáis dependencias, binarios de compilación ni copias completas de otros repositorios.
