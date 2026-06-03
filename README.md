# PracticeLobbyHelper
Tutorial, modo de usos y detalles tecnicos de PracticeLobbyHelper
=====================

Uso rapido:

1. Abri el cliente de League of Legends e inicia sesion.
2. Ejecuta PracticeLobbyHelper-v0.2.5-windows-x64.exe.
3. Selecciona tu rol: TOP, JG, MID, BOT o SUP.
4. Pulsa "Crear entrenamiento".
5. Elegi lado azul o rojo.
6. Inicia la partida manualmente desde el cliente.

El lobby default se llama "Entrenamiento Vs Bots".

Al crear el lobby, la app no agrega el bot de tu rol en tu equipo. Por ejemplo,
si elegis JG y lado rojo, no agrega el Xin Zhao del equipo B. Tambien actualiza
tu posicion en la sala custom usando el rol seleccionado en la app.

GUIA DE USO DEL PRESET:

La app crea el preset editable en:

%LOCALAPPDATA%\PracticeLobbyHelper\preset.json

Tambien podes abrirlo desde el boton "Abrir preset".

Para volver al preset inicial, usa "Resetear preset". La app pedira confirmacion
porque eso borra el preset actual.

El preset usa nombres faciles:

team: "A" o "B"
position: "top", "jungle", "mid", "adc", "support"
championName: "Darius", "Xin Zhao", etc.

No hace falta conocer championId ni teamId.

Para campeones con apostrofes o conectores podes escribirlos simple. Por ejemplo,
Kai'Sa tambien funciona como "Kaisa" o "kai sa"; Nunu y Willump tambien funciona
como "Nunu", "Nunu & Willump" o "Nunu and Willump".

Practice Lobby Helper is not endorsed by Riot Games and does not reflect the
views or opinions of Riot Games or anyone officially involved in producing or
managing Riot Games properties. Riot Games and all associated properties are
trademarks or registered trademarks of Riot Games, Inc.
