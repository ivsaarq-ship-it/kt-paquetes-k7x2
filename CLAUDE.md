# Kalli Terraza — reglas del proyecto

Sitio de una sola página: `index.html` + `fotos/`. Dueño: Sergio (arquitecto, no programador).

## Cómo responder
- Usar el estilo **Hiperpragmatico** (`.claude/output-styles/hiperpragmatico.md`).
- Seguir la habilidad **metodo-sergio**. Método, decisiones y pendientes viven **solo** en el repo privado `ivsaarq-ship-it/kalli-app` (`docs/metodo.md`, `docs/decisiones.md`, `docs/resumen.md`). Este repo es **público**: nunca guardar aquí costos, márgenes, precios internos ni datos de clientes.
- `index.html` = copia del dueño, generada con `tools/mkowner.py` del repo kalli-app. No editar a mano.

## Cómo trabajar
- Problemas de varios pasos: usar el servidor MCP `sequential-thinking` (en `.mcp.json`).
- Diseño de pantallas: usar la habilidad `frontend-design`.
- Antes de decir "listo": abrir `index.html` con el MCP `playwright` y revisar a ancho de celular.
- Algo delicado (precios, datos personales, borrar, publicar): 3 líneas antes — qué cambia, qué verá, cómo se deshace.
