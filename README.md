
	 ,----.                             
	'  .-./    ,--,--.,--,--,--. ,---.  
	|  | .---.' ,-.  ||        || .-. : 
	'  '--'  |\ '-'  ||  |  |  |\   --. 
	 `------'  `--`--'`--`--`--' `----' 
	 		          ,---.                       
			   ,---. /  .-'                       
			  | .-. ||  `-,                       
			  ' '-' '|  .-'                       
			   `---' `--'                         
	    ,--.   ,--. ,---.                   
	    |  |   `--'/  .-' ,---.             
	    |  |   ,--.|  `-,| .-. :            
	    |  '--.|  ||  .-'\   --.            
	    `-----'`--'`--'   `----'   

 	-----------------------------------------------------
 	
 	Victor Paiva Torres 	<vpaivatorres@gmail.com>
	February 23, 2015		Natal, RN - Brazil
	MIPS Assembly			Mars Simulator 4.5
	
	-----------------------------------------------------
	
		The Game of Life, also known simply as Life, 
	is a cellular automaton devised by the British 
	mathematician John Horton Conway in 1970.

		The "game" is a zero-player game, meaning 
	that its evolution is determined by its initial 
	state, requiring no further input. One interacts 
	with the Game of Life by creating an initial 
	configuration and observing how it evolves or, 
	for advanced players, by creating patterns with 
	particular properties.
	
	See more: http://en.wikipedia.org/wiki/Conway's_Game_of_Life
	
	-----------------------------------------------------
	
	- Any live cell with fewer than 		   
	  two live neighbours dies, as 			   
	  if caused by under-population.		   
							   
	- Any live cell with two or three 		   
	  live neighbours lives on to the 		   
	  next generation.			  	   
							   
	- Any live cell with more than three 		   
	  live neighbours dies, as if by 		   
	  overcrowding.					   
							   
	- Any dead cell with exactly three 		   
	  live neighbours becomes a live 		   
	  cell, as if by reproduction.	
	
	-----------------------------------------------------

	64 columns 	width pixels			   
	64 rows 	height pixels
	
	Space needed: 64 * 64 * 4 bytes (32 bits)
	
	Base address: 0x10010000 (static data)
	
