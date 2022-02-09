# Cornerless 1024
It's like 1024, but with no corners. Since the most popular method for most 2048 variants specifically involves combining into a corner, why not fuck with everyone and remove all four. I made this during school, so I didn't feel like actually cloning the original 2048 repository. Of course, tons of credit and respect goes to Gabe Cirulli & company for making this fun, inventive, and astonishingly distracting game. Below are a list of changes and some notes to give you a better understanding of how I made this version work.

## Changes
- Removed the "New Game" button
- Only spawns 2s
- The corners are simply not loaded into the grid.
- Style of the corner cells match the background
- New color sequence from https://coolors.co

## Notes
To be honest, a lot of the changes I made were just CSS corner-cuts. The "New Game" button didn't work with the longer game title, so I just removed it entirely. I initially tried to only write 2 cell elements in the HTML and center them, but I ended up just changing their background color to match the game container. I'm like 80% sure 2048 is impossible on this board, and even if it is possible it's too difficult for it to be the goal. I play 2048 and all the various variants during class pretty much every day, so this was a fun project to work on. Especially since I probably should've been studying.
