# Spectral Swap

**Spectral Swap** is a Roblox game where players can dynamically switch between two distinct bodies, referred to as the **Main Body** and the **Spectre Body**, while leveraging a puck-throwing mechanic for interaction and gameplay progression. The game provides unique mechanics involving trajectory prediction, body swapping, and environment interaction.

NOTE: What I provided was just the main body of code, there are other things in Roblox Studio that I have NOT included.

## Features

- **Dual-Body Mechanics**: 
  - Players can switch between the Main Body and the Spectre Body using the **Q** key.
  - The Spectre Body is represented by a glowing, neon-styled avatar positioned relative to the Main Body.
  - Accessories and animations are seamlessly managed during body swapping.

- **Puck-Throwing Mechanic**:
  - Players can equip a puck using the **E** key and throw it using the left mouse button.
  - The puck's trajectory is dynamically calculated, with visual guides for better aiming.
  - Interaction with the environment through puck reflections and valid zones.

- **Zone System**:
  - Valid zones and walls are dynamically managed using tags (`isValidZone` and `isValidWallZone`).
  - Zones can be added or removed dynamically, with automatic updates to the valid zone list.

- **Trajectory Visualization**:
  - A smooth, neon-styled trajectory guide helps players visualize the puck's path.
  - The trajectory adjusts dynamically based on mouse position and player state.

- **Custom Animations**:
  - Several animations enhance player immersion, including idle, body swapping, equipping the puck, and throwing animations.

## Key Bindings

- **E**: Equip/unequip the puck.
- **Q**: Swap between the Main Body and Spectre Body.
- **Left Mouse Button**: Throw the puck when equipped.

## Future Enhancements

- Multiplayer integration with distinct interactions for different players.
- Additional environmental mechanics involving puck physics.
- Customization options for Spectre Body appearances and abilities.
- Leaderboards for competitive gameplay.

## 🌟 Watch the Showcase GIF! 🌟
![alt text](SpectralSwapGIF.gif) <br>
(unfortunately the FPS on the GIF is low 😞) 
