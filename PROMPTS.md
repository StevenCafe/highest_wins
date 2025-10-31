### prompt_001 - Initialize and describe the game
```
Generate a game code using WebGL that can simply run on html with three.js via CDN. the game is in 3D world, player can move with wasd keyboard to move and space to jump. there is a scoreboard in the end to showcase the highest score for the game. 

Players have to jump as high as they can with many fully solid blocks floating in the air. The score is the height players stand in the air. Game over when player falls from the starting platform.
```

### prompt_002 - Refine the game setting
```
The character should look a bit like a figure in roblox. avatar should be facing to the direction when player change directions. The player can jump up to 5m. All the blocks are floating solidly in the sky and should allow players to jump from one to another. Sometimes the blocks appear in stair-like formation. 

Grounding rule: jumping succeeds only when grounded; platforms and blocks are treated as fully solid. 

Check if the code is runnable, and fix any bugs if it isn't.
```

### prompt_003 - Add features to the game
```
Additionally, add this camera feature: 
Drag mouse to rotate camera (orbit view) will change player's direction. Avatar always back to the camera and when press "w" means walk away from camera. W/A/S/D movement direction always matches the camera’s perspective.
```
