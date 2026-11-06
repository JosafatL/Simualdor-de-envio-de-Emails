# 📧 Enviar Email

Formulario de envío de correos con validación en tiempo real, hecho con **HTML, CSS y JavaScript puro**.

> Este proyecto forma parte del curso **JavaScript Moderno**. Lo hice para practicar la **manipulación del DOM**, el manejo de eventos y la validación de formularios con JavaScript.

## ✨ Funcionalidades

- **Validación en tiempo real**: cada campo se revisa mientras el usuario escribe.
- **Mensajes de error dinámicos**: se crean e insertan alertas en el HTML cuando un campo está vacío o el email no es válido, y se eliminan al corregirlo.
- **Validación de email con expresión regular**.
- **Botón de envío inteligente**: permanece deshabilitado hasta que todos los campos sean válidos.
- **Spinner de carga** que simula el envío del correo.
- **Alerta de éxito** que aparece al enviar y desaparece después de unos segundos.
- **Botón de reset** que limpia el formulario y su estado.

## 🧠 Conceptos practicados

- Selección de elementos con `querySelector`
- Eventos con `addEventListener` (`DOMContentLoaded`, `input`, `submit`, `click`)
- Creación y eliminación de elementos con `createElement`, `appendChild` y `remove`
- Manejo de clases con `classList.add` y `classList.remove`
- Uso de un objeto para guardar el estado del formulario
- Validación con `trim()` y expresiones regulares
- `Object.values()` e `includes()` para comprobar campos vacíos
- Temporizadores con `setTimeout`
- `preventDefault()` para controlar el comportamiento del formulario

## 🛠️ Tecnologías

- HTML5
- CSS (estilos con clases de Tailwind CSS ya compiladas)
- JavaScript (Vanilla JS)

## 🚀 Cómo usarlo

1. Clona o descarga el repositorio.
2. Abre `index.html` en tu navegador.

No necesita instalación ni dependencias.

## 📌 Nota

El envío del correo es **simulado**: el proyecto no se conecta a ningún servidor ni envía emails reales. Su objetivo es practicar la lógica del lado del cliente y la interacción con el DOM.
