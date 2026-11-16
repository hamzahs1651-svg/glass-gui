# Glass HS (Fabric, Minecraft 1.21.11, client side, Mojang mappings)
Glass GUI colorways, glass scoreboard, world look, FOV and sky options. Open options in game with `/hs`.

Build: JDK 21+, `./gradlew build` -> `build/libs/glass-gui-1.0.0.jar`. Or push to GitHub; the Actions workflow builds it.
Put the jar in `mods` together with Fabric API.

Code lives in `src/client` (split source sets); resource packs in `src/main/resources/resourcepacks`.
If the game crashes on startup, remove the `"mixins"` block in `fabric.mod.json` (turns off only FOV + sky colour).
