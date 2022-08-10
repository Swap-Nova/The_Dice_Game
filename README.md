# <ul> 🎲 The Dice Challenge Gaming Experience </ul> 
### A two-player dice game. The working is pretty simple, just by refreshing the tab both the dices present their values.
* If Player-1 dice's value is higher compared to Player-2 then Player-1 wins and vice-versa.
* If the value of both dices are equal then the match will be a draw.
* To restart the challenge just refresh your webpage.

#### The Webpage is built using JavaScript, HTML & CSS.
##### Primarly focusing on the JS part, we started of by using the floor & random function to roll the dice from 1-6:
```bash
Math.floor(Math.random());
````

##### Moving on, to select the exact image of the dice we created variables and used the `SetAttribute()` Property to attach the image of the dice value.
```bash
element.setAttribute("class", "democlass");
````

##### At the end to decide which Player wins the challenge we use an if-else loop as well as the else-if condition to find out the result.
```bash
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false
}
````
