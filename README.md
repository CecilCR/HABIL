# Habilidad crítica en acción

Herramienta interactiva de una sola página (HTML + CSS + JS, sin dependencias) para **ejercitar y reflexionar** sobre las habilidades que marcan la diferencia en nuevos entornos organizacionales.

## ¿Qué hace?

- Presenta **7 situaciones** organizacionales (desvinculación, caída de ventas, cambio de sistema, fraude por correo, falla de proveedor, sesgo algorítmico, accesibilidad de herramientas).
- Pide elegir **exactamente 3 habilidades** de un catálogo de **17**, clasificadas en **3 familias**: sociales, técnicas y digitales.
- Muestra un **análisis por situación**: indispensables, aportan, discutibles y **puntos ciegos**.
- Al final entrega un **perfil** (reparto % por familia + puntos ciegos acumulados) con lectura pedagógica.
- Permite **justificar por escrito** cada elección y **exportar** el resumen en `.txt` o los datos en `.json`.
- **Guarda el progreso** en `localStorage`.

## Cómo usarlo

1. Abre `index.html` en un navegador moderno, o publica el repo con GitHub Pages.
2. Recorre las situaciones y elige tus 3 habilidades.
3. Lee el análisis y la reflexión, y discute con tu grupo.
4. Al final, descarga tu resumen.

## Publicar en GitHub Pages

```bash
git init
git add .
git commit -m "Versión inicial"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/habilidad-critica.git
git push -u origin main
