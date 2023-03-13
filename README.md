
		Y A H T Z E E

This is Zorst's old Yahtzee game for Unix after a facelift and a few
fixes. It started when I noticed that there is a small security hole
in the standard Linux version (because it predates a working rename())
it uses system() to run mv. Thus if setuid games it can be used to get
access as games.

I fixed this by putting the rename back. The old one blew up with ^Z so
I switched to ncurses. Finally since it was ncurses I added colour to
the entire game.

The gameplay/logic hasn't changed a line - proof that its the game play
that counts not the flash graphics.

	Alan


Zorst's readme is in README.old
