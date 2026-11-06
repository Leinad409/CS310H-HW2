Daniel Cohen

CS310H

Lab 2

Unreal version 5.0.3

---

Video of Features:
[Click here for the video demonstrating the features described below for Lab2]([https://www.youtube.com/watch?v=qk19vGlqKwA](https://www.youtube.com/watch?v=Fbx0HBFwGzA))

---

**Features in the Project:**

- Used the FPS template and loaded the starter assets.
 
Create 3 unique levels
- One level must is a scene with a start button that loads the first level and a quit button that exits the game.
- The level that is loaded from the menu has hazards and targets.

Environment
- Once all targets have been destroyed the third level automatically loads.
- The last level has hazards and targets, but a different layout.
- Once all targets have been destroyed the menu scene automatically loads.
- Both of the non-menu levels have static meshes with materials applied for the user to navigate.
- Each non-menu level has at least 3 targets and at least 3 hazards.
  - Targets left are displayed at the top right of the screen
- Targets have a “health” variable. Their starting health is 100. 
- After a target’s health reaches 0 or less the target is destroyed.
- Once all targets in a level are destroyed the next level automatically is loaded.
- Hazards need to damage the player.
  - Lava does 25 damage.
  - Spinning bar does 10 damage.
  - Spike does 5 damage.
    
Health  
- The player has 100 starting health.
- When a player collides with a hazard they will lose health. 
- Once a player’s health reaches 0 or less the level should automatically restart the level currently being played.
- Health is displayed at the bottom left of the screen

Ammo
- The player should have limited ammo.
- Whenever the player fires if they have ammo the ammo is reduced by 1.
- If the player is currently at 0 or less ammo the gun does not fire.
- The ammo count is displayed at all times in the bottom right of the screen.

Pickups
- Ammo pickups
  - If the player runs over an ammo pickup their ammo count increases and the pickup is destroyed.
  - Ammo pickups give 5 ammo.
  
- Health pickups
  - If the player runs over a health pickup their health increases. Health Cannot exceed 100.
  - Health pickups give 25 health.
