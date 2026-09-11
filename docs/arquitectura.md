# Arquitectura de la automatización

## Descripción general

La automatización fue desarrollada con Microsoft Power Automate Desktop (PAD) para procesar documentos PDF y realizar su carga y clasificación en un sistema institucional de gestión documental.

El flujo combina automatización de interfaz, procesamiento de archivos y lógica de control para reducir tareas repetitivas.

## Flujo general

```text
Selección de carpeta
        ↓
Identificación del tipo de autorización
        ↓
Identificación del programa académico
        ↓
Identificación del año
        ↓
Obtención de archivos PDF
        ↓
Filtrado de documentos ya procesados
        ↓
Inicialización del consecutivo
        ↓
Clasificación del documento
        ↓
Carga del PDF
        ↓
Registro de fecha
        ↓
Renombrado del archivo
        ↓
Nuevo documento
        ↓
Siguiente archivo
