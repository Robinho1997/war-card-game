# war-card-game

Building a card game by requesting the data from an api was really enjoyable.

I used the get method in the fetch request to get a deck of 52 cards.
Then when I receive the data I use the properties for the card value and the value of remaining cards.

To check which value is higher then the other, 
I created an Array with all the cardValues as strings in rising power.
Then I could use the indexOf() method with the cardvalues from the api as arguments to check who won.
The player who won got +1 in its scorevariable.
When the deck is empty, which I tracked with the property data.remaining a function will check with an if statement which score is higher and then will display the winner.
Also when the deck is empty the draw button is disabled.


https://robinho1997.github.io/war-card-game/
