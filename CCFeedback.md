# CCFeedback


### Praise 

- Aesthetics and visuals : people are SUPER happy with how the game looks. The neon, the bouncing in sync with the audio, the endless visual feedback to player input.
Lots of praise on the Particle Systems especially, and specifically on the final explosion as well as the portals.
Nobody noticed the freezing portals at all. Like, ever.
- Lots of things happening, always something cool to look at
- Poeple liked the slomo, the ability to take time and aim. On the same topic, the explosion when you take a hit, that gives you a breather, was appreciated. People super love the final explosion, like, A LOT
- People had fun breaking the game. At least there's that.
- Some people suggested it could be playable on mobile ? Why not
- The intensity rising feels super nice and there are a lots of elements to convey it
- Super good to have a tutorial / mess around area
___
### Not Great

- Game is super easy to break right now. Main bugs are :
  - Chain super easy to break after a couple of special attacks
  - The way Iframes are implemented right now, is disabling the collider of the player. That was a huge mistake on my side, as the player can super easily go out of bounds.
  - Special attack essentially became a Pandora's box, you never know what bugs you're gonna cause.
  - Scoring system breaks, and also does not have any purpose. The bar going up is nice though
- Not enough crowd control. There's the chain, but not enough crushing.
- The health in percentage form is misleading, people expect to have more health
- Central black hole is still confusing apparently ? I dunno
```
Note : I feel like the main bug is really the chain breaking. If that's solved, many other bugs will get solved at the same time. 
```
___
### Remarks

- Building momentum (like Gereon likes, making the ball spin around the player with a good rythm) received a lot of praise. However, there were mixed feelings about that momentum being broken when the ball hits an enemy or a bullet. Some people wanted the ball to keep going a crush multiple enemies, leading to more crowd control.
- A better way to track the overall high score, instead of it getting it reset every time
- Displying health could be done just by tweaking the color of the car
- Game is WAY too over engineered. It heavily need de-coupling of components, and some code structure. (I just don't have that skill just yet 😥)
- A "dummy" in the tutorial section could be useful
- Different enemy types could make the ball react differently, like a spiky enemy could hold the ball in place
- Need a restart button and a menu for QoL improvement