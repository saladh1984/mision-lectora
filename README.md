# Misión Lectora

App web para preparar una prueba de comprensión lectora de 6.° básico (Taller de Lectoescritura, Chile, OA 02).
Entrena cuatro habilidades: **localizar, inferir, sintetizar y reflexionar** (con el modelo **RICE**).

Todo está en un solo archivo: [`mision-lectora.html`](mision-lectora.html) (React + Babel desde CDN; requiere internet).

## Módulos

| Etapa | Módulo | Estado |
|---|---|---|
| 1 | Inicio (cuenta regresiva, progreso, medallas) | ✅ |
| 1 | Aprende (fichas por habilidad) | ✅ |
| 1 | Lecturas modelo con claves + «Mis 10 claves» | ✅ |
| 1 | Zona de ejercicios (opción múltiple, unir, V/F, vocabulario) | ✅ |
| 1 | Plan de 5 días | ✅ |
| 2 | Subrayado, Taller RICE, Práctica, Detective, Ensayo, Retroalimentación | Pendiente |

## Cómo usarla

- Abre `mision-lectora.html` en el navegador (doble clic), o publica el repositorio con GitHub Pages.
- El progreso se guarda en el navegador (`localStorage`) y se puede reiniciar desde el menú.

## Cómo agregar contenido

Los textos, preguntas, ejercicios y el plan están en `window.DATA` y la configuración (nombre, fecha, colores del subrayado) en `window.CONFIG`, al inicio del archivo.
Para agregar un ejercicio, copia uno existente y cambia su `id`.

Todos los textos de práctica son originales.
