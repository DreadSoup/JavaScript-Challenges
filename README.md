# javaScriptChallenges
Log of challenges attempted during JavaScript course

fundamentals 1 - challenge 1:
Declare variables for Mark and John, create variables for BMI using the calculation

fundamentals 2 - challenge 1:
Create a function to calculate an average score (value), create a function to check a winner based on average score and other condtions, log the results

fundamentals 2 - challenge 2:
Create a function to calculate a tip, call the function with data from array
BONUS - create an array and store the totals

fundamentals 2 - challenge 3:
Create two objects, create a BMI calculator, log who has the higher BMI (include values)

fundamentals 2 - challenge 4:
Create a function to calculate a tip, call the function with data from array, bills
Use a for loop to create 2 new arrays, tips and totals
BONUS - create a function to calculate the sum of the totals and tips

developerSkills - challenge 1:
Given an array of forecasted maximum temperatures, the thermometer displays a
string with the given temperatures. Example: [17, 21, 23] will print "... 17ºC in 1
days ... 21ºC in 2 days ... 23ºC in 3 days ..."

dataStructures modernOperators and strings - challenge 1:
1. Create one player array for each team (variables 'players1' and
'players2')
2. The first player in any player array is the goalkeeper and the others are field
players. For Bayern Munich (team 1) create one variable ('gk') with the
goalkeeper's name, and one array ('fieldPlayers') with all the remaining 10
field players
3. Create an array 'allPlayers' containing all players of both teams (22
players)
4. During the game, Bayern Munich (team 1) used 3 substitute players. So create a
new array ('players1Final') containing all the original team1 players plus
'Thiago', 'Coutinho' and 'Perisic'
5. Based on the game.odds object, create one variable for each odd (called
'team1', 'draw' and 'team2')
6. Write a function ('printGoals') that receives an arbitrary number of player
names (not an array) and prints each of them to the console, along with the
number of goals that were scored in total (number of player names passed in)
7. The team with the lower odd is more likely to win. Print to the console which
team is more likely to win, without using an if/else statement or the ternary operator

dataStructures modernOperators and strings - challenge 2:
1. Loop over the game.scored array and print each player name to the console,
along with the goal number (Example: "Goal 1: Lewandowski")
2. Use a loop to calculate the average odd and log it to the console (We already
studied how to calculate averages, you can go check if you don't remember)
3. Print the 3 odds to the console, but in a nice formatted way, exactly like this:
Odd of victory Bayern Munich: 1.33
Odd of draw: 3.25
Odd of victory Borrussia Dortmund: 6.5
Get the team names directly from the game object, don't hardcode them
(except for "draw").
4. Bonus: Create an object called 'scorers' which contains the names of the
players who scored as properties, and the number of goals as the value. In this
game, it will look like this:
{
Gnarby: 1,
Hummels: 1,
Lewandowski: 2
}

dataStructures modernOperators and strings - challenge 3: <p>
Write a program that receives a list of variable names written in underscore_case
and convert them to camelCase.<p>

The input will come from a textarea inserted into the DOM (see code below to
insert the elements), and conversion will happen when the button is pressed.<p>

Test data (pasted to textarea, including spaces): <p>
   underscore_case
     first_name
    Some_Variable
    calculate_AGE
  delayed_departure
  
Should produce this output (5 separate console.log outputs): <p>
underscoreCase ✅
firstName ✅✅
someVariable ✅✅✅
calculateAge ✅✅✅✅
delayedDeparture ✅✅✅✅✅

