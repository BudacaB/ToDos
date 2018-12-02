1. Display card deck array in FE
1.1 Create component 'Deck..' to display the deck array - make HTML to iterate all cards in 'services' response
1.2 Request deck from backend through API in a 'services' file
1.3 Create Home component -> place <deck></deck> (home component just contains <deck> tag)

---------------

25Nov:
1. ^1. Style deck display - maybe array like instead of one long column

02 December 2018: 
  - 1 FRONTEND: create a component <active-game> where you display two players and their cards
  - 2 FRONTEND modify home component to show: if a gamee is started: "active-game" component. if a game is not started: "begin-game" component
  - BACKEND+FRONTEND implement start game mechanism (socket.io for communication between 2 browsers thru backend)
  - Replace hardcoded "Writing stuff" message with text input - input tag and using send() hand over to the server -> chat between players -  https://angular.io/guide/user-input
