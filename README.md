# traficoMapa 
 Son varios componentes listos para conectar entre sí, map-component y traffic incident(el cual hace uso de traffic-incident-data)
 El ejemplo de conexion se encuentrta en el fichero interconexion, el cual es un web component en el que se conecta los componentes con los atributos necesarios


## Ramas

El escenario normal se encuentra en la rama master, sin embargo, hay otras ramas en las que se modifican los ficheros según unas métricas de calidad para hacer estos escenarios "peores".

### versIntercon
Rama en la que se disminuye el número de conexiones entre los componentes. Esto significa que será un escenario pero ya que habrá menor comunicación entre componentes y por tanto una menor personalización.

### versRam
Escenario con una mayor utilización de recursos. Nieva, para provocar bajada de FPSs, además de que se aumenta la memoria que usa.
