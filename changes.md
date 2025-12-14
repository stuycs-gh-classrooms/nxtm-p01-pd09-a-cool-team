* abandoned keeping player and enemy in same class, would be too complicated
* instead of have a "die" method for everything, I deleted the object from their corresponding arrays whenever they collided with something
* added direction to enemy and player, enemy will change direction when hitting edge of screen, player will change direction when arrow keys are pressed
* made enemies reset to the top of the screen if they get too close to the player, the player loses lives based on how many enemies do this
* instead of the enemies moving smoothly, I added made it so that update() only runs every 60 frames, making it more accurate to how the enemies move in the actual game
* instead of each enemy changing direction individually, I made it so that as soon as one enemy hits the edge, more acurrate to the actual game, every single enemy changes direction together, this was done by adding a direction instance to enemy class and also method changeDir
* instead of winning after defeating all enemies, changed to an endless wave mode, after defeating all enemies in current wave, immediately spawns next batch, the speed and fireChance of the enemies are incremented every wave, making it harder the more waves you survive. Since theres technically no way to "win" anymore, Boolean gameWon has been removed along with all the text displayed when it is true.
* Added text to display the current wave at the start of each wave, also added a final score screen displaying the final score and how many waves you survived
* added a color to enemies, color shifts from purple to red as more waves go by, making it easier to see the change in dificulty
