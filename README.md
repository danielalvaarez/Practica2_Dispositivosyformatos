Controles configurados



| Acción       | Teclado          | Controlador USB arcade | Mando XInput |

|--------------|------------------|------------------------|--------------|

| blipper\_izqd | Flecha izquierda | Botón 1                | LB           |

| blipper\_dcha | Flecha derecha   | Botón 2                | RB           |

| lanzador     | Flecha arriba    | Botón 3                | A            |

| reiniciar    | R                | Botón 4                | Start        |



Los controles se han probado con teclado. Las asignaciones del controlador USB arcade y del mando XInput están configuradas, pero no se han podido probar.



&#x20;Configuración física



1. Bola

\- Escala de la esfera: 0,025 en los tres ejes.

\- Masa: 0,5 kg.

\- Amortiguación lineal: 0,01.

\- Amortiguación angular: 0.

\- Simulación física y gravedad activadas.

\- Detección continua de colisiones (CCD) activada.

\- Perfil de colisión: PhysicsActor.



2\. Material físico

\- Fricción: 0,05.

\- Fricción estática: 0.

\- Restitución: 0,75.



3\. Impulsos

\- Lanzador: vector frontal del componente Arrow multiplicado por -500, con Vel Change activado.

\- Bumpers: impulso de magnitud 100, con Vel Change activado, dirigido desde el elemento golpeado hacia la bola y proyectado sobre el plano del tablero.



Puntuación

\- Bumpers: 50 puntos.

\- Dianas: 25 puntos.

\- Gomas: 10 puntos.







&#x20;Mejoras implementadas



1. Puntuación en dianas y gomas, además de los bumpers.

2\. Valores de puntuación diferentes según el elemento golpeado.

3\. Cambio temporal del color del marcador al puntuar: lila en bumpers y azul en dianas y gomas, con regreso al blanco.

4\. Lógica de bonus de 100 puntos adicionales cada cinco golpes registrados en dianas. Esta mejora está pendiente de validación durante una partida.



\*\*Como ya escribí en un correo, utilicé mal GitHub al inicio y el historial de commits comienza con el proyecto ya avanzado. Siento las molestias.\*\*

