File Contents Breakdown
1. *Imports*  
   - pygame → Main game library  
   - time & random → For delays and food spawning  

2. *Initial Setup*  
   - Screen dimensions (width, height)  
   - Colors (white, black, red, green, blue)  
   - Snake speed & block size  

3. *Key Functions*  
   - display_score() → Shows current score  
   - draw_snake() → Renders the snake  
   - message() → Displays game-over messages  

4. **Main Game Loop (game_loop())**  
   - Handles keyboard inputs (arrow keys)  
   - Detects collisions (walls/self)  
   - Spawns food randomly  
   - Updates snake length  

5. *Game Controls*  
   - *Arrow Keys* → Move the snake  
   - *Q* → Quit game  
   - *C* → Restart after losing
