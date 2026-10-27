# Modelización de las clases del Ajedrez

# Juego

## Atributos

- \- tablero: Tablero
- \- turno: Color
- \- estado: Estado

## Métodos

- \+ inicializar()
- \+ jugada(Movimiento)
- \+ dameTablero()
- \+ dameTurno()
- \+ dameEstado()
- \- cambiaTurno()
- \- mover(Movimiento)

# Partida

# Jugador (Oponente, Adversario)

# Tablero

## Atributos

- \- piezas[8,8]: Escaque

## Métodos

- \+ damePieza(Posición): Pieza
- \+ ponPieza(Posición, Pieza)
- \+ quitaPieza(Posición)
- \+ hayPieza(Posición): bool
- \+ hayPiezasEntre(Movimiento): bool
- \+ mover(Posición inicial, Posición final)
- \+ mover(Movimiento)
- \+ clonar()
- \+ \<\<clase>> colorEscaque(Posición): Color

# Escaque (Casilla)

## Atributos

- \- pieza: Pieza

## Métodos

- \+ ponPieza(Pieza)
- \+ quitaPieza()

# Color (turno)

- Blanco
- Negro

# Pieza

## Atributos

- \- color: Color

## Métodos

- ctor(Color)
- \+ dameColor(): Color
- \+ mover(Movimiento, Tablero)
- \# esValido(Movimiento, Tablero)

# Rey -> Pieza

## Métodos

- \# esValido(Movimiento, Tablero)

# Reina (Dama) -> Pieza

## Métodos

- \# esValido(Movimiento, Tablero)

# Alfil -> Pieza

## Métodos

- \# esValido(Movimiento, Tablero)

# Caballo -> Pieza

## Métodos

- \# esValido(Movimiento, Tablero)

# Torre -> Pieza

## Métodos

- \# esValido(Movimiento, Tablero)

# Peon -> Pieza

## Evento

- Promocion

## Métodos

- \# esValido(Movimiento, Tablero)
- \+ mover(Movimiento, Tablero)
- \- inicia(Movimiento): bool
- \- avanza(Movimiento): bool
- \- puedeComer(Movimiento): bool

# Posición

## Atributos

- columna: char
- fila: char

## Métodos

- ctor(Char fila, Char columna)
- dameFila()
- dameColumna()
- igual(Posicion)

# Movimiento (Jugada)

## Atributos

- posicionInicial : Posicion
- posicionFinal : Posicion

## Métodos

- ctor(Cadena)
- damePosicionInicial() : Posicion
- damePosicionFinal() : Posicion
- esVertical(): bool
- esHorizontal(): bool
- esDiagonal(): bool
- saltoVertical(): entero
- saltoHorizontal(): entero
- deltaVertical(): entero
- deltaHorizontal(): entero

# -Enroque

# -Promoción

# Organizador

# Estado

# -Tablas

# -Tiempo

# -Jaque

# -Jaque mate


# JuegoException

