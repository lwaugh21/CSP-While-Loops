# CSP-While-Loops
Some practice with Javascript

var die1 = -1;
var die2 = -1;
var loopNum = 0; //use to count number of loops
var twelveCount = 0; //use to count 12's

while(loopNum < 1000){ 
  loopNum++;
  die1 = randomNumber(1, 6);
  die2 = randomNumber(1, 6);
  console.log("Rolled a " + die1 + " and a " + die2 + " for a total of " + (die1 + die2));
}
console.log("The number of times 12 was rolled was: " + twelveCount);
console.log("Done.");
