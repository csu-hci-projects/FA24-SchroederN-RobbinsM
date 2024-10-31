# FA24-SchroederN-RobbinsM
## Contributors:
Nolan Schroeder:\
Worked on the health systems like player heealth, health packs, and hazard damage as well as the menu and his level.\
Responsible for most of the GitHub troubleshooting
\
Max Robbins:\
Worked on the ammo and target systems like ammo pickups, no firing at zero ammo, and targets dissapearing after losing all their health to bullets.\
Also contructed the fire level.

## Associated Links

## The Fire Level
The fire level consists of the player, a weapon pick up, 3 targets, 3 ammo pickups, __ health pickups, and 6 hazards the player can be damaged by.\
\
The weapon pickup is put in front of the player to get them moving, starting with zero ammo.\
\
The pickups found near the targets give the player five bullets, the perfect amount to remove the targets.\
\
Ammo is given to the player by checking for collision overlap with the player, and then increasing the ammo count of the player by a pickup amount.\
\
The targets themselves have a health of 100 that goes down by 20 whenever it detects a projectile hitting it, using the "event Hit" to detect the projectile. After that it makes a check to see if the targets health is less than or equal to 0, if so it will destroy the actor.\
\
___Insert Section on Hazards and how they handle health here___\
\
___Insert Sections on health pickups and basics of how they work here___\
\

## ___Insert other level name here___
___Insert level details here

## Resources Used
ChatGPT was a very useful resource as it alowed us to find answers to bug and collision issues we were having while making the project\
\
The videos used for the labs were also helpful in getting some basics down before moving on to more complex systems.
