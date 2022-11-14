# ENUNCIADO

Para este ejercicio replicaremos las bases de una plataforma de distribución de viedojuegos. Teniendo asi por un lado los vieojuegos con sus atributos, el sistema que tendra en el todos los videgojuegos y una barra de busqueda que nos permitira realizar ciertas consultas.

No es neceserio alarmarse, puesto que solo llevaremos a cabo una sintesis abstracta de estos conceptos, siendo asi que las funcionalidades de la barra de busqueda serán aplicadas como métodos del propio sistema.

# DIAGRAMA

![Diagrama](https://github.com/santiagosimonsantos/Taller-introductorio-a-la-Programacion-Orientada-a-Objetos-con-Java/blob/main/Diagrama.svg)

# ROADMAP TIENDA DE VIDEOJUEGOS

## ROADMAP VIDEOJUEGO

### Atributos

- [ ]  Nombre, String.
- [ ]  Listado de generos, ArrayList\<String\>.
- [ ]  Número de jugadores, Integer.
- [ ]  Precio, Double.

### Metodos

- [ ]  Devolver el nombre del juego, → String.
- [ ]  Cambiar el nombre del juego,  (String).
- [ ]  Conseguir el listado de generos a los que pertenece, → ArrayList\<String\>.
- [ ]  Añadir o remover generos del listado, (String) / (ArrayList\<String\>).
- [ ]  Conseguir el numero de jugadores, → Integer.
- [ ]  Cambiar el numero de jugadores, (Integer).
- [ ]  Conseguir el precio, → Double.
- [ ]  Cambiar el precio, (Double).

## ROADMAP TIENDA

### Atributos

- [ ]  Lista de juegos, ArrayList\<String\>.

### Metodos

- [ ]  Añadir o remover juegos, (String) / (ArrayList\<String\>).
- [ ]  Conseguir un objeto juego por su nombre, (String) → (Videojuego).
- [ ]  Conseguir un listado de juegos por medio de uno o mas generos, (String) / (ArrayList\<String\>) → (ArrayList\<Videojuego\>).
- [ ]  Devolver una lista ordenada de los juegos basándonos en el numero
de jugadores activos, → ArrayList\<Videojuego\>.
- [ ]  Conseguir los juegos que estén entre dos valores dados de precios, (Double, Double) → (ArrayList\<Videojuego\>).
