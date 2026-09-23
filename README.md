# Práctica 8 — Avisos en vivo

Código de arranque de la Práctica 8 de TC2007B.

Es la app de Avisos tal como quedó al final de la Práctica 7: login, sesión
cifrada en el teléfono, refresh automático, el tablón con su rol y el sistema de
diseño. Todo funciona. Lo que le
falta es el tema de la práctica: hoy el tablón se consulta; al terminar, el
servidor te avisa — en vivo con la app abierta, y como notificación cuando no.

## Cómo empezar

1. Clona el repositorio y ábrelo en Android Studio.
2. Espera a que Gradle sincronice y corre la app: entra con tu cuenta (o crea
   una) y ve el tablón.
3. Abre https://startdroid.com/consola, entra, y toca *Escuchar /avisos/stream*.
   Es la Parte 0 de la guía, y va antes de escribir código.
4. Sigue la guía: https://startdroid.com/practicas/avisos-en-vivo.html

## Cómo trabajar

Haz un commit en cada checkpoint de la guía:

    git add -A ; git commit -m "checkpoint a3"

Si algo se rompe sin remedio, `git restore .` te regresa al último checkpoint bueno.

## Lo que nunca va en `src/main`

El disparador de pruebas del worker (`RevisarAhoraReceiver`) vive en `src/debug`.
Un APK de release no debe llevar botones de prueba.

## Uso de IA

Todo commit con código generado por IA debe declararlo con un trailer
`Co-Authored-By`. Ver la política completa en la guía.

## Entrega

Ver la rúbrica en la guía.
