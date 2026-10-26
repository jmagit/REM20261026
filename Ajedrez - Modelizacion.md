# Modelización de las clases del Ajedrez

# Juego

## Atributos

- \- tablero: Tablero
- turno: Color
- estado: Estado

## Métodos

- \+ inicializar()
- \+ jugada(Movimiento)
- \+ dameTablero()
- \+ dameTurno()
- \- cambiaTurno()
- \- mover(Movimiento)

# Partida

# Jugador (Oponente, Adversario)

# Tablero

## Atributos

- \- piezas[8,8]: Escaque

## Métodos

- \+ ponPieza(Posición, Pieza)
- \+ quitaPieza(Posición)
- \+ hayPieza(Posición, Pieza): bool
- \+ mover(Posición inicial, Posición final)
- \+ mover(Movimiento)

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

- \+ mover(Movimiento, Tablero)
- \+ esValido(Movimiento, Tablero)

# Rey -> Pieza

## Métodos

- \+ esValido(Movimiento, Tablero)

# Reina (Dama) -> Pieza

## Métodos

- \+ esValido(Movimiento, Tablero)

# Alfil -> Pieza

## Métodos

- \+ esValido(Movimiento, Tablero)

# Caballo -> Pieza

## Métodos

- \+ esValido(Movimiento, Tablero)

# Torre -> Pieza

## Métodos

- \+ esValido(Movimiento, Tablero)

# Peon -> Pieza

## Métodos

- \+ esValido(Movimiento, Tablero)
- \+ mover(Movimiento, Tablero)

# Posición

## Atributos

- columna: char
- fila: chas 

## Métodos

- 

# Movimiento (Jugada)

## Atributos

- posicionInicial : Posicion
- posicionFinal : Posicion

## Métodos

- esVertical
- esHorizontal
- esDiagonal
- deltaVertical
- deltaHorizontal

# -Enroque

# -Promoción

# Organizador

# Estado

# -Tablas

# -Tiempo

# -Jaque

# -Jaque mate
