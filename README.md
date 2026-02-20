# Analisis de la encuesta

##  **Sección A: Evidencia de Campo (Discovery)**
##  **1. El Problema:**
### ¿Qué duele?
Dure 6 meses para poder sacar el pase de conducción, ya que los documentos se tardaban mucho en subirse al sistema.
### Frecuencia
Es un problema demasiado recurrente 5/5
### La solución soñada
Hacer un seguimiento del proceso vía online, para ver el estado de mi trámite

##  **Resultados de la sonda**
#### [***Link del formulario***](https://docs.google.com/forms/d/e/1FAIpQLScsHjQL3d5CyIZwEW8cEwgLdnkO9LLciflB7fSq5hKv8S6kNA/viewform?usp=header)
El gráfico muestra que la mayor dificultad percibida por los encuestados está en Trámites y burocracia (45,5%), lo que indica que casi la mitad siente que pierde más tiempo en filas, formularios manuales y procesos administrativos. Esto evidencia una fuerte necesidad de digitalización y simplificación de trámites
los resultados reflejan que los procesos administrativos tradicionales siguen siendo el mayor punto de fricción en la vida cotidiana de los participantes
##  **Sección B: Definición de Requisitos (Definition)**
##  **2. definición actual:**    
## ***Historia de usuario Principal***
**COMO** ciudadano que está realizando el trámite para obtener su pase de conducción, **QUIERO** poder hacer seguimiento en línea al estado de mi proceso y documentos, **PARA** saber en qué etapa se encuentra mi solicitud y evitar demoras e incertidumbre
## ***Criterios de aceptación***
1. El usuario puede ingresar con su número de documento o código de trámite
2. El sistema muestra claramente el estado actual del proceso (Ej: Documentos recibidos, En validación, Aprobado, Pendiente por corrección)
3. El usuario puede ver si falta algún documento
4. El sistema envía notificaciones (correo o SMS) cuando haya un cambio en el estado
5. La información se actualiza en tiempo real o con un máximo de 24 horas de desfase
## ***Requisitos Funcionales***
* RF01 – El sistema debe permitir al usuario consultar el estado actual de su trámite ingresando su número de documento o código de solicitud.
* RF02 – El sistema debe mostrar claramente las etapas del proceso (ej: Documentos recibidos, En validación, Aprobado, Rechazado, Pendiente de corrección).
* RF03 – El sistema debe enviar notificaciones automáticas por correo electrónico o SMS cuando el estado del trámite cambie.
* RF04 – El sistema debe permitir visualizar qué documentos han sido aprobados, rechazados o están pendientes.
* RF05 – El sistema debe almacenar y mostrar un historial de cambios de estado con fecha y hora.
* RF06 – El sistema debe requerir autenticación segura del usuario antes de permitir la consulta del trámite.