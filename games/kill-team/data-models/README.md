# Data Models 

## Models
- Effect
- Game
- List
- Map
- Mission
- Player
- Team

## Relationships

### Effect
- An Effect belongs to a Mission.
- An Effect belongs to many Games.

### Game
- A Game has many Teams.
- A Game has one Effect.
- A Game has one Mission.

### List
- A List belongs to a Player.

### Map
- A Map belongs to many Missions.

### Mission
- A Mission has one Map.
- A Mission belongs to many Games.

### Player
- A Player belongs to many Teams.
- A Player has many Lists.

### Team
- A Team belongs to a Game.
- A Team has many players.
