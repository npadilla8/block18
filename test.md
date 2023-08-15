Writing Test Specifications

Unit Test: 

1. A function called "multiplication" that returns the product of the two input numbers.

    * If entered: multiplication(5, 2) results should be 10
    * If entered: multiplication(2, 5) results should be another number   that multiplies both
    * If entered: multiplication(6, "2") results should give an error > numbers should not be strings 
    * If entered: multiplication(6, "n") results should be give an error > Cannot multiply string and number 
    * 

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

    * If entered: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) > Results: [-1, 1, 3, 9, 15]
    * If entered: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) > Results: Should be an array of Odd numbers
    * If entered: concatOdds(["3, 2, 1"], [9, 1, 1, 1, 4, 15, -1]) > Results: Error - Arguments should be integers not strings 
    * If entered: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) > Results: For every repeated number > Array should result in only one - Array will not repeat numbers
    
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]
Think about the following; you may need to make assumptions or decisions about the prompt and how the code should behave:
What should happen with unexpected inputs?
What kinds of unexpected inputs should we worry about?
What should happen when there are multiples of the same odd number in the arrays? (Hint: We gave you the answer to this one in the example above.)

Functional Tests:

1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

    * When a user clicks checkout as a guest they should first be prompted if they would like to create an account for easier access. > If no, they will contiue to checkout. If yes > the will be brought up to the page where they can create their new account. 
    * When clicked on checkout as logged-in user > It will bring them to the login page.
    * If the cart is empty and they clicked checkout > show an error they may not continue as there are no itmes in the cart to checkout and to continue shopping 
    * Before they can click on checkout it will ask if they are done shopping and give them some suggestions similar to what they have chosen in the cart and suggestions of best seller items
    

Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:
What should happen if the cart is empty?
What needs to be shown to the user at each step of check out?
What behaviors of this feature does the prompt miss or gloss over?
Hint: Observe the shopping cart and checkout features of some popular websites to get some ideas!