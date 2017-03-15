## Questions relating to Snakes and Ladders solution

### What is different from the way you tried to solve the problem?

While we kept track of turns in a turn counter, this solution has a TurnLog class.
This solution also has more checks involved - it is more robust in terms of validating moves etc.

### Are there any parts you don't understand?

Yes!

### Testing - why has the dice class not been tested?

Because it just returns a random element from the array generated i a new dice object. It's hard to test randomness. We tested that the dice returned an integer and that it was within range. Perhaps there was a reason we shouldn't have done this?

### Why is all of the 'puts'-ing in one viewer class?
 It feels like it's a good idea to keep all the part of the game that prints to the console and interacts with the viewer separate from the logic. This means you can make changes to the cosmetic elements of the game without having to touch its inner working and seems safer somehow?
