# Circuito de Inicio/Parada con Enclavamiento

Este documento describe el funcionamiento, la prueba y los requisitos de hardware de un circuito de inicio/parada con enclavamiento (latch) diseñado para activar/desactivar una carga.

## Cómo Funciona

El sistema se compone de dos secciones principales:

1.  **Circuito Combinacional:** Realiza operaciones lógicas basadas en las entradas actuales.
2.  **Circuito Secuencial:** Mantiene el estado y responde a las entradas y al reloj.

## Cómo Probar

Para verificar el funcionamiento del circuito:

1.  **Activación:** Presione el botón de inicio para cada solución del circuito y confirme que la carga se activa correctamente.
2.  **Desactivación:** Presione el botón de parada para cada solución del circuito y confirme que la carga se desactiva correctamente.

## Hardware Externo Necesario

Para realizar las pruebas, se requiere el siguiente hardware:

* **Botones de Pull-Down Set:** Conecte un circuito de botón de pull-down set a las entradas IN0-IN1 y IN6-IN7 para cada solución.
* **LEDs:** Conecte 5 circuitos LED a las salidas OUT0, OUT1-OUT3 y OUT7 para verificar:
    * La señal del reloj.
    * La solución del circuito secuencial.
    * La solución del circuito combinacional.
* **Osciloscopio:** Utilice un osciloscopio para verificar la señal del reloj.

---
