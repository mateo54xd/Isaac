# Guía: trabajar con Claude (nube) y Roblox Studio (Rojo)

Flujo: Claude (nube) -> GitHub -> tu PC (git pull) -> Rojo -> Roblox Studio

## Instalación (una sola vez)
1. Instala Git: https://git-scm.com/download/win
2. Instala GitHub Desktop (más fácil): https://desktop.github.com
   y clona el repositorio `mateo54xd/isaac`.
3. Instala Rojo: https://rojo.space/docs/v7/getting-started/installation/
   - Plugin de Studio: en Studio abre Toolbox > busca "Rojo" > instala el plugin
     (o instálalo con `rojo plugin install` si instalaste el programa).

## Cada vez que trabajes
1. En GitHub Desktop: elige la rama que te indique Claude y pulsa "Fetch / Pull".
2. En la carpeta del proyecto abre una terminal y ejecuta: `rojo serve`
3. En Roblox Studio: abre un lugar vacío, pestaña Plugins > Rojo > Connect.
4. Los scripts de `src/` aparecen en Studio y se actualizan solos.

## Dónde va cada cosa
- `src/server`  -> ServerScriptService
- `src/client`  -> StarterPlayerScripts
- `src/shared`  -> ReplicatedStorage/Shared
