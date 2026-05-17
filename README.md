# 🌐 Intranet AOD - Sistema Central (Comisión C)

Una Single Page Application (SPA) interactiva que simula la base de datos y el portal web interno de la **Fundación A.O.D. (Comisión C)[cite_start]**, perteneciente al universo del manga *"En Orden de Dianthus"*.

Basado en la obra original de Joirent "En Orden de Dianthus":
https://mangaplus-creators.jp/titles/iz2307020305433290024427833/

Este proyecto web está diseñado con una estética burocrática, militar y de sistema cerrado, simulando la herramienta que directores y coordinadores utilizan en su día a día para gestionar reclutas, monitorear misiones y leer reportes clasificados.

## 🚀 Características y Secciones

El portal cuenta con un sistema de navegación lateral integrado en JavaScript que permite alternar entre las siguientes vistas sin recargar la página:

* 📊 **Pizarra General:** Panel de control (Dashboard) que muestra el nivel de alerta actual del sistema, avisos generales y el estado del personal desplegado en misiones o campamentos de instrucción.
* 🔎 **Directorio de Personal:** Un buscador funcional integrado a una base de datos local (JSON). [cite_start]Permite buscar los expedientes operativos de unidades, coordinadores y reclutas (Inna [cite: 2443][cite_start], Niobi [cite: 2438][cite_start], Darina [cite: 2434][cite_start], Bertrand [cite: 2426][cite_start], Lan[cite: 2431], etc.) mediante Nombre o ID Numérico.
* ✉️ **Bandeja de Entrada:** Sistema de mensajería simulado para leer reportes internos confidenciales cruzados entre los directivos y coordinadores de la Comisión C (ej. Soith, Sofyan, Desant [cite: 2461]).
* [cite_start]⚠️ **Registro de Anomalías:** Base de datos con información clasificada sobre las amenazas activas o neutralizadas, como el *Esperpento de Faurán* y el *Espíritu del Sonido*[cite: 2406].

## 🛠️ Tecnologías Utilizadas

Este proyecto fue desarrollado desde cero sin el uso de frameworks externos, priorizando la ligereza y el control del DOM:
* **HTML5:** Estructura semántica de la aplicación.
* **CSS3:** Variables globales (`:root`), Flexbox, CSS Grid y animaciones personalizadas para lograr una estética "Dark Mode" de intranet militar.
* **Vanilla JavaScript:** Lógica de ruteo interno (pestañas), motor de búsqueda de arrays, y manipulación dinámica del DOM.

## ⚠️ Derechos de Autor y Uso de Contenido

Todo el contenido narrativo, los personajes, la estructura del universo (lore) y cualquier material directamente relacionado con la obra **"En Orden de Dianthus"** son creaciones 100% originales y de mi autoría.

El código de esta aplicación web se comparte a modo de demostración técnica y portfolio. Sin embargo, los derechos intelectuales sobre la historia, la Fundación AOD, las comisiones y los perfiles de los personajes están estrictamente reservados. 

Si deseas utilizar, distribuir, adaptar o incluir cualquier parte de este contenido narrativo o visual en otros proyectos, **por favor comunícate conmigo previamente para solicitar el permiso correspondiente**.
