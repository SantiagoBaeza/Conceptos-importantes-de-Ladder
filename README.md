[⬅️ Volver a "Proyectos con PLC/HMI/SCADA"](https://github.com/SantiagoBaeza/Recopilacion-proyectos-PLC-HMI-SCADA)

# Conceptos importantes de Ladder

Este repositorio reúne conceptos importantes de programación en PLC. Cada apunte está documentado y alojado en su propio repositorio individual, ilustran buenas prácticas y simulaciones de errores comunes.

---

## 📗 Índice de conceptos

### 00. Enclavamiento de motor (simulacion).
- 📅 Fecha: Diciembre 2025
- 🔗 [Ver repositorio](https://github.com/SantiagoBaeza/Enclavamiento-de-motor-simulacion-)
- 🛠️ Tecnologías: PLC Siemens 1200, software TIA Portal V16, Memorias virtuales.
- 📄 Descripción: Sistema que permite mantener un motor encedido aunque el boton de inicio deje de presionarse.

### 01. Repetición de señales en PLC (simulación de error)
- 📅 Fecha: Diciembre 2025
- 🔗 [Ver repositorio](https://github.com/SantiagoBaeza/Repeticion-de-se-ales-en-PLC/tree/main)
- 🛠️ Tecnologías: PLC Siemens S7-1200, software TIA Portal V16, Memorias virtuales
- 📄 Descripción: - Simulación que demuestra por qué no se deben repetir bobinas de salida en distintos segmentos. Aunque el primer segmento muestra que `motor3` se enciende, el segundo revela que no recibe energía, evidenciando el error. Este tipo de fallas puede pasar desapercibido y generar mala práctica profesional.

### 02. Uso de funciones SET y RESET en PLC

- 📅 Fecha: Enero 2026  
- 🔗 [Ver repositorio](https://github.com/SantiagoBaeza/Uso-de-funciones-SET-y-RESET-en-PLC/tree/main)  
- 🛠️ Tecnologías: Siemens S7-1200 / TIA Portal / Ladder (LAD)  
- 📄 Descripción: Este proyecto muestra cómo utilizar las funciones SET y RESET en programación de PLCs para controlar salidas de forma más intuitiva.  
  A partir del ejercicio anterior sobre repetición de bobinas, se implementa una lógica de enclavamiento usando bobinas de tipo SET y RESET, junto con botones de inicio y parada.  
  Las capturas documentan el comportamiento del motor en cada etapa de la simulación, y el archivo del proyecto está disponible para abrirlo directamente en TIA Portal.

### 03. Uso de flancos positivos y negativos en PLC

- 📅 Fecha: Enero 2026  
- 🔗 [Ver repositorio](https://github.com/SantiagoBaeza/Uso-de-flancos-positivos-y-negativos-en-PLC/tree/main)  
- 🛠️ Tecnologías: Siemens S7-1200 / TIA Portal / Ladder (LAD)  
- 📄 Descripción: Este proyecto muestra cómo utilizar los flancos positivos y negativos en programación de PLCs para detectar eventos puntuales y controlar salidas de forma más precisa.  
A partir del ejercicio anterior sobre enclavamiento con SET y RESET, se incorpora el uso de flancos para activar motores en el instante exacto en que se presiona un botón, evitando repeticiones en cada ciclo de scan.  
Las capturas documentan el comportamiento del motor en cada segmento del programa, y el archivo del proyecto está disponible para abrirlo directamente en TIA Portal.

### 04. Uso de temporizadores en PLC

- 📅 Fecha: Enero 2026  
- 🔗 [Ver repositorio](https://github.com/SantiagoBaeza/Uso-de-temporizadores-en-PLC/tree/main)  
- 🛠️ Tecnologías: Siemens S7-1200 / TIA Portal / Ladder (LAD)  
- 📄 Descripción: Este proyecto muestra cómo utilizar los temporizadores **TON, TOF, TP y TONR** en programación de PLCs para controlar salidas en función del tiempo.  
Se aplicaron distintos tipos de temporizadores a motores simulados, configurando un tiempo de preset de 15 segundos en cada caso.  
Las capturas documentan el comportamiento de cada temporizador y el archivo del proyecto está disponible para abrirlo directamente en TIA Portal.

05. Uso de contadores en PLC  
- 📅 Fecha: Enero 2026  
- 🔗 [Ver repositorio](https://github.com/SantiagoBaeza/Uso-de-contadores-en-PLC/tree/main)  
- 🛠️ Tecnologías: Siemens S7-1200 / TIA Portal / Ladder (LAD)  
- 📄 Descripción: Este proyecto documenta el uso de los contadores CTU, CTD y CTUD en programación de PLCs.  
Se aplicaron distintos tipos de contadores a motores simulados, configurando valores de preset (PV) y explorando el comportamiento de cada tipo: ascendente, descendente y bidireccional.  
Las capturas muestran la lógica de cada esquema y el archivo del proyecto está disponible para abrirlo directamente en TIA Portal.

### 06. ... 
- 📅 Fecha: ...
- 🔗 [en construccion](pegar_enlace)
- 🛠️ Tecnologías: ...
- 📄 Descripción: ...

---

## Objetivo
Este repositorio tiene como propósito reunir conceptos fundamentales de programación en PLC con TIA Portal. La meta es ofrecer un espacio que documente ejercicios, simulaciones y buenas prácticas de Ladder, de manera que sirva como referencia de aprendizaje.

---

> 🧩 Estos espacios estan en construcción y se actualizan de forma frecuente.
