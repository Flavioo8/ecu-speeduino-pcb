# ecu-speeduino-pcb

PCB de una ECU (unidad de control de motor) basada en el proyecto de código abierto [Speeduino](https://github.com/speeduino/speeduino), diseñada en Proteus sobre un Arduino MEGA. La placa se fabricó y se probó en un motor Chevrolet 1.6L.

## Por qué la hice
Para afianzar cómo una ECU gestiona un motor (lectura de sensores, control de inyección y encendido) y entender la electrónica que hay detrás.

## Qué aprendí en 18 revisiones
No todo lo que se diseña se puede construir así de fácil:
- **Ancho de pistas:** ajustado a lo que permitía la máquina láser donde se fabricó la PCB.
- **Ruteo:** solo sirve el tipo de ruteo que realmente se puede fabricar.
- **Ubicación de componentes:** posicionar bien cada elemento cambia todo el diseño.

## Contenido
- `proteus/revisiones/`: revisiones 1 a 18.1 del esquema y la PCB (`revNN_` indica el orden).
- `proteus/esquematicos/` y `proteus/simulaciones/`: esquemáticos base y simulaciones del control de inyector y bobina.
- `gerber/`: archivos CADCAM de las versiones 14 y 18.1. `pcb-pdf/`: capas TOP, BOTTOM y SILK.
- `bom/`: lista de componentes reales. `docs/`: conexiones mínimas necesarias (pines).

El firmware no está incluido: la placa usa Speeduino sin modificaciones, disponible en su repositorio oficial.
