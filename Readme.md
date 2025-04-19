# Sistema de Comunicación IoT Industrial

## Descripción

Este repositorio contiene la Especificación de Requisitos de Software (SRS) para el firmware de un sistema de comunicación inalámbrica en un entorno industrial IoT. El sistema está diseñado para conectar sensores remotos en una planta de manufactura con un servidor central para monitoreo y análisis en tiempo real.

## Propósito del Proyecto

Desarrollar un firmware robusto para microcontroladores ARM de bajo consumo que permita:

- Adquisición y procesamiento de datos desde múltiples tipos de sensores
- Transmisión segura mediante protocolo MQTT
- Operación fiable en entornos con interferencia electromagnética
- Optimización del consumo energético para prolongar la vida útil de las baterías

## Requisitos Principales

### Requisitos Funcionales

- **Adquisición de Datos**: Muestreo configurable de múltiples tipos de sensores
- **Procesamiento de Datos**: Conversión, calibración y compresión de datos
- **Implementación MQTT**: Comunicación bidireccional con el servidor central
- **Cifrado de Datos**: Mecanismos de seguridad para proteger la información
- **Gestión de Energía**: Alternancia entre modos de bajo consumo y activo
- **Actualización Remota**: Capacidad de actualizar el firmware de forma segura
- **Diagnóstico y Registro**: Monitoreo del estado del sistema y registro de eventos

### Requisitos No Funcionales

- **Rendimiento**: Latencia máxima de 500 ms, 10 mensajes/segundo
- **Confiabilidad**: Disponibilidad del 99.9%
- **Seguridad**: Cifrado AES-128 o superior
- **Eficiencia Energética**: Vida útil de batería de al menos 6 meses
- **Escalabilidad**: Soporte para hasta 10 sensores por nodo
- **Resistencia a Interferencias**: Operación en entornos industriales hostiles
