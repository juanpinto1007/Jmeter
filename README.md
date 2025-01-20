# Prueba de Carga con JMeter

Este proyecto contiene una prueba de carga realizada con Apache JMeter, simulando 1000 usuarios por segundo para evaluar el rendimiento de la API de https://reqres.in/. El objetivo es identificar posibles cuellos de botella y asegurar la escalabilidad del sistema.

## Requisitos Previos

Antes de ejecutar las pruebas, asegúrate de tener instalados los siguientes programas:

- **Apache JMeter**: Herramienta de código abierto para pruebas de carga y rendimiento.
- **Java 1.8 o superior**: Se requiere Java 1.8 para ejecutar JMeter.

## Archivos Incluidos

- **Prueba de Carga (`reqrest.jmx`)**: Archivo de configuración de JMeter que define los escenarios de prueba.
- **Script de Ejecución (`Script_ejecutado.txt`)**: Script en CMD para iniciar la prueba de carga.
- **Reporte de Resultados (`ReportesHTML`)**: Reporte generado por JMeter con los resultados de la prueba.

## Instalación

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/juanpinto1007/Jmeter.git
