# NeXtCS Project 01
### Period:09
### Name0: Jimmy Lin
#### Selected Game: Space Invaders
---

### How To Play
Survive waves of enemies, dodge enemy projectiles to avoid losing lives, if lives hit zero, the game ends. Use left and right arrow keys to move left and right, use space bar to shoot, 'r' to reset the game, and 'p' to pause the game.


---

### Features
After each wave of enemies has been defeated, another wave will spawn automatically, this new wave will have faster speed, shoot more often, and have a redder color.

---

### Changes
After feedback round:
- split Enemy and player into seperate classes to make things less complicated
- instead of having a "die" method, I just removed the Object from their array when they "died".
During programming:
- made enemy movement happen every 60 frames, achieving a more arcade game look
- made all enemies change direction in unison instead of individually
- added waves and varying difficulty
