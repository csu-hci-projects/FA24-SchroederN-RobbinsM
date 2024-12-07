# FA24-SchroederN-RobbinsM
## Contributors:
Nolan Schroeder:\
Worked on the majority of the target systems like scoring and deletion. Also did the work for the moving of levels.\
\
Max Robbins:\
Worked on the ammo and teleport surfacing systems.\

## Associated Links:
https://youtu.be/RK9CNP2GE6o  \
https://youtu.be/ScnO4oAI0sE  \

## Running Requirements:
To run this application only 3 things are needed: \
- A Functioning vr headset \
- A working version of unreal engine to run the project \
- A computer that can support the project \

## AmmoPistol:
The AmmoPistol blueprint is what's responsible for basically all of the firing and ammo functionality.\
\
The weapon pickup is put in front of the player when the game starts, having 30 ammo to begin with.\
\
The player is able to fire by using the triggers. When they run out of ammo they are able to reload by hitting the trigger again and waiting for the gun to reload after 1.5 seconds.\
\
Ammo is also displayed on top of the gun with a text display, and it ticks down with every shot.\
\
The targets themselves have a health of 100 that goes down by 20 whenever it detects a projectile hitting it, using the "event Hit" to detect the projectile. After that it makes a check to see if the targets health is less than or equal to 0, if so it will destroy the actor.\
\

## Teleport zones:
The teleport zones were fairly simple. Both use a volume box that simply allows teleporting or not. \
\
We switch between them by utilizing a sender from the targets that tell the level to change the volume when a certain amount of targets are hit/destroyed. \

## Meetings:
- Dec 3rd, 2024 - Short communication online to get the project rolling\
\
- Dec 5th, 2024 - Short communication online to clarify work.\
\
- Dec 6th, 2024 - Video call online to finish up recording videos and creation of README.
