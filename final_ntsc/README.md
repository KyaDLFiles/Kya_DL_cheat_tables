
Some stuff already documented as https://kyadlfiles.github.io/technical
Quick writeup about what's not:
- distance from floor goes to max 10,3; at which point kya starts freefalling
- aux speeds seem clamped? like after a certain value kya will move at the same max speed regardless of the value; except an absurdely high value which sends her to the libo
- setting current status to 168 unlock flight like in sep29/may12; but this is a forced method and can actually lock up kya in some circumstances (eg while fighting). another useful one is 161, which kills kya
- health <= 0 achieves zombie state, health > 250 crashes EVERYTHING (including the emulator itself)
- If infincibility/strength timer >= game timer, kya is invincible/strong
- Make kya invisible works for activation, but to deactivate you need to enter and exit FPV
- i don't know how cam pointers work, snugggles found them
- max mana can\'t be >10, but it can go negative
- regeneration seems to be forcibly given every time you enter NC
- game speed multiplier is wonderful. too fast breaks the game, negative value absolutely destroys it (try it!)
- dualshock 2 pressure values, does the game even actually use them?
- Starting level: 00 = NATIV
- some sectors load whole areas, other just some areas (eg: shops). Other parts stay always loaded even if you put an invalid sector
- Screen width: 3FE38E39 = 16:9, 3FAAAAAB  = 4:3)
- set regen cheat counter to 10 and freeze it to instantly regen by just pressing start
