1. Microcontrolador ATmega328P
2. Pines analógicos
3. Pines de alimentación
4. Pines digitales
5. Puerto USB
6. Controlador USB
7. Conector de alimentación
8. Regulador de voltaje
9. Cristal de cuarzo
10. Botón RESET
11. GND / Tierra
12. VIN
13. LED integrado
14. RX/TX
15. AREF
## Cuadro comparativo

|             | Digital                            | Analógica      | PWM                           |
| ----------- | ---------------------------------- | -------------- | ----------------------------- |
| **Valores** | HIGH / LOW                         | Continuos      | HIGH / LOW variando el tiempo |
| **Arduino** | `digitalRead()` / `digitalWrite()` | `analogRead()` | `analogWrite()`               |
| **Uso**     | Botones, LED                       | Sensores       | Brillo, velocidad             |
