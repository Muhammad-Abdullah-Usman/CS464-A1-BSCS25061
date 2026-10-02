# CS464 Assignment 01 · Muhammad Abdullah · BSCS25061

## Game 1 · Jetpack Joyride

- **Store link:** [https://play.google.com/store/apps/details?id=com.halfbrick.jetpackjoyride&hl=en&pli=1]
- **Genre:** Endless runner / arcade
- **I played:** Approximately 33 minutes, completed the tutorial, reached Rookie rank 3, and achieved a best distance of 1,441 m.

<p>
<img src="Docs/game1/1.png" width="240">
<img src="Docs/game1/2.png" width="240">
<img src="Docs/game1/3.png" width="240">
<img src="Docs/game1/4.png" width="240">
</p>

1. **[M1, M6]** · Jetpack movement during a run while collecting coins.
2. **[M4]** · Missions give the player specific objectives that influence how each run is played.
3. **[M3]** · A vehicle pickup changes the normal movement system and temporarily protects the player.
4. **[M2]** · The game records distance and saves the player's best distance as a high score.

| # | Mechanic | Dynamic | Aesthetic | Bartle type |
|---|---|---|---|---|
| M1 | Holding the screen fires Barry's machine-gun jetpack downward and makes him rise, while releasing the screen makes him fall. | Players repeatedly hold and release the screen to control their height and move around hazards. | **Challenge:** precise height control becomes increasingly important as more hazards appear. | **Achiever:** players act on the game world to survive and travel farther. |
| M2 | The player's distance increases continuously during a run and their best distance is saved as a high score. | Players repeatedly start new runs and try to travel farther than their previous best. | **Challenge:** beating a previous distance requires increasingly successful runs. | **Achiever:** the player is trying to beat a measurable goal set by the game. |
| M3 | Collecting a vehicle pickup replaces Barry's normal movement with a temporary vehicle that has different controls and protects him until it is destroyed. | Players adapt their movement strategy when using different vehicles and may take more risks while protected. | **Discovery:** each vehicle gives the player a different movement system to learn. | **Explorer:** players interact with the game world to discover how different vehicles behave. |
| M4 | The game gives missions such as reaching a certain distance, collecting vehicles, high-fiving scientists or narrowly avoiding missiles. | Players alter how they approach a run in order to complete the current mission instead of only focusing on distance. | **Challenge:** missions create additional goals that must be deliberately completed. | **Achiever:** completing objectives contributes to progression and rank advancement. |
| M5 | After death, the game can offer revival options that allow the player to continue the same run instead of immediately restarting. | Players may save revival resources for runs in which they are close to beating their high score. | **Challenge:** continuing a strong run gives the player another chance to reach a difficult target. | **Achiever:** reviving helps the player continue pursuing measurable progress. |
| M6 | Coins collected during runs act as currency that can be spent on boosts, revives and other equipment. | Players move toward coin trails and decide whether to save their currency or spend it to improve later runs. | **Challenge:** resource collection and spending can improve the player's chances of surviving longer. | **Achiever:** coins are used to improve performance and progression in the game. |
| M7 | Colliding with hazards such as zappers or missiles ends the run unless the player is protected by a vehicle or another defensive effect. | Players constantly adjust their height and timing to avoid hazards and remain alive for longer. | **Challenge:** survival depends on reacting correctly to increasingly difficult obstacles. | **Achiever:** avoiding failure lets the player continue increasing distance and score. |

**Aesthetic profile:**  
Jetpack Joyride mainly focuses on **Challenge**, **Sensation**, and **Submission**. Challenge comes from controlling Barry precisely, avoiding hazards, completing missions and trying to beat previous distances. Sensation comes from the responsive jetpack movement, explosions, vehicles, sound effects and visual feedback. Submission is also important because runs are short, easy to restart and suitable for repeated casual play.

**Player types**
- **Primary: Achiever (Acting × World)**, because the game constantly gives measurable goals such as increasing distance, beating high scores, completing missions and progressing through ranks (M2, M4, M7).
- **Secondary: Explorer (Interacting × World)**, because players discover how different vehicles, power-ups and systems behave and adapt to them during play (M3).



## Level blockouts

| Level | Screenshot | Its idea | Wayfinding tool |
|---|---|---|---|
| Level01 | <img src="Docs/levels/level01.png" width="320"> | An introductory route connects two enclosed spaces through a narrow bridge, requiring the player to carefully cross the middle section before reaching the goal. | **Landmark:** a tall, brightly coloured pillar beside the goal gives the player a visible destination to move toward. |
| Level02 | <img src="Docs/levels/level02.png" width="320"> | A split-route level gives the player a choice between a short risky path with gaps and a longer, wider elevated path with ramps. | **Leading lines:** the shapes and edges of the two routes visually guide the player from the spawn room toward the goal room. |
| Level03 | <img src="Docs/levels/level03.png" width="320"> | A maze forces the player to navigate several turns and corridors before reaching the goal. | **Breadcrumbs:** small yellow markers are placed along the intended route to help guide the player through the maze. |
| Level04 | <img src="Docs/levels/level04.png" width="320"> | A sequence of separated platforms rises toward a central peak and then descends toward the goal, requiring repeated jumps. In a scripted version, the highest platform could move horizontally or vertically to increase the challenge. | **Contrast:** the yellow platforms stand out clearly from the surrounding grey geometry and show the intended traversal route. |
| Level05 | <img src="Docs/levels/level05.png" width="320"> | An elevated route winds around a large central tower before the player reaches the final goal area. | **Framing:** a bright yellow arch frames the entrance to the goal room and draws attention toward the destination. |