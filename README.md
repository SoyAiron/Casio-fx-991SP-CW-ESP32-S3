# Casio fx-991SP CW + ESP32-S3

# Casio fx-991SP CW

Este es un proyecto que he decidido hacer en mis tiempos libres de 2º Bachillerato.
Consistira en modificar una Casio fx-991SP CW para quedarnos con la carcasa y darle mas potencia mediante un ESP32-S3, tendra una mejor pantalla, calculo avanzado y conectividad wifi.

Esta pensado para ser **100% reversible**. La placa original de Casio se conserva intacta y la carcasa exterior de plástico no sufre ningún corte, agujero ni modificación destructiva.

## Arquitectura de Hardware
* **Microcontrolador:** ESP32-S3-MINI-1 (Wi-Fi, Dual Core).
* **Pantalla:** OLED 2.08" Monocromática.
* **Alimentación:** Batería LiPo 3.7V con gestor de carga TP4054 y LDO ME6211.
* **PCB:** Diseño personalizado (KiCad) con contactos de membrana en oro inmerso (ENIG).

## Estructura del Repositorio
* `/Hardware`: Archivos de diseño electrónico y PCB desarrollados en KiCad 8.
* `/Firmware`: Código fuente en C++ estructurado para PlatformIO.
* `/Docs`: Datasheets, fotografías del proceso y documentación técnica.

## Licencia
Este proyecto se distribuye bajo la licencia **Creative Commons Reconocimiento-NoComercial 4.0 (CC BY-NC 4.0)**. Eres libre de estudiar, copiar y modificar el diseño para fines educativos o personales. El uso comercial o la venta de este dispositivo requiere autorización expresa del autor.