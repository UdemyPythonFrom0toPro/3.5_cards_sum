# A list of cards is given. 
For example, something like this:

current_hand = [2, 3, 4, 10, 'Q', 5]

In general, the list can contain the following values: 2, 3, 4, 5, 6, 7, 8, 9, 10, 'J', 'Q', 'K', 'A'.

Each card has its own "weight":

2, 3, 4, 5, 6 weigh +1
7, 8, 9 weigh 0
10, 'J', 'Q', 'K', 'A' weigh -1
Task: having a list of cards (for example, see current_hand above), calculate their total "weight".

Note: this is a more difficult task. For a nice solution, think about how a dictionary can help you here.

Examples of inputs and expected results:

current_hand = [2, 3, 4, 10, 'Q', 5] # total weight = 2
current_hand = ['A', 3, 4, 10, 'J', 4] # total weight = 0
current_hand = [2, 7, 4, 9, 3, 5] # total weight = 4
Write the calculated total weight of the cards into a variable named cards_sum
