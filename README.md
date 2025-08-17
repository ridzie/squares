# Square Survival

A minimalist browser game built with **HTML5 Canvas + JavaScript**.  
You control a square that follows your mouse/touch. Survive falling blocks, manage your size, and chase a high score.  

---

## 🎮 Gameplay Rules

- **White squares** → `+1` point  
  - Every 10 whites shrink your size by 1 (not smaller than the starting size).  
- **Black squares** → Grow in size and `-1` point  
  - Every 10 blacks shrink your size by 1.  
- **Red squares** → Instant **Game Over** (fall diagonally).  
- **Green circles** → Rare, give `+2` points and shrink you.  
- **Pink glitch blocks** → Disappear on their own (only after score > 50 or < -50).  

The game ends in a red screen spill when you hit a red square.  

---

## 🖥️ How to Run

Clone the repo and open `squares.html` in any modern browser:

```bash
git clone https://github.com/yourusername/square-survival.git
cd square-survival
open squares.html   # or double click the file