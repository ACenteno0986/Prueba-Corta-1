# Prueba Corta 1
Alejandro Centeno Chaves - 2017169579
Redes Gr 20

#### Un usuario de telefonía móvil se encuentra en un auto en movimiento a 30 kms por hora, el mismo cruza el límite de una celda y de pronto la llamada actual se detiene de forma repentina, asumiendo que todo el sistema se encuentra funcionando de forma adecuada, ¿Por qué razón la llamada se detiene?

Dentro de cada una de las celdas, se encuentran frecuencias disponibles para que los teléfonos móviles puedan transferir los diferentes datos. Las frecuencias utilizadas cambian entre celdas adyacentes, para evitar que estas se interfieran, por lo que cada vez que un teléfono celular sale de una celda, la estación base que lo administra coordina con las celdas adyacentes para que alguna lo tome y haga la asignación de frecuencias. Hay dos formas en las que se puede hacer, y la que puede generar un tiempo de espera es la llamada soft handoff, o transferencia suave de celdas, donde la nueva base adquiere el dispositivo antes de que la base anterior lo libere, proceso que tarda 0.3 segundos, muy poco para ser notado.

El otro proceso es el hard handoff, o transferencia dura de celda, donde la base actual libera el dispositivo antes de que la nueva base lo tome. En este caso, si no hay frecuencias disponibles en la nueva base, la llamada se cortará.
  
##### ¿Explique de forma concisa porqué la transmisión de ondas de baja frecuencia no es práctica en medios inalámbricos?

En términos de frecuencias, las más bajas son útiles para atravesar obstáculos, debido a que lo hacen con mayor facilidad, sin embargo, pierden potencia a medida que se alejan de la fuente, en una relación 1/r^2. Esto genera que se deban colocar transmisores y repetidores muy cercanos entre ellos para evitar que la señal se pierda antes de llegar a su destino. Adicional a esto, las ondas de mayor frecuencia pueden rebotar en las capas superiores de la atmosfera y seguir así la curvatura de la tierra, haciéndolas optimas para la transmisión de datos inalámbricos.

#### Ante una crisis como conflicto bélico o un desastre natural, que daña o afecta los canales de comunicación o infraestructura de un país, ¿Qué tipo de transmisión recomendaría a ese país para mantener comunicación con el resto del mundo? Explique.

Recomendaría el uso de comunicación satelital, que de hecho es una de las comunes en tiempos de conflicto o desastre natural, esto debido a que este tipo de comunicaciones no requieren de infraestructura muy compleja en tierra, por lo que las estaciones de transmisión se ven menos propensas a ser dañadas o tomadas, e incluso interferidas. Claramente, este tipo de tecnología pude verse afectadas por eventos climáticos, pero raramente estos eventos evitarían del todo el uso de la comunicación satelital por un largo periodo de tiempo.

#### Explique el concepto ancho de banda en telecomunicaciones.


#### Explique las diferencias entre conmutación de paquetes y conmutación de circuitos.

La conmutación de paquetes, o store and fordward, se basan en el almacenamiento de paquete en los enrutadores que manejan la información enviada desde un punto a otro, por lo que no es necesario establecer una ruta física directa antes de enviar la información, como si debe hacerse en el caso de la conmutación de circuitos. En este ultimo método, se establece una conexión o camino directo entre los circuitos de la red antes de enviar la información, mientras que, en la conmutación de paquetes, estos se almacenan en los enrutadores y se envían conforme se necesiten.