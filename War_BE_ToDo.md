25Nov:
1.  1.2 BE point from below - method that splits the deck in 2 - input este un deck  / output 2 deckuri egale
2. Make wargame.bogdanbudaca.com - link in main site header, new font awsm icon
3. Backend must be made public - AWS

--------

Rules (User story):
1. Deck is splitted equally between 2 players -> 52 / 2 = 26 cards each
2. Each player takes turns and puts down first card face up
3. Whoever has the biggest value card takes both cards
4. If cards were equal -> put 2 cards down - first face down, second face up
5. Who has the highest face up takes everything
6. Continue game
7. Game ends when one player has all cards - is declared winner

BE:
1.1 new method shuffleDeck
		Input: deck
		Output: randomized deck
		
1.2 new method: splitDeck
		Input: full deck
		Output: 1 array with 2 sub-arrays - each sub-array contains half of the input deck


-------------

How to shuffle deck?

Iterate all cards
For each card change to random position in deck

-------
02 December 2018: 
  - 1 BACKEND: create a method dealCards(howMany) 
  - BACKEND+FRONTEND implement start game mechanism (socket.io for communication between 2 browsers thru backend)
  
  incepem backendu in c# (c sharp) pt game rules
- primii pasi in c#
- cream regulile pt war game in rules BE (BackEnd)
- combinam BEurile, le chemam intre ele , in asa fel incat un request din frontend sa treaca prin amandoua

-----
9Dec 2018:

1. Make a method that receives your name as parameter and returns an array with every letter of the given name.
2. Make a class with properties letter (as string) and position (as int)
3. Make a method similar to ex 1, that returns an array with objects of type from the ex2 class, that contains every letter and position in array.
4. To understand 'compiled / compiling' you can inspect the .dll/.exe file after compiling - using tool called 'ildasm'
   - Installed here with Visual Studio - C:\Program Files (x86)\Microsoft SDKs\Windows - ildasm.exe
   - https://www.youtube.com/watch?v=D_1Op4TBM-Y
