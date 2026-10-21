HABITACION — DELTARUNE / UNDERTALE (Toriel's Monologue Scene)
====================================================================

COMO USARLO
-----------
1. Abre "index.html" en cualquier navegador moderno (Chrome, Firefox, Edge, Brave).
   - Puedes abrirlo directamente con doble clic en el archivo index.html,
     o servirlo con un servidor local simple:
        python -m http.server 8000
     y luego visitar: http://localhost:8000/index.html
2. Haz clic en la puerta monocromatica para entrar a la habitacion e iniciar el ambiente sonoro de lluvia y viento de fondo.
3. Mueve el cursor: el corazon SOUL rojo te sigue, manteniendose siempre visible.
4. Haz clic en CUALQUIER lugar de la habitacion para que empiece el texto:
   * (Toriel esta hablando del otro lado de la pared, en su habitacion.)
   * (Escuchar?)
     Si  ♥️No
5. Para elegir:
   - Usa las flechas [Izquierda/Derecha] o [Arriba/Abajo] en tu teclado, o mueve el raton / haz clic sobre "Si" o "No".
   - Al mover la seleccion se escucha el sonido "snd_squeak" de Undertale.
   - Presiona [Enter], [Espacio], [Z] o haz clic para confirmar tu eleccion.
6. Si eliges "No":
   * . . .
   (La caja de dialogo se cierra y el sonido de lluvia y viento continua).
7. Si eliges "Si":
   - El sonido de lluvia y viento se pausa inmediatamente.
   - Comienza a sonar la musica de fondo: "You Could Always Come Home" (Deltarune Chapter 7b OST).
   - Toriel empieza a hablar con su sonido caracteristico de voz (snd_txttor):
     * Desde el dia que se fueron...
     * Sabia que algo mal habia en el ambiente de ese dia.
     * Kris tan apagado, Asriel lucia extrano...
     ...
     * Podian haber venido a casa.
     * . . .
8. Puedes usar [Enter], [Espacio], [Z] o hacer clic con el raton para revelar instantaneamente cada linea o avanzar a la siguiente.

ESTRUCTURA DE ARCHIVOS
-----------------------
index.html                  -> Pagina completa con logica, escenas y caja de texto Undertale
assets/audio_data.js        -> Datos de audio base64 precargados para ejecucion instantanea y sin CORS
assets/door_mono.png        -> Puerta de entrada en tono monocromatico
assets/room_mono.png        -> Habitacion de Kris monocromatica y apagada
assets/heart.png            -> Alma roja (SOUL) de Undertale usada para el cursor y las opciones
assets/rain_wind.mp3        -> Sonido ambiente de lluvia y viento
assets/home_theme.mp3       -> "You Could Always Come Home" (https://www.youtube.com/watch?v=bagvuERU6mk)
assets/toriel_voice.wav     -> Sonido de texto de Toriel normalizado (snd_txttor)
assets/generic2_voice.wav   -> Sonido de texto generico normalizado (narrador de Undertale)
assets/snd_squeak.wav       -> Sonido de navegacion de opciones de Undertale (snd_squeak)
assets/8bitoperator_jve.ttf -> Fuente oficial de Undertale/Deltarune (8bitoperator JVE)
assets/determination_mono.ttf -> Fuente Determination Mono para respaldo tipografico pixel-perfect
