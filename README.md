# GeneratorsV1.5

A generator repair system for Roblox. Generators spawn at random locations, each with its own state and one of three minigames. Multiple players can repair a generator from different sides if the spots are free
The server handles spawnng, distance checks, occupied spots and repair completion. The client handles the UI and minigames

Files:
- `Server` Main generator logic
- `GeneratorUIController` Opens and closes minigame GUIs
- `Energy` Remember and repeat a sequence
- `Labry` Navigate a maze without touching walls
- `Wire` Connect wires by matching colors
The system isn't connected to rounds yet, so generators currently spawn when a player joins
