# Emulating-ECU-Sensor-Control-Unit
An Emulating ECU Sensor Control Unit with STM32F MCU

# Diagram
```
+----------------------+
|      Application     |
|  - Sensor Task       |
|  - Control Task      |
|  - Comm Task         |
+----------▲-----------+
           |
+----------|-----------+
|      RTOS Layer      |
|  - FreeRTOS          |
|  - Scheduler         |
+----------▲-----------+
           |
+----------|-----------+
|      Driver Layer    |
|  - GPIO              |
|  - UART              |
|  - ADC               |
|  - Timer             |
+----------▲-----------+
           |
+----------|-----------+
|      HAL / BSP       |
+----------------------+
```
