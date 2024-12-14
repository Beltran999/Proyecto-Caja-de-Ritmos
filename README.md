# Proyecto Caja de Ritmos 🎵

Un proyecto de ingeniería electrónica desarrollado como parte de la asignatura de **Procesadores Integrados**. Este proyecto consiste en el diseño e implementación de una caja de ritmos basada en microcontroladores, que permite reproducir sonidos musicales con diferentes configuraciones y funcionalidades adicionales.

## Contenido 📂

- [Descripción](#descripción)
- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Autores](#autores)
- [Licencia](#licencia)

## Descripción 📝

El proyecto **Caja de Ritmos** es una herramienta que combina hardware y software para:
- Reproducir patrones de ritmos predefinidos.
- Permitir al usuario configurar velocidades, volumen y bucles.
- Controlar las funciones mediante botones y una interfaz gráfica OLED.
- Implementar conectividad Bluetooth para interacciones remotas.

Este proyecto utiliza tecnologías como:
- **Microcontroladores Arduino**.
- **Bibliotecas de audio** para reproducción de archivos WAV.
- **Interfaz gráfica OLED** para visualizar la información en tiempo real.
- **Bluetooth Low Energy (BLE)** para comunicación inalámbrica.

## Características ✨

- Reproducción de hasta 6 sonidos con 3 velocidades diferentes (50%, 100%, 200%).
- Control de volumen y velocidad mediante potenciómetros.
- Interfaz gráfica para mostrar información del sistema.
- Conectividad Bluetooth para configuraciones remotas.
- Visualización del circuito mediante herramientas como TinkerCAD, Fritzing o Wokwi.

## Requisitos ⚙️

- **Hardware**:
  - Microcontrolador compatible con Arduino.
  - Pantalla OLED.
  - Tarjeta SD y lector SD.
  - Módulo Bluetooth BLE.
  - Circuito amplificador de audio y parlantes.
  - Potenciómetros y botones.

- **Software**:
  - [Arduino IDE](https://www.arduino.cc/en/software)
  - Librerías utilizadas: `SD`, `SPI`, `U8g2lib`, `AudioFileSourceSD`, `AudioGeneratorWAV`, `AudioOutputI2S`, entre otras.

## Instalación 🛠️

1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tuusuario/caja-de-ritmos.git
   cd caja-de-ritmos
