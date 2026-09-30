# 🗓️ Calendario Laboral

App web (PWA) 100% privada para gestionar turnos, vacaciones, ERTEs, notas y horas extra desde el móvil.

## ✨ Funciones Principales

* **Carga Automática:** Añade solos los festivos, Pascua y 3 semanas de agosto (empiezan el lunes de esa semana, o el siguiente si el día 1 es V, S o D).
* **Turnos A/B:** Cálculo rotativo automático de Mañanas (M) y Tardes (T).
* **Día de Cobro (Nuevo):** Calcula automáticamente el 5º día laborable de cada mes (saltando festivos y fines de semana) y lo marca con el símbolo **`€`**.
* **Notas Personalizadas (Nuevo):** Estado "Otros" para indicar el motivo exacto (bajas, permisos...). Deja una chincheta 📌 en el calendario que despliega un bocadillo de texto al tocarla.
* **Control de Horas Extra:** Opción de sumar horas por día (soporta escribir decimales con coma, ej. `2,5h`) con recuento automático.
* **Estados de Día:** ERTE (Total/Individual), Vacaciones, Día Personal, Sáb. Producción, Libre (Sáb) *(día de compensación por trabajar un sábado)*, Jornada Industrial, Curso y Otros.
* **Resúmenes Visuales:** Panel anual fijo arriba y mini-contadores bajo cada mes. Todos utilizan los mismos colores hexadecimales exactos que los días del calendario.
* **Interfaz Inteligente:** Auto-scroll automático al mes actual al abrir la app. Menú de edición inferior que permite marcar y editar múltiples días seguidos sin cerrarse.

## 🚀 Uso e Instalación

1. **Instalar:** Abre la web en el navegador del móvil y pulsa **"Añadir a la pantalla de inicio"**.
2. **Editar:** Toca **✏️ Activar Edición**, selecciona los días, elige el estado o las horas extra en el menú de abajo, y pulsa **💾 Guardar / Terminar Edición**. 
3. **Leer notas:** Fuera del modo edición, toca cualquier día que tenga una chincheta 📌 para ver la nota asignada.

## 🔒 Privacidad y Backups

Tus datos y notas se guardan solo en la memoria de tu móvil (`LocalStorage`). Abajo del todo tienes botones para **📥 Exportar** e **📤 Importar** una copia de seguridad completa (`.json`) si borras el historial o cambias de teléfono.
