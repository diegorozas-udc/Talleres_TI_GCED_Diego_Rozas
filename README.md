# Prácticas de Teoría de la Información 
_Grado Ciencia e Ingeniería de Datos (GCED) de la Universidade da Coruña (Facultad de A Coruña)_

## Entorno recomendado por la asignatura

En esta asignatura se **recomienda explícitamente** el uso de **GitHub Codespaces** como entorno de trabajo para las prácticas.

La razón es sencilla:

- Permite que **todos los estudiantes trabajen con el mismo entorno**
- Evita problemas de instalación y configuración de Python y librerías
- Facilita el seguimiento de las prácticas y la resolución de dudas
- Permite centrarse en los **contenidos de la asignatura**, no en aspectos técnicos

Este repositorio está diseñado **pensando en GitHub Codespaces** y es la opción que se utilizará y apoyará desde la asignatura.

---

## ⚠️ Sobre el uso de otros entornos

Es posible trabajar con un entorno local propio (Python instalado en el ordenador, entornos virtuales, etc.), pero:

- **no es la opción recomendada**
- la asignatura **no dará soporte** a problemas derivados de instalaciones locales
- el correcto funcionamiento de los cuadernos **solo está garantizado en GitHub Codespaces**

Por este motivo, se aconseja encarecidamente utilizar el entorno propuesto, especialmente si no se tiene experiencia previa gestionando entornos Python.

---

---

## 🧩 Uso del repositorio durante el curso (importante)

Este repositorio es una **plantilla (template)** de la asignatura y **no se utiliza directamente para trabajar en las prácticas**.

Cada estudiante deberá:

1. **Usar esta plantilla** para crear una copia en su cuenta (botón **Use this template** en GitHub)
2. **Configurar el nuevo repositorio como privado**
3. Trabajar siempre sobre **su propio repositorio**
4. Crear su **Codespace asociado a ese repositorio personal**

👉 Esto permite que cada estudiante tenga:
- su propio espacio de trabajo
- su propio historial
- independencia total respecto a otros compañeros

---

### 🔐 Repositorio propio y privacidad

El repositorio creado a partir de la plantilla debe ser **privado**, para evitar:
- plagios involuntarios
- compartir soluciones sin querer
- accesos no deseados

El profesor **no necesita acceso** a tu repositorio personal.

---

### 🔄 Sincronizar el Codespace con tu repositorio (muy importante)

Es **fundamental** que sincronices tu Codespace con tu repositorio privado con regularidad (commit y push). Así se garantiza la **permanencia** de todo lo que desarrollas en la nube.

Si no sincronizas, el trabajo que hagas en el Codespace podría perderse si el espacio se elimina o expira.

> **Regla de oro:** haz commit y push de tus cambios para que queden guardados en tu repositorio.

---

### 📅 ¿Cuándo se hará esto?

El proceso de:
- crear la copia desde la plantilla,
- configurar el repositorio como privado,
- y crear el Codespace asociado,

se explicará **paso a paso en el primer taller**.

Por ahora, es suficiente con saber que:
> **Para trabajar en las prácticas cada estudiante tendrá su propio repositorio (privado) y su propio Codespace, y debe sincronizar el Codespace con el repositorio para no perder el trabajo.**

---

## 🧠 Idea clave (muy importante)

> **Con GitHub Codespaces el código se ejecuta en la nube, no en tu ordenador.**

Aunque utilices VS Code instalado en tu equipo, los archivos y el Python que se usan  
**están en GitHub Codespaces**.

---

## 🚀 Cómo empezar

Una vez tengas **tu copia** del repositorio (creada desde la plantilla y configurada como privada), puedes trabajar con GitHub Codespaces de **dos formas equivalentes**.  
El entorno es el mismo; solo cambia el editor.

---

### Opción A — Usar Codespaces desde el navegador (más sencillo)

1. Entra en **tu repositorio** en GitHub
2. Pulsa el botón **Code**
3. Ve a la pestaña **Codespaces**
4. Pulsa **Create codespace**
5. Espera a que se abra el entorno (VS Code en el navegador)

No necesitas instalar nada.

---

### Opción B — Usar Codespaces con VS Code instalado (si ya lo usas y prefieres usar tu equipo)

Si ya usas Visual Studio Code en tu ordenador:

1. Instala **Visual Studio Code**
2. Instala la extensión **GitHub Codespaces**
3. Inicia sesión en GitHub desde VS Code
4. Abre tu repositorio y crea/abre el Codespace

El entorno es el mismo que en el navegador; solo cambia la comodidad del editor.

---

## 📓 Jupyter Notebooks

Las prácticas se realizan mediante **cuadernos Jupyter Notebook** (`.ipynb`).

- Abre el notebook correspondiente al taller
- Ejecuta las celdas normalmente
- El kernel de Python **ya está configurado**

Si VS Code te pide seleccionar kernel:
- elige el **Python que aparece por defecto**
- **no crees entornos virtuales**

---

## 💾 Guardar vs Commit vs Push (muy importante)

Hay varias acciones distintas:

### Guardar (`Ctrl + S`)
- Guarda el archivo en el Codespace
- **No lo guarda en GitHub**

### Commit + Push
- El commit registra los cambios; el push los envía a tu repositorio en GitHub
- Así el trabajo queda **definitivamente** en tu repositorio (en la nube)

> **Regla de oro**  
> Si haces commit y push, tu trabajo no se pierde y permanece en tu repositorio.

Los avisos de commit **no son errores**, solo recordatorios.

---

## 📁 ¿Dónde están mis archivos?

- Los archivos **no están en tu ordenador**
- Están en el Codespace (en la nube)
- El repositorio GitHub es el lugar donde se guardan definitivamente

Descargar un archivo crea solo una **copia local**, pero la versión oficial es la del repositorio.

---

## 🔒 Privacidad

- Cada estudiante trabaja en su **Codespace privado**
- Nadie más puede ver tu Codespace
- El profesor **no ve tu entorno de trabajo**
- Solo se comparte lo que tú subes al repositorio o entregas

---

## 📌 Organización del curso

- Este repositorio (como plantilla) proporciona el **entorno común de trabajo**
- Los cuadernos de cada taller se irán proporcionando progresivamente
- No es necesario conocer Git en profundidad para la asignatura

Al final de cada sesión de prácticas:
1. Guarda el notebook
2. Haz commit y push (sincroniza con tu repositorio)
3. Continúa la próxima sesión sin problemas

---

## 📤 Entrega de las prácticas

**La entrega no se realiza a través del repositorio del estudiante.**

Para cada taller debes:

1. **Descargar** el notebook que hayas completado desde tu Codespace o desde tu repositorio
2. **Subir** ese archivo a la tarea correspondiente en Moodle

Requisitos de la entrega:
- Siempre el **notebook completado** del taller
- **Nombre del fichero** exactamente como se indique (con tus datos de estudiante)
- Notebook **ejecutado por completo y sin errores** antes de descargarlo

---

## ❓ Si algo no funciona

Antes de pedir ayuda, comprueba:
- Que estás trabajando en un **Codespace**
- Que el kernel es el Python por defecto
- Que has guardado el notebook

Si el problema persiste, consúltalo en clase.

---

## ✅ Resumen final

- Usa la **plantilla** para crear tu repositorio privado (no hagas fork)
- No instales Python; no crees entornos virtuales
- Trabaja en GitHub Codespaces
- **Sincroniza** tu Codespace con tu repositorio (commit y push)
- **Entrega** cada taller descargando el notebook completado y subiéndolo a Moodle (nombre correcto, ejecutado sin errores)
- Céntrate en la asignatura

---

*Este entorno está pensado para ayudarte, no para complicarte la vida.*
