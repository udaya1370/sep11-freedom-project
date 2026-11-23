# Tool Learning Log

## Tool: **kaboom**

## Project: **parkour  game**

---

### 11/16/2026:
* - I called `add([...])` to create a new game object in the scene.
- I used `rect(width(), 48)` to shape it: full screen width, 48px tall.
- I placed it with `pos(0, height() - 48)` at the bottom-left, so its top sits 48px above the floor.
- I added `area()` to give it a hitbox for collisions.
- I added `body({ isStatic: true })` to make it solid and unmovable, so things land on it.
- I added `color(...)` and `outline(4)` just so I could see it.
- I made the side walls the same way: tall `rect`s with `area()` and `body({ isStatic: true })`, at x=0 and x=`width() - 24`.
- I relied on the player's own `body()` to handle gravity and landing, so once the ground existed, `isGrounded()` returned true and jumping worked.
thats a lot of learning for tonight ima get some sleep lol.
### 11/22/2026:
* 


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
