# Laboratorio 2 - Interfaz LCD con ADC y UART

![Microcontrolador](https://img.shields.io/badge/Microcontrolador-ATmega328P-blue) 
![Display](https://img.shields.io/badge/Display-LCD_16x2-green) 
![Comunicación](https://img.shields.io/badge/Protocolo-UART-orange) 
![UVG](https://img.shields.io/badge/Universidad-UVG-red)

## Resumen General
Sistema integrado que muestra lecturas analógicas en LCD y permite control remoto vía UART, implementando:
- Lectura de 2 potenciómetros mediante ADC
- Visualización en pantalla LCD 16x2
- Comunicación serial bidireccional
- Control de contador desde terminal

## Características Principales

### 1. Subsistema de Visualización
- **Librería LCD personalizada** en modo 8 bits
- Formato de visualización:
- Sensor 1: 2.5V
- Sensor 2: 3.1V
- Contador: 15
