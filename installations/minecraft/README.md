# Minecraft Launcher

## Manual Installation Instructions

NOTE: You need to only do this once and the modpack is automatically updated whenever modlist is changed!

1. Download Forge Installer (`1.20.1-47.3.10`) from [**here**](https://maven.minecraftforge.net/net/minecraftforge/forge/1.20.1-47.3.10/forge-1.20.1-47.3.10-installer.jar) and click on `Install Client` and install to the default Minecraft installation (typically, `~/.minecraft` or `%appdata%\.minecraft` on Windows)
2. Download the `shallowslept-mclauncher.zip` archive from [**Releases**](https://github.com/Mythoid/shallowslept-modpack/releases), and extract everything into your default Minecraft installation location.
3. Add the following snippet to the `launcher_profiles.json` file in your default Minecraft installation location, under the `profiles` group:
   ```json
   "shallowslept-modpack-instance": {
     "created": "1970-01-02T00:00:00.000Z",
     "gameDir": <replace-with-game-path>,
     "icon": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAIAAACQkWg2AAAACXBIWXMAAAsTAAALEwEAmpwYAAAFyWlUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNi4wLWMwMDYgNzkuZGFiYWNiYiwgMjAyMS8wNC8xNC0wMDozOTo0NCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RFdnQ9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZUV2ZW50IyIgeG1sbnM6ZGM9Imh0dHA6Ly9wdXJsLm9yZy9kYy9lbGVtZW50cy8xLjEvIiB4bWxuczpwaG90b3Nob3A9Imh0dHA6Ly9ucy5hZG9iZS5jb20vcGhvdG9zaG9wLzEuMC8iIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIyLjQgKFdpbmRvd3MpIiB4bXA6Q3JlYXRlRGF0ZT0iMjAyNC0xMC0wNlQxNDo0MzoxOSswNzowMCIgeG1wOk1ldGFkYXRhRGF0ZT0iMjAyNC0xMC0wNlQxNDo0MzoxOSswNzowMCIgeG1wOk1vZGlmeURhdGU9IjIwMjQtMTAtMDZUMTQ6NDM6MTkrMDc6MDAiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6MTc3ZjFkNWYtYjk0MC1hZDRiLWE4MWItOWI2ZTdmNGIxMDkxIiB4bXBNTTpEb2N1bWVudElEPSJhZG9iZTpkb2NpZDpwaG90b3Nob3A6NGNkNTdmNDUtNGFiNi1iNzRjLWE1ODYtZDc2ODg1NmFkZjdhIiB4bXBNTTpPcmlnaW5hbERvY3VtZW50SUQ9InhtcC5kaWQ6ZDkzNmFhMTUtYjk0MS1mMjQ4LWE1NjMtOTMwNzJiYTBkMWE5IiBkYzpmb3JtYXQ9ImltYWdlL3BuZyIgcGhvdG9zaG9wOkNvbG9yTW9kZT0iMyI+IDx4bXBNTTpIaXN0b3J5PiA8cmRmOlNlcT4gPHJkZjpsaSBzdEV2dDphY3Rpb249ImNyZWF0ZWQiIHN0RXZ0Omluc3RhbmNlSUQ9InhtcC5paWQ6ZDkzNmFhMTUtYjk0MS1mMjQ4LWE1NjMtOTMwNzJiYTBkMWE5IiBzdEV2dDp3aGVuPSIyMDI0LTEwLTA2VDE0OjQzOjE5KzA3OjAwIiBzdEV2dDpzb2Z0d2FyZUFnZW50PSJBZG9iZSBQaG90b3Nob3AgMjIuNCAoV2luZG93cykiLz4gPHJkZjpsaSBzdEV2dDphY3Rpb249InNhdmVkIiBzdEV2dDppbnN0YW5jZUlEPSJ4bXAuaWlkOjE3N2YxZDVmLWI5NDAtYWQ0Yi1hODFiLTliNmU3ZjRiMTA5MSIgc3RFdnQ6d2hlbj0iMjAyNC0xMC0wNlQxNDo0MzoxOSswNzowMCIgc3RFdnQ6c29mdHdhcmVBZ2VudD0iQWRvYmUgUGhvdG9zaG9wIDIyLjQgKFdpbmRvd3MpIiBzdEV2dDpjaGFuZ2VkPSIvIi8+IDwvcmRmOlNlcT4gPC94bXBNTTpIaXN0b3J5PiA8L3JkZjpEZXNjcmlwdGlvbj4gPC9yZGY6UkRGPiA8L3g6eG1wbWV0YT4gPD94cGFja2V0IGVuZD0iciI/PjezF34AAACvSURBVCiR1ZKxDsMgDET5hW4wlolujPz/n7DBRLdsVV+5BKJUrZRuPSnhbN8RYmzMhstXmD1G9rrh1jHCow0WQhjlGOO9AzKSCFYDi3OulKJdEdVaHx0QQuURIHt5eBSnlFprIksHhJCkCLLVMI6BSFvKoA9CxvGmYS/6xP/DwM+9G9SMo4Em0Dje3nt1Rh1TqNI0WGtzzkpxo5R1cRBNACUEyOZlnxiNX4bv1Hg/AXlp9nNwLgNfAAAAAElFTkSuQmCC",
     "javaArgs": "-Xmx6G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M -javaagent:unsup.jar",
     "lastUsed": "1970-01-02T00:00:00.000Z",
     "lastVersionId": "1.20.1-forge-47.3.10",
     "name": "Shallowslept",
     "type": "custom"
   }
   ```

   Your `launcher_profiles.json` should look like this,
   ```json
   {
     "profiles": {
        "shallowslept-modpack-instance": { ... },
        // other profiles goes here
     },
     // other stuff, don't need to touch
   }
   ```
4. Replace the `<replace-with-game-path>` with the any of these values (depending on your OS),
   ```json
   // Windows -- you need to change from "User" to your username.
   "C:\\Users\\User\\AppData\\Roaming\\.minecraft\\installations\\Shallowslept"

   // MacOSX
   "~/Library/Application Support/minecraft/installations/Shallowslept"

   // Linux
   "~/.minecraft/installations/Shallowslept"
   ```
5. Launch Minecraft playing your new profile!

## `unsup` Distribution
[`unsup`](https://git.sleeping.town/unascribed/unsup) is a Java Agent that runs before the start of the game, it will automatically download any mod files required. Additionally, any changes to main modlist will apply to your pack installation automatically.

The project is licensed with LGPL, so we can include the distribution into the modpack. The version used is `0.2.3`.