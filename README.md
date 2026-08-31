# Sistema Sanitario COVID-19

Este proyecto es parte del Trabajo Práctico Integrador de la materia **Sistemas y Organizaciones**. Consiste en la aplicación práctica de la metodología de **Análisis Estructurado de Sistemas**, modelando los procesos de negocio de un Comité de Emergencia Sanitaria provincial durante la pandemia de COVID-19.

## Objetivo y Descripción del Sistema

El sistema documentado modela el flujo de información y las reglas de negocio necesarias para gestionar las excepciones comerciales al *aislamiento social, preventivo y obligatorio* dictado por el Estado. 
El Comité de Emergencia Sanitaria es responsable de registrar solicitudes de empresas, otorgar carnets habilitantes, fiscalizar el cumplimiento de los protocolos de seguridad sanitaria y sancionar los incumplimientos. 
El proyecto abstrae toda esta realidad administrativa en un conjunto de diagramas y diccionarios estandarizados.

## Estructura del Análisis Estructurado

El análisis se documentó utilizando diagramas de flujo de datos (DFD) en distintos niveles de profundidad, acompañados por sus especificaciones textuales correspondientes:

### 1. Diagrama de Contexto (Nivel 0)
Define los límites del sistema y su interacción con las entidades externas u origen/destino de los datos. Se identificaron las siguientes entidades externas:
*   **Empresas / Comercios**: Solicitan excepciones y envían declaraciones juradas.
*   **Policía**: Verifica permisos y emite consultas de tránsito.
*   **A.R.T. (Aseguradora de Riesgo de Trabajo)**: Recibe actualizaciones de pólizas de empresas exceptuadas.
*   **Dirección de Comercio**: Emite carnets y protocolos.

### 2. Diagrama de Subsistemas (Nivel 1)
Descompone el sistema principal en grandes áreas funcionales o subsistemas, permitiendo entender la arquitectura macro de los procesos internos. Ejemplos de procesos en este nivel incluyen la gestión de solicitudes, la evaluación y habilitación, el control sanitario y la gestión de penalizaciones.

### 3. Diagrama de Funciones (Nivel 2)
Desglosa cada subsistema del Nivel 1 en funciones más detalladas, mostrando flujos de datos intermedios y almacenes de datos internos (como listas de espera y registros históricos de infractores).

### 4. Diccionario de Datos
Proporciona una definición exhaustiva y estructurada de cada componente del sistema, incluyendo:
*   Composición de los flujos de datos (ej. qué campos tiene el formulario de solicitud o el carnet habilitante).
*   Estructura de los almacenes de datos.

### 5. Especificación de Procesos (Procesos Primitivos)
Detalla la lógica interna de los procesos de nivel más bajo (procesos que ya no se subdividen) utilizando herramientas como pseudocódigo, árboles o tablas de decisión, explicando *cómo* los datos de entrada se transforman en datos de salida.

## Conclusión y Aprendizaje
Este trabajo práctico permitió afianzar las bases del pensamiento sistémico, la capacidad de abstraer flujos complejos de información a partir de narrativas narrativas textuales, y la habilidad de estandarizar la documentación siguiendo los principios del Análisis Estructurado de Yourdon/DeMarco.
