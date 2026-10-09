# ¡Ahora Caigo! 3D — remake no oficial

> **Remake no oficial hecho por un fan, sin ánimo de lucro. ¡Ahora Caigo! es un formato de Antena 3 / Gestmusic. Sin relación oficial con el programa.**

Remake en 3D (Three.js) del minijuego de Scratch «¡Ahora Caigo!», jugable en el navegador (móvil y ordenador) y en Android.

▶ **Jugar online:** https://ikeriano.github.io/ahora-caigo-3d/

## Modos de juego

- **Minijuego** — la partida rápida, con las preguntas del juego original: duelos de 30 segundos, 2 comodines (PASA), monedas, palabra gallina en la ronda 5 y decisión final.
- **Entrenamiento** — practica una prueba suelta (duelo, palabra gallina, monedas o juego final) sin eliminación, viendo la respuesta correcta y con tiempo ilimitado opcional.
- **Programa completo** — camina por el plató hasta tu trampilla y juega el programa entero: presentador virtual, chistes malos, 8 oponentes, monedas, plantarse o **Juego Final** (10 preguntas en 2 minutos).
- **Especial Prime Time** — versión de gala del programa completo, con luces doradas y un premio final mayor.
- **Cabecera** — el Programa completo y el Especial Prime Time empiezan con una cabecera cinematográfica hecha con el motor del juego (unos 25 s, se salta tocando la pantalla). Si en el futuro existe `assets/intro.mp4`, primero se reproduce el vídeo y luego la cabecera. Se puede elegir con `?cabecera=ambas`, `?cabecera=video` o `?cabecera=motor`.
- **Historia del programa** — el presentador virtual repasa la historia del concurso en 12 capítulos mientras la cámara recorre el plató.
- **Temáticas** — Clásico, Halloween, Niños, Nochebuena, Navidad, Carnaval, Semana Santa, Verano y San Valentín, cada una con su decorado y sus preguntas.
- **Luces** — botón 💡 con una mesa de luces (cabezas móviles, LineBars, Washes y paneles LED), con colores, estados, CUEs, gobos, movimientos y velocidades.

## Controles

- **Móvil:** joystick en pantalla para caminar, arrastra para mirar y el teclado del móvil para escribir las respuestas.
- **Ordenador:** WASD o flechas para caminar, arrastra con el ratón para mirar y teclado físico para responder.

## Instalar en Android (APK)

Descarga los APK desde la página de [releases](https://github.com/ikeriano/ahora-caigo-3d/releases/latest):

- [AhoraCaigo3D.apk](https://github.com/ikeriano/ahora-caigo-3d/releases/latest/download/AhoraCaigo3D.apk) — el remake 3D.
- [AhoraCaigo-original.apk](https://github.com/ikeriano/ahora-caigo-3d/releases/latest/download/AhoraCaigo-original.apk) — el minijuego de Scratch original, tal cual.

Pasos:

1. Abre el enlace en el móvil y descarga el archivo `.apk`.
2. Ábrelo. Si Android lo pide, permite **«Instalar apps desconocidas»** para tu navegador o gestor de archivos (Ajustes → Aplicaciones → Acceso especial).
3. Pulsa **Instalar** y abre el juego. Funciona sin conexión y requiere Android 7.0 o superior.

Las APK están firmadas con un certificado de depuración (no se distribuyen por Google Play), así que Android puede mostrar un aviso. Es normal.

## Créditos

- Voz sintética: Piper TTS, voz `es_ES-davefx-medium`. Es una voz genérica que no imita a ninguna persona real.
- El presentador virtual es un personaje genérico y no representa a ninguna persona real.
- Motor 3D: [three.js](https://threejs.org/).
