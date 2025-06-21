# Script de Encuestas Automáticas - Evaluación Docente UAN 📚✨

**Autor:** [HectorUwO](https://github.com/HectorUwO)

---

## 🚀 Descripción

Este script para ViolentMonkey (o gestores de UserScripts similares) está diseñado para **agilizar el proceso de llenado de las encuestas de Evaluación Docente** en la plataforma PIIDA de la Universidad Autónoma de Nayarit (UAN).

El script automatiza las partes más repetitivas:
* Abre cada encuesta de docente una por una.
* **Selecciona automáticamente la primera opción** en todas las preguntas de opción múltiple (radio buttons).
* Espera a que **tú revises y confirmes** haciendo clic manualmente en "Terminar Evaluación" o "Salir".
* Una vez que cierras una encuesta, el script procede con la siguiente.

✅ ¡El objetivo es ahorrarte tiempo sin quitarte el control final sobre tus respuestas!

---

## 🎯 Sitio de Aplicación

Este script está específicamente diseñado para funcionar en la siguiente URL:

* `https://alumnos.piida.uan.mx/evaluacion-docente/unidades*`

---

## 🛠️ Características Principales

* Automatización de la apertura secuencial de encuestas.
* Selección automática de la primera opción en preguntas de radio button.
* **Modo Interactivo:** El script espera tu acción manual (clic en "Terminar Evaluación" o "Salir") antes de continuar.
* Mensajes en la consola del navegador para guiarte durante el proceso.
* Diseñado para la interfaz de Evaluación Docente de la UAN.

---

## 📋 Requisitos Previos

1.  Un **navegador web moderno** (Chrome, Firefox, Edge, etc.).
2.  Una **extensión de gestión de UserScripts**. 
    * [Violentmonkey](https://violentmonkey.github.io) (Recomendada)
    * También puede funcionar con Greasemonkey (Firefox) o TemperMonkey.

---

## ⚙️ Instalación

1.  **Asegúrate de tener Violentmonkey** (o un gestor similar) instalado en tu navegador.
2.  **Instala el script:**
    * **Opción 1:**
        * Navega al archivo `script.js` en este repositorio de GitHub.
        * Haz clic en el botón "Raw".
        * Tampermonkey debería detectar automáticamente el script y ofrecerte instalarlo. Confirma la instalación.
    * **Opción 2 (Manual):**
        * Abre el panel de Tampermonkey en tu navegador.
        * Ve a "Crear un nuevo script..." o "Añadir script".
        * Copia todo el contenido del archivo `script.js` de este script.
        * Pega el contenido en el editor de Tampermonkey, reemplazando cualquier texto de plantilla.
        * Guarda el script (Archivo > Guardar).
   * **Opción 3 RECOMENDADA! (Desde Greasy Fork):**
        * Visita la página del script en Greasy Fork:
          [Script de Encuestas Automaticas de la Evaluacion Docente UAN 2025](https://greasyfork.org/es-419/scripts/538056-script-de-encuestas-automaticas-de-la-evaluacion-docente-uan-2025)
        * Haz clic en el botón verde que dice "Instalar este script" (o similar).
        * Tampermonkey se abrirá y te pedirá confirmación para instalar el script. ¡Confirma y listo!
      

---

## 📖 ¿Cómo Usarlo?

1.  Una vez instalado, **navega a la página de la Evaluación Docente de la UAN**:
    `https://alumnos.piida.uan.mx/evaluacion-docente/unidades` (o la subpágina específica donde aparezca la lista de docentes a evaluar).
2.  El script se **ejecutará automáticamente** después de unos segundos (verás mensajes en la consola del navegador, presiona F12 para abrirla).
3.  El script comenzará a **abrir la primera encuesta**, seleccionará la primera opción en cada pregunta y mostrará un mensaje en la consola indicando que debes actuar.
4.  **Revisa las opciones seleccionadas**. Si estás de acuerdo:
    * Haz clic en el botón "**Terminar Evaluación**" (para guardar y cerrar).
    * O haz clic en "**Salir**" (si así lo deseas).
5.  Una vez que el modal de la encuesta se cierre, el script **esperará un breve momento y procederá con la siguiente encuesta** de la lista, repitiendo el proceso.
6.  Continúa hasta que todas las encuestas hayan sido procesadas.

💡 **Consejo:** Mantén la consola de desarrollador de tu navegador (F12 > pestaña "Consola") abierta para ver los mensajes de estado del script (Solo si sabes que onda).

---

## ⚠️ Notas Importantes y Descargo de Responsabilidad

* **Uso Responsable:** Este script es una herramienta para ayudarte. Asegúrate de que las respuestas reflejen tu opinión honesta. Eres responsable de las evaluaciones que envías.
* **Periodo 2025:** El nombre del script incluye "2025", lo que afirma que está adaptado para el ciclo de evaluación de ese año. Si la interfaz de la página cambia en futuros ciclos, el script podría necesitar actualizaciones.
* **Cambios en la Web:** Si la estructura HTML de la página de evaluación docente de la UAN cambia significativamente, los selectores usados por el script podrían dejar de funcionar. En tal caso, el script requeriría una actualización.
* **Propósito:** Este script está pensado para uso personal y para facilitar una tarea repetitiva.
* **Revisión:** Aunque el script selecciona opciones, siempre tienes la oportunidad de revisarlas y cambiarlas antes de enviar la encuesta.

