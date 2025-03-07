# Chess Game

Este es un juego de ajedrez implementado en HTML, CSS y JavaScript. El juego permite a dos jugadores mover piezas en un tablero de ajedrez interactivo, con un historial de movimientos que se actualiza en tiempo real.

## Características

- **Tablero de ajedrez interactivo**: El tablero se renderiza dinámicamente usando una cuadrícula CSS.
- **Movimientos válidos**: El juego valida los movimientos de cada pieza según las reglas del ajedrez.
- **Historial de movimientos**: Se muestra un historial de movimientos en tiempo real.
- **Promoción de peones**: Los peones se promocionan automáticamente a reina al llegar a la última fila.
- **Turnos alternados**: El juego alterna entre los turnos de las piezas blancas y negras.
- **Reinicio del juego**: El juego se puede reiniciar en cualquier momento.

## Cómo jugar

1. **Selecciona una pieza**: Haz clic en una pieza para seleccionarla. Las casillas válidas a las que puede moverse la pieza se resaltarán.
2. **Mueve la pieza**: Haz clic en una casilla válida para mover la pieza seleccionada.
3. **Historial de movimientos**: Los movimientos se registran en el panel de historial a la derecha del tablero.
4. **Promoción de peones**: Si un peón llega a la última fila, se promociona automáticamente a reina.
5. **Reiniciar el juego**: Para reiniciar el juego, recarga la página.

## Estructura del código

- **HTML**: Define la estructura del tablero y el panel de historial.
- **CSS**: Estiliza el tablero, las piezas y el panel de historial.
- **JavaScript**: Implementa la lógica del juego, incluyendo la validación de movimientos, el manejo de turnos y la promoción de peones.

### Funciones principales

- **`parseFEN(fen)`**: Convierte una cadena FEN en una matriz que representa el estado del tablero.
- **`renderBoard()`**: Dibuja el tablero en el DOM basado en el estado actual de la matriz `board`.
- **`getValidMoves(piece, x, y)`**: Calcula los movimientos válidos para una pieza específica.
- **`handleSquareClick(x, y)`**: Maneja los clics en las casillas del tablero, incluyendo la selección de piezas y la ejecución de movimientos.
- **`addMoveToHistory(fromX, fromY, toX, toY, piece)`**: Añade un movimiento al historial.

## Estilos

- **Tablero**: El tablero está diseñado con una cuadrícula CSS, con casillas claras y oscuras alternadas.
- **Piezas**: Las piezas se representan con caracteres Unicode.
- **Historial**: El panel de historial tiene un diseño simple con un fondo que combina con el tablero.

## Requisitos

- Navegador web moderno con soporte para JavaScript y CSS Grid.

## Instalación

No se requiere instalación. Simplemente abre el archivo `index.html` en tu navegador para comenzar a jugar.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacer un fork y enviar un pull request con tus mejoras.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

¡Diviértete jugando al ajedrez!