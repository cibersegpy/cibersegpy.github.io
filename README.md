# Estadísticas de Vulnerabilidades Shodan en Paraguay

Este repositorio contiene un análisis detallado de la exposición de dispositivos conectados a Internet en Paraguay, utilizando datos recolectados a través de la plataforma Shodan. El objetivo es visualizar y concientizar sobre el estado de la ciberseguridad en el país, identificando los principales riesgos, tecnologías y actores involucrados.

## ¿Qué es Shodan?
[Shodan](https://www.shodan.io/) es un motor de búsqueda que permite identificar dispositivos conectados a Internet (servidores, cámaras, routers, etc.) y recopilar información sobre sus servicios, vulnerabilidades y configuraciones.

## Contenido del Repositorio
- `index.html`: Visualización interactiva de las estadísticas principales extraídas de Shodan para Paraguay.

## Estadísticas Principales
El archivo `index.html` muestra:
- **Top 50 Vulnerabilidades**: CVEs más frecuentes en Paraguay.
- **Top 50 Proveedores de Internet (ISPs)**: Empresas con mayor cantidad de dispositivos expuestos.
- **Top 50 Ciudades**: Localidades con más dispositivos conectados.
- **Top 50 Productos**: Tecnologías y dispositivos más detectados (routers, cámaras, servidores, etc.).
- **Top 50 Sistemas Operativos**: SOs más comunes en dispositivos expuestos.
- **Top 50 Puertos Abiertos Detectados**: Puertos que se encuentran abiertos con mayor frecuencia. La exposición de puertos puede representar un riesgo si los servicios que los utilizan no están debidamente asegurados o son vulnerables.
- **Top 50 ASNs**: Sistemas autónomos con mayor actividad.
- **Top 50 Componentes HTTP y Categorías**: Frameworks, librerías y tecnologías web más usadas.
- **Versiones de SSL/TLS Detectadas y su Prevalencia**: Versiones de SSL/TLS y su frecuencia. El uso de versiones obsoletas representa un riesgo de seguridad.
- **Conteo de Dispositivos con Capturas de Pantalla**: Cantidad de dispositivos para los cuales Shodan tiene capturas de pantalla disponibles.

## ¿Cómo se generaron los datos?
Los datos fueron recolectados mediante consultas automatizadas a la API de Shodan y procesados para su visualización. El script de actualización (`update_shodan_stats.sh`) permite refrescar los datos periódicamente.

## Uso
1. Abre `index.html` en tu navegador para explorar las estadísticas.
2. Consulta los archivos CSV y JSON para análisis más detallados o procesamiento adicional.

## Contribuciones
Si tienes sugerencias, mejoras o deseas aportar nuevos análisis, ¡no dudes en abrir un issue o pull request!

## Licencia
Este proyecto se distribuye bajo la Licencia MIT.

## Créditos
- Autor: [@karl](https://x.com/karlbooklover)

---
**Última actualización de datos:** 15 de mayo de 2025
