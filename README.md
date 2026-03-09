# analysis_connectaTel
identificacion patrones de consumo, diseñar estrategias de retención y sugerir mejoras en los planes ofrecidos por la empresa.
Paso 1: Cargar y explorar:
En esta etapa, valido que los archivos se carguen correctamente, conocerás sus columnas y tipos de datos, y detectarás posibles inconsistencias.
Paso 2: Identificación de problemas de calidad de datos:
Detectar la presencia y magnitud de valores faltantes para evaluar si afectan el análisis o requieren imputación/eliminación.
Paso 3: Limpieza básica de datos
Aplicar reglas de limpieza para reemplazar valores sentinels y corregir fechas imposibles.
Paso 4: Summary statistics de uso por usuario:
Agrupación por comportamiento de uso
Paso 5: Visualización de distribuciones (uso y clientes) y outliers:
Entender visualmente cómo se comportan las variables clave tanto de uso como de clientes, observar si existen diferencias según el tipo de plan, y analizar la forma de la distribución.
Paso 6: Segmentación de Clientes:
Clasificar a cada usuario en un grupo de uso (Bajo uso, Uso medio, Alto uso) basándose en la cantidad de llamadas y mensajes registrados
Paso 7: Insight Ejecutivo para Stakeholders:
Análisis ejecutivo
⚠️ Problemas detectados en los datos

Se detectaron valores nulos en columnas del data set users y usage.
Se detectaron sentinels en columna age en data set users.
Se detectaron valores no validos en columna city de data set usage.
Se detectaron fechas imposibles en date set users.
🔍 Segmentos por Edad

El segmento Adulto concetra la mayor cocentración de usuarios
El grupo Adulto mayor representa un segmento relevante pero menor.
Los Adultos presentan la mayor cantidad de usuarios Premium.
📊 Segmentos por Nivel de Uso

Predomina el uso medio, que concentra la mayor cantidad de usuarios.
El bajo uso representa el segundo grupo en tamaño.
➡️ Esto sugiere que el producto o servicio tiene mayor afinidad con usuarios en etapa laboral activa. Ademas que existen portunidades para incrementar la frecuencia o intensidad de uso.

💡 Recomendaciones

El segmento adulto es el principal generador de volumen y valor, por lo que debe mantenerse como foco prioritario esto puede realizarse mediante la implementación campañas de upgrade de Básico a Premium, especialmente en usuarios adultos con uso medio o alto.
Los jóvenes representan una oportunidad de crecimiento a largo plazo si se logra incrementar su participación esto puede realizarse diseñando beneficios específicos o planes adaptados para aumentar adopción, tambien integrando funcionalidades más digitales o sociales.
