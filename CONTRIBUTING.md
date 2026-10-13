# Guía de Contribución (Proyecto de Clase 💀)

¡Buenas! Si estás leyendo esto, te ha tocado sufrir este proyecto de web con nosotros. Como es una práctica de clase sin pretensiones donde lo importante es aprobar y no morir en el intento, vamos a mantener las reglas de colaboración simples para no volvernos locos, pero intentando mantener un mínimo de orden.

---

## 1. Convención de Nombres de Rama (`branch naming`)

Por favor, no subas todo a `main` directamente a lo loco. Crea una rama descriptiva para lo que estés haciendo usando este formato genérico:

`tipo/nombre-corto`

*   `feature/` - Para añadir algo nuevo (ej. `feature/contacto`, `feature/footer-cutre`).
*   `fix/` - Para arreglar algo que se ha roto (ej. `fix/css-roto`, `fix/enlaces-rotos`).
*   `docs/` - Para tocar el README o cosas de documentación (ej. `docs/actualizar-readme`).

**Ejemplo:** `git checkout -b feature/formulario-contacto`

---

## 2. Formato de los Mensajes de Commit (`commit messages`)

Intenta que los mensajes tengan un mínimo de sentido para saber qué has tocado si algo explota. Nada de "asdfgh" o "cambios". 

Usa verbos en imperativo y sé breve:

*   `feat: añade la estructura básica del index`
*   `fix: arregla el margen gigante del header`
*   `style: centra los botones con flexbox`
*   `docs: añade este maravilloso CONTRIBUTING.md`

---

## 3. ¿Qué debe incluir una Pull Request (PR)?

Cuando termines tu parte y quieras meterla en `main`, abre una Pull Request y asegúrate de cumplir lo siguiente:

1.  **Título claro:** Que resuma qué has hecho (ej. *Añadida la página de galería*).
2.  **Descripción corta:** Explica en una línea qué hace el cambio por si acaso.
3.  **Checklist básico (Mental o en texto):**
    *   [ ] Funciona en local y no da errores raros en la consola del navegador.
    *   [ ] No has borrado el código de otro compañero por accidente.
    *   [ ] La web sigue abriendo con un doble clic en el `index.html` o con el servidor local que usemos.
4.  **Revisión:** Pídele a otro compi del grupo que le eche un ojo rápido y le dé al botón de aprobar para poder hacer el *merge*.

¡Y ya estaría! Mucha suerte sobreviviendo a la entrega.