# Habilidad crítica en acción

Herramienta interactiva de una sola página (HTML + CSS + JS, sin dependencias ni backend) para **ejercitar y reflexionar** sobre la combinación de habilidades sociales, técnicas y digitales que se requiere en nuevos entornos organizacionales.

## Idea pedagógica central

> **No basta con una habilidad aislada: la clave está en la combinación.**

Cada situación invita a elegir exactamente **3 habilidades** y luego muestra:
- Cuáles son **indispensables** (sin ellas la situación se resuelve mal),
- Cuáles **aportan** (mejoran la respuesta, pero no son críticas),
- Cuáles son **discutibles** (se pueden defender con argumentos),
- Y, sobre todo, la **combinación requerida** para enfrentar la situación con éxito.

El objetivo es evitar la sobrecarga cognitiva: 5 situaciones base + 2 avanzadas opcionales.

## Estructura del recorrido

| Bloque | Situaciones | Carácter |
|---|---|---|
| **Base** | 5 (desvinculación, caída de ventas, nuevo sistema, correo urgente, proveedor) | Obligatorio |
| **Desafío extra** | 2 (sesgo algorítmico, accesibilidad) | Opcional |

## Funcionalidades

- **Catálogo de 17 habilidades** en 3 familias: sociales (8), técnicas (6), digitales (3).
- **Pregunta de combinación** en cada análisis: *"¿Qué combinación se requiere para enfrentar la situación con éxito?"*
- **Justificación escrita** por situación (opcional, persistente, incluida en exportaciones).
- **Puntos ciegos acumulados** por familia en el perfil final.
- **Persistencia** en `localStorage` (progreso, justificaciones, nombre del alumno).
- **Identificación opcional** del alumno antes de exportar.
- **Exportación** en `.txt` (resumen legible) y `.json` (datos estructurados).
- **Modo docente** (toggle en el header):
  - Muestra las claves (`c` y `r`) dentro de cada situación, sin spoilear al alumno.
  - Habilita el **Panel docente** con resultados agregados.
- **Panel docente** (solo local, en el navegador):
  - Carga múltiples `.json` exportados por los alumnos.
  - Muestra: nº de respuestas, distribución por familia, habilidades más elegidas, puntos ciegos más frecuentes y **tabla por alumno**.
  - Exporta el reporte agregado en **CSV**.
  - Nada se envía a un servidor: todo ocurre en el navegador del docente.

## Cómo usarlo

### Alumno
1. Abrir `index.html` en un navegador moderno (o en GitHub Pages).
2. Recorrer las 5 situaciones base eligiendo 3 habilidades y justificando la combinación.
3. Leer el análisis y discutir la pregunta de reflexión.
4. Al final, revisar el perfil y, si se quiere, aceptar el desafío extra.
5. Exportar el resumen (`.txt`) o los datos (`.json`) y entregarlos al docente.

### Docente
1. Activar el **Modo docente** (botón arriba a la derecha).
2. Al recorrer una situación, ver el bloque *"Claves docentes"* con las indispensables y las que aportan.
3. Desde el perfil final del alumno o desde el botón **Panel docente**, abrir el panel de resultados agregados.
4. Arrastrar los `.json` recibidos de los alumnos.
5. Revisar métricas y exportar el reporte en `.csv`.

## Publicar en GitHub Pages

```bash
git init
git add .
git commit -m "Versión con combinación de habilidades, modo docente y panel agregado"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/habilidad-critica.git
git push -u origin main
