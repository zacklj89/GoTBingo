# GoTBingo
A game of thrones bingo game designed by Zachary Johnson and Reynolds Aguilar.

Design goals:

1) web based (probably 4x4) visual bingo board to be submitted by each subscriber with picture and name of characters from HBO's Game Of Thrones.

2) On the day of the first episode, each bingo board becomes visible to all other users.

3) Each week, the visual must be updated, shading red characters that die during that week's episode.

4) Display current ranking based on number of adjacent bingo block matches.


Checklist:

Drag and drop bingo board
- visualization 
- images can be uploaded onto draggable blocks
- text can be displayed over the image with the characters name
- images can resize properly based on block size
- page will resize if new users are added and space out cards properly

Login page
- username password
- visualization
- login won't matter after first date

Logic for game
- Winner in case deaths happen in same episode is based on time of death
- players bingo blocks will update based on us changing tiles to red after death
- bingo cards become locked on July 16th
- while creating a card, you can overwrite previous cards if the date is before july 16th
