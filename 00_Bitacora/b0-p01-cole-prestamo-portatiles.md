- **Alumno:** Aarón Zaragoza García 
- **Bloque:** Practica_03_Cole_Inventario_Equipos
- **Fase / ejercicio:** Fase 0.2
- **Fecha de inicio:** 22/10/2026
- **Fecha de entrega:** 22/10/2026

---

## 🎯 Qué se pedía

Crear un inventario de equipos desde cero, guardarlo en tres versiones (3 commits) y despues de haber dejado de grabar hacer otro commit, todo esto usando usando una boveda de obsidian.

## ⌨️ Comandos y pasos importantes
pwd
git remote -v
git status
git log --oneline
git switch main
git switch --detach CODIGO_PRIMER_COMMIT
git status --short --untracked-files=all
git diff -- inventario/equipos.csv README.md
git check-ignore -v inventario/videos/revision-01.mp4 inventario/videos/revision-02.mp4
git push
git commit -m "Crear inventario inicial de equipos"
git commit -m "Actualizar ubicacion y estado de equipos"
git commit -m "Ampliar inventario y documentar mantenimiento"
## 🛠️ Qué he hecho

He hecho lo explicado en la pregunta 1.

## 🚩 Qué me ha fallado y cómo lo he resuelto

Me equivoque al hacer el primer commit y me toco volverlo a hacer desde el principio.

## 🤔 Respuestas a las preguntas
¿Por qué git init se hizo en 01_Proyecto y no en la raíz de la bóveda?
`git init` se hizo en `01_Proyecto` para controlar solo los archivos del proyecto web, no toda la bóveda.
¿Qué mostró git status antes de add , después de add y después de commit ?
`git status`: antes de `add`, archivos sin seguimiento; después de `add`, archivos preparados; después de `commit`, árbol de trabajo limpio.
¿Por qué creaste un repositorio de GitHub propio y lo conectaste con git remote add origin ?
Creé un repositorio propio en GitHub para guardar una copia remota y conectar el proyecto con `git remote add origin`.
¿Por qué las páginas nuevas aparecen en git status pero no en git diff -- web/index.html ?
Las páginas nuevas aparecen en `git status` porque Git detecta archivos nuevos, pero `git diff -- web/index.html` no muestra archivos sin seguimiento.
¿Cómo has comprobado que los vídeos existen pero no se van a subir?
Comprobé que los vídeos existen en la carpeta y que están excluidos mediante `.gitignore`.
¿Qué muestra git diff --cached --stat después de preparar los cuatro archivos?
`git diff --cached --stat` muestra un resumen de los cuatro archivos preparados, con sus cambios y líneas añadidas o eliminadas.
¿Qué cambia al visitar el primer commit y qué recuperas al volver a main ?
Al visitar el primer commit veo la versión inicial de la web. Al volver a `main`, recupero la versión actual.
¿Por qué esta web necesita historial? ¿Qué aportaría GitHub si otro técnico trabajase contigo?
La web necesita historial para recuperar versiones y controlar cambios. GitHub permitiría que otro
Si mañana corriges una errata en normas.html , ¿qué pasos repites y cuáles no?
Si corrijo una errata en `normas.html`

## 🔗 Enlaces

- **Vídeo de esta fase:** [https://youtu.be/euoWrYaX5zg](https://youtu.be/euoWrYaX5zg)
- **Playlist:** ### [B0.P01 · Cole · Préstamo de portátiles con Git y GitHub](https://studio.youtube.com/playlist/PLShsV6Ywtgx8/edit)

## 💭 Dudas / a repasar

- [ ] nada.