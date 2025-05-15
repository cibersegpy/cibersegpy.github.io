# Estadísticas de Vulnerabilidades Shodan en Paraguay

Este repositorio contiene un análisis detallado de la exposición de dispositivos conectados a Internet en Paraguay, utilizando datos recolectados a través de la plataforma Shodan. El objetivo es visualizar y concientizar sobre el estado de la ciberseguridad en el país, identificando los principales riesgos, tecnologías y actores involucrados.

## ¿Qué es Shodan?
[Shodan](https://www.shodan.io/) es un motor de búsqueda que permite identificar dispositivos conectados a Internet (servidores, cámaras, routers, etc.) y recopilar información sobre sus servicios, vulnerabilidades y configuraciones.

## Contenido del Repositorio
- `index.html`: Visualización interactiva de las estadísticas principales extraídas de Shodan para Paraguay.

## Estadísticas Principales
El archivo `index.html` muestra:
- **Top 50 Proveedores de Internet (ISPs)**: Empresas con mayor cantidad de dispositivos expuestos.
- **Top 50 Ciudades**: Localidades con más dispositivos conectados.
- **Top 50 Vulnerabilidades**: CVEs más frecuentes en Paraguay.
- **Top 50 Productos**: Tecnologías y dispositivos más detectados (routers, cámaras, servidores, etc.).
- **Top 50 Sistemas Operativos**: SOs más comunes en dispositivos expuestos.
- **Top 50 Puertos**: Puertos más abiertos y potencialmente riesgosos.
- **Top 50 ASNs**: Sistemas autónomos con mayor actividad.
- **Top 50 Componentes HTTP y Categorías**: Frameworks, librerías y tecnologías web más usadas.
- **Top Versiones de SSL**: Protocolos de cifrado más implementados.
- **Dispositivos con Capturas de Pantalla**: Cantidad de dispositivos con screenshots públicas.

## ¿Cómo se generaron los datos?
Los datos fueron recolectados mediante consultas automatizadas a la API de Shodan y procesados para su visualización. El script de actualización (`update_shodan_stats.sh`) permite refrescar los datos periódicamente.

## Uso
1. Abre `index.html` en tu navegador para explorar las estadísticas.
2. Consulta los archivos CSV y JSON para análisis más detallados o procesamiento adicional.

## Contribuciones
Si tienes sugerencias, mejoras o deseas aportar nuevos análisis, ¡no dudes en abrir un issue o pull request!

## Licencia
Este proyecto se distribuye bajo la Licencia MIT.

---
**Última actualización de datos:** 15 de mayo de 2025
