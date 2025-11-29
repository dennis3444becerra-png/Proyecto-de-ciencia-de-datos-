PROYECTO DE CIENCIA DE DATOS – ESTRUCTURA Y DESCRIPCIÓN

Este archivo README.txt explica la organización del proyecto, la estructura de carpetas
y las convenciones de nombres utilizadas para mantener un flujo de trabajo ordenado,
claro y reproducible.

1. ESTRUCTURA DE CARPETAS

data/
    Contiene todos los datos usados en el proyecto.
    • raw/: datos originales sin modificar.
    • processed/: datos limpios o transformados.
    • external/: fuentes de datos adicionales.

notebooks/
    Incluye los archivos .ipynb para el análisis exploratorio, limpieza, modelado y
    visualización. Cada notebook inicia con un número que indica el orden de trabajo.

scripts/
    Scripts en Python que automatizan tareas como limpieza, entrenamiento del modelo
    y generación de visualizaciones.

models/
    Almacena los modelos entrenados (.pkl) y sus evaluaciones.

reports/
    Contiene el informe final del proyecto y las figuras generadas.

docs/
    Archivos de documentación adicional, referencias y notas importantes.

config/
    Archivos de configuración como parámetros, claves, rutas o conexiones.

README.txt
    Archivo explicativo del proyecto.

2. CONVENCIÓN DE NOMBRES

• Archivos y carpetas en minúsculas.
• Las palabras se separan con guiones bajos.
• Los notebooks llevan un número inicial para indicar su orden.
• Los modelos se guardan con un nombre descriptivo y fecha.

3. USO GENERAL DEL PROYECTO

Para reproducir este proyecto:
1. Cargar los datos en la carpeta data/raw/.
2. Ejecutar los notebooks en el orden indicado.
3. Usar los scripts para automatizar limpieza y entrenamiento.
4. Revisar los modelos almacenados en models/.
5. Consultar reports/ para ver resultados y gráficos finales.

Fin del archivo README.txt
