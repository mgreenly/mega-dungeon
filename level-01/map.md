# Level 1 Map

```
                                            ┏━━━━━┓     ┏━━━━━┓     ┏━━━━━┓
                                            ┃     ◊═════◊     ◊═════◊     ┃
                                            ┃ 27  ┃     ┃ 28  ┃     ┃ 29  ┃
                                            ┗━━◊━━┛     ┗━━◊━━┛     ┗━━◊━━┛
                                               ║           ║           ║
                                               ╚═══════════╬═══════════╝
                                                           ║
        ┏━━━━━┓  ┏━━━━━┓  ┏━━━━━┓           ┏━━━━━┓     ┏━━◊━━┓     ┏━━━━━┓
        ┃     ◊══◊     ◊══◊     ┃           ┃     ◊═════◊     ┃     ┃     ┃
        ┃ 20  ┃  ┃ 21  ┃  ┃ 22  ┃           ┃  7  ┃     ┃ 26  ┃     ┃ 30  ┃
        ┗━━◊━━┛  ┗━━◊━━┛  ┗━━━━━┛           ┗━━◊━━┛     ┗━━◊━━┛     ┗━━◊━━┛
           ║        ║                          ║           ║           ║
           ╚════════╬══════════════════════════╬═══════════╬═══════════╝
                    ║                          ║           ║
                 ┏━━◊━━┓     ┏━━━━━┓      ┏━━━━◊┓     ┏━━◊━━┓
                 ┃     ┃     ┃     ◊══════◊  ▤  ┃     ┃     ┃
                 ┃ 19  ┃     ┃  6  ┃      ┃  8  ┃     ┃  9  ┃
                 ┗━━◊━━┛     ┗━━◊━━┛      ┗━◊━━━┛     ┗━◊━━━┛
                    ║           ║           ║           ║
                    ╚═══════╦═══╩═══╦═══════╩═══╦═══════╬═╦═══╦══════════════════╗
                            ║       ║           ║       ║ ║   ║                  ║
                         ┏━━◊━━┳┳━━━◊┳┳━━━━━┳┳━━◊━┳┳━━━━◊┳◊┳━━◊━━┓               ║
                         ┃     ┃┃    ┃┃     ┃┃    ┃┃     ┣━┫     ┃               ║
                         ┃  1  ┃┃  2 ┃┃  3  ┃┃  4 ┃┃  5  ┃ ┃ 10  ┃               ║
                         ┗━━━━━┛┗━━◊━┛┗━━◊━━┛┗━━◊━┛┗━━◊━━┛ ┗━━━━━┛               ║
                                   ║     ║      ║     ║                          ║
                                   ╚═════╬══════╬═════╬══════════════════════════╣
                                         ║      ║     ║                          ║
        ┏━━━━━┓  ┏━━━━━┓  ┏━━━━━┓        ║      ║     ║     ┏━━━━━┓  ┏━━━━━┓  ┏━━◊━━┓
        ┃     ◊══◊     ◊══◊     ┃        ║      ║     ║     ┃     ◊══◊     ◊══◊     ┃
        ┃ 11  ┃  ┃ 12  ┃  ┃ 13  ┃        ║      ║     ║     ┃ 23  ┃  ┃ 24  ┃  ┃ 25  ┃
        ┗━━━━━┛  ┗━━◊━━┛  ┗━━◊━━┛        ║      ║     ║     ┗━━━━━┛  ┗━━◊━━┛  ┗━━◊━━┛
                    ║        ║           ║      ║     ║                 ║        ║
                    ╚════════╬═══════════╝      ║     ╚═════════════════╬════════╝
                             ║                  ║                       ║
                          ┏━━◊━━┓               ║                    ┏━━◊━━┓
                          ┃     ┃               ║                    ┃     ┃
                          ┃ 14  ┃               ║                    ┃ 18  ┃
                          ┗━━◊━━┛               ║                    ┗━━◊━━┛
                             ║                  ║                       ║
                          ┏━━◊━━┓               ║                    ┏━━◊━━┓
                          ┃     ┃               ║                    ┃     ┃
                          ┃ 15  ┃               ║                    ┃ 17  ┃
                          ┗━━◊━━┛               ║                    ┗━━━━━┛
                             ║                  ║
                          ┏━━◊━━┓               ║
                          ┃     ┃               ║
                          ┃ 16  ┃               ║
                          ┗━━━━━┛               ╚ (Entrance)
```

## Legend
- Room numbers: 1-30
- `━` and `┃` = Room walls (heavy solid lines)
- `┏` `┓` `┗` `┛` = Room corners (heavy solid lines)
- `┳` `┻` `┣` `┫` = Room wall junctions (heavy solid lines)
- `═` and `║` = Corridors (light double lines)
- `╔` `╗` `╚` `╝` = Corridor corners (light double lines)
- `╦` `╩` `╠` `╣` `╬` = Corridor junctions (light double lines)
- `◊` = Doors
- `▤` = North-South stairs
- `▥` = East-West stairs
- `┋` and `┈` = Portcullis

## Layout Description
- **Entry**: Bottom of the map - marked corridor entrance leads to the central junction
- **Main Corridor**: Rooms 1-5 and 10 form the central spine of the dungeon
- **Central Junction**: Large hallway system connecting all four major sections
- **Original Upper Loop**: Rooms 6-9 form an interconnected loop
- **West Wing**: Rooms 11-16 form a vertical complex with linear progression
- **East Wing**: Rooms 17-18 and 23-25 create an eastern section
- **Northwest Extension**: Rooms 19-22 branch off to the northwest
- **North Extension**: Rooms 26-30 form the northernmost section with room 7

## Key Features
- Four major sections branching from the central hub
- Multiple paths and loops prevent bottlenecks
- Several dead-ends suitable for special encounters (rooms 10, 16, 17, 22, 30)
- Interconnected design allows for tactical retreat and flanking
- The expanded layout creates opportunities for faction territories
- Strategic chokepoints at major corridor junctions

## Encounter Difficulty Distribution
Based on the assigned difficulties:
- **Hard**: Room 11 (West Wing entrance)
- **Moderate**: Rooms 13, 17 (distributed across wings)
- **Easy**: Rooms 1, 7, 8, 12, 14, 16, 20, 23, 24 (spread throughout)
- **Unassigned**: Remaining 18 rooms for treasure, puzzles, or environmental challenges
