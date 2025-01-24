# Proyecto 8. Megaline: Smart o Ultra. 

## Descripción
La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.

Tenemos acceso a los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos. De este modo realizamos una comparativa de dos modelos: bosque aleatorio y regresión logística, para obtener la mayor exactitud posible, usando como umbral de exactitud:0.75

## Contenido del Notebook
- **Total de celdas:** 27
- **Celdas de markdown:** 17
- **Celdas de código:** 10

### Procesos de análisis

1. **Carga de datos:**
   - Lectura de datos desde archivos fuente.
2. **Descripción de los datos:**
   - Método info para obtener información general de los datos.
3. **Preprocesamiento de los datos:**
   - Segmentación de los datos en conjuntos de entrenamiento, validación y prueba.
4. **Análisis de los datos:**
   - Analisis de la calidad de los modelos con distintos hiperparámetros.
5. **Conclusiones:**
   - Resumen de los hallazgos y conclusiones del análisis.

## Requisitos del sistema

Para ejecutar este notebook, necesitarás:
- Python 3.8 o superior
- Dependencias listadas en `requirements.txt`

## Ejecución
1. Clona este repositorio:
   ```bash
   git clone <URL-del-repositorio>
   ```

2. Cambia al directorio del proyecto:
   ```bash
   cd <nombre-del-directorio>
   ```

3. Abre y ejecuta el notebook:
   ```bash
   jupyter notebook proyecto_8.ipynb
   ```

## Contribuciones
Si deseas contribuir:
1. Realiza un fork del repositorio.
2. Crea una rama para tus cambios:
   ```bash
   git checkout -b mejora-analisis
   ```
3. Envía un pull request explicando tus cambios.

## Licencia
Consulta el archivo `LICENSE` para más información sobre el uso y distribución de este proyecto.
