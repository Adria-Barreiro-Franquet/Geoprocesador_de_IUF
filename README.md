# GEOPROCESADOR DE INTERFAZ URBANO-FORESTAL

Plugin de QGIS para el mapeo y análisis de la Interfaz Urbano-Forestal de una region determinada. Integra múltiples metodologías científicas para la gestión del riesgo de incendios.

---

## DESCRIPCIÓN
Este plugin permite automatizar el cálculo de las zonas IUF cruzando geodatos de edificaciones (de cualquier origen) con la capa de usos del suelo del SIOSE AR 2017.
Está diseñado para manejar grandes volúmenes de datos espaciales mediante procesos optimizados.

## METODOLOGÍAS DE MAPEADO
El plugin propone tres enfoques distintos para la obtención de resultados:

1.  **Método Alcasena**
2.  **Método Lampin-Maillet**
3.  **ABF** (metodo propio que combina lo mejor de los anteriores)

## DATOS NECESARIOS (INPUTS)
Para que el plugin funcione correctamente, se requieren las siguientes capas en formato vectorial:
* **Edificaciones**: Polígonos de todo aquello que se tenga en cuenta como edificación.
* **Uso del suelo**: Clasificación de usos del suelo según los estándares del SIOSE AR 2017. *(Es necesario contar con un equipo de más del doble del peso de esta capa en capacidad de RAM)*

## INSTALACIÓN
1.  Descargar y descomprimir el .zip del proyecto.
2.  Copiar la carpeta del plugin en la ruta de plugins de QGIS:
    `C:\Users\TU_USUARIO\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins`
3.  Entrar en la carpeta del plugin y ejecutar `...\plugins\Geoprocesador_de_IUF\fragstats\fragstats version 4.2.681[x64] INSTALLER.exe`,
    esto instalará software indispensable para ejecutar el plugin, dejar todo por defecto.
4.  Abrir QGIS y activar el plugin desde el **Administrador de Complementos**.

---

*Más información en:* https://www.qgis.org/resources/hub/