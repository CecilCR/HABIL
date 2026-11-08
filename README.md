# Habilidad crítica en acción

Herramienta interactiva de una sola página (HTML + CSS + JS, sin dependencias ni backend) para **ejercitar y reflexionar** sobre la combinación de habilidades sociales, técnicas y digitales que se requiere en nuevos entornos organizacionales.

## Idea pedagógica central

> **No basta con una habilidad aislada: la clave está en la combinación.**

El recorrido comienza con una **pantalla de bienvenida** que explica el objetivo: no se trata de elegir la habilidad "más importante", sino de encontrar la mejor combinación (social, técnica o digital) para resolver cada situación con éxito.

## Estructura del recorrido

| Bloque | Situaciones | Carácter |
|---|---|---|
| **Base** | 5 (desvinculación, caída de ventas, nuevo sistema, correo urgente, proveedor) | Obligatorio |
| **Desafío extra** | 2 (sesgo algorítmico, accesibilidad) | Opcional al finalizar las 5 base |

## Funcionalidades

- **Pantalla de bienvenida** con gráfico de las tres familias y explicación de la consigna.
- **Catálogo de 17 habilidades** en 3 familias: sociales (8), técnicas (6), digitales (3).
- **Pregunta de combinación** en cada análisis: *"¿Qué combinación se requiere para enfrentar la situación con éxito?"*
- **Justificación escrita** por situación (opcional, persistente, incluida en exportaciones).
- **Puntos ciegos acumulados** por familia en el perfil final.
- **Persistencia** en `localStorage` (progreso, justificaciones, nombre del alumno).
- **Identificación opcional** del alumno antes de exportar.
- **Exportación** en `.txt` (resumen legible) y `.json` (datos estructurados para analítica externa).

## Cómo usarlo

1. Abrir `index.html` en un navegador moderno (o en GitHub Pages).
2. Leer la pantalla de bienvenida y comenzar.
3. Recorrer las 5 situaciones base eligiendo 3 habilidades y justificando la combinación.
4. Leer el análisis y discutir la pregunta de reflexión.
5. Al final, revisar el perfil, identificarse (opcional) y exportar el resumen (`.txt`) o los datos (`.json`) para entregar al docente.
6. Opcionalmente, aceptar el desafío extra.

## Publicar en GitHub Pages

```bash
git init
git add .
git commit -m "Versión con pantalla de bienvenida y combinación de habilidades"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/habilidad-critica.git
git push -u origin main
