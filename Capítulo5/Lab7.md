# Práctica 8. Estimación con puntos de historia (_Planning Poker_)

## Objetivos
Al finalizar la práctica, serás capaz de:
- Estimar el esfuerzo relativo de historias de usuario utilizando la técnica de _Planning Poker_.
- Aplicar el concepto de tamaño relativo (complejidad, incertidumbre, esfuerzo) en lugar de tiempo.
- Colaborar con un equipo para alcanzar un consenso en las estimaciones.

## Duración aproximada:
-   50 minutos.
Nota: Grupo Completo

## Requerimientos
Utilizar la herramienta de https://planningpokeronline.com.
No se necesita cuenta.

## Instrucciones

El objetivo de esta práctica es estimar de forma colaborativa el "tamaño" de las Historias de Usuario que crearon en la práctica anterior. No estimaremos en horas o días, sino en **Puntos de Historia**, que representan una medida relativa del esfuerzo total.

### Procedimiento a Seguir

Paso 1. Entender el Concepto de Puntos de Historia.
-   Recordar que los Puntos de Historia no son unidades de tiempo. Representan una combinación de:
    -   Complejidad: ¿Qué tan difícil es de entender y resolver?
    -   Incertidumbre: ¿Qué tanto desconocemos sobre lo que hay que hacer?
    -   Esfuerzo: ¿Cuánto trabajo implica (diseñar, codificar, probar)?

Paso 2. Ingresar a la plataforma de: https://planningpokeronline.com/.

Paso 3. Seleccionar el botón de Start Game.

<img width="616" height="415" alt="image" src="https://github.com/user-attachments/assets/106424da-b8d4-4b45-8942-bf875645e11f" />

Paso 4. Planificar la sesión de juego.
-   Colocar un nombre para la sesión.
-   Utilizar la secuencia de Fibonacci modificada (0, 1, 2, 3, 5, 8, 13, 20...) para las estimaciones. Los saltos grandes nos obligan a agrupar las tareas por tamaño relativo en lugar de ser demasiado precisos.
-   Seleccionar "Create Game".

<img width="869" height="555" alt="image" src="https://github.com/user-attachments/assets/6f5a5b13-78cb-4167-9ba2-b78853106ce7" />

Paso 5. Establecer una Línea Base.
-   Seleccionar una de las Historias de Usuario más pequeñas y sencillas del backlog.
-   Acordar como equipo asignarle un valor de referencia bajo, por ejemplo, **2 puntos**. A partir de ahora, todas las demás historias se estimarán en comparación con esta: "¿Es esta nueva historia más grande, más pequeña o del mismo tamaño que nuestra historia de 2 puntos?".

Paso 6. Ejecutar el Ciclo de Estimación (Planning Poker).
-   Presentar la primera Historia de Usuario a estimar. El Product Owner o el instructor la explicará y leerá sus Criterios de Aceptación.
-   Discutir y aclarar dudas. El equipo debe hacer preguntas para asegurarse de que todos entienden el alcance de la historia.
-   Votar en silencio y de forma individual, utilizando la herramienta de estimación. Cada miembro selecciona el número que cree que representa el tamaño de la historia en comparación con la línea base.
-   Revelar los votos al mismo tiempo.
-   Alcanza el consenso.
    -   Si todos votaron lo mismo, ¡excelente! Ese es el valor de la historia. Pasen a la siguiente.
    -   Si hay diferencias, las personas que votaron el número más alto y el más bajo deben **explicar su razonamiento**. Esta discusión es la parte más valiosa del proceso, ya que saca a la luz suposiciones y riesgos ocultos.
    -   Repetir la votación hasta que el equipo alcance un consenso o una estimación muy cercana.

Paso 7. Repetir el Proceso.
-   Continuar con el ciclo de "Presentar -> Discutir -> Votar -> Consensuar" para el resto de las Historias de Usuario.

Paso 8. Colocación en Jira
-   Dentro de Jira selecciona el guión de la historia de usuario que hayas calificado en el backlog para modificar su valor
<img width="1281" height="95" alt="image" src="https://github.com/user-attachments/assets/f997716e-23d0-4635-990e-b21924428a5d" />

-   También lo puedes hacer seleccionando la historia y buscando la opción "Story points"
<img width="761" height="636" alt="image" src="https://github.com/user-attachments/assets/62d58a7f-a62b-4635-b028-cc03ad1d495c" />

### Resultado Esperado
Al finalizar, el equipo tendrá un conjunto de Historias de Usuario del backlog con una estimación de esfuerzo en puntos acordada por consenso. Más importante aún, el equipo tendrá una **comprensión compartida y profunda** del trabajo que implica cada historia, gracias a las discusiones durante el proceso de estimación.

**Ejemplo del producto final en Jira (o cualquier otra herramienta):**
-   HU 1.1: Crear cuenta con email/redes sociales - **8 puntos**
-   HU 1.2: Recuperar contraseña - **5 puntos**
-   HU 3.2: Mostrar tiempo estimado de entrega - **8 puntos**

<img width="1279" height="235" alt="image" src="https://github.com/user-attachments/assets/93b4e589-f8ee-4698-9692-c528ca95779d" />

