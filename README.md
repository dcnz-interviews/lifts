# Lifts
Lifts / Elevators are one of the main reasons we are capable of having multistorey buildings within many cities and residential areas. Without them we would have to walk up and down countless stairs every day or have designed our buildings to be only a few stories high. Meaning we save much more space and effort by having them around. Not to mention small children, the elderly and differently abled people benefit greatly from something so simple. 
<br />
For this challenge we'd like you to design and implement a simple lift system. A lift would be your entity and a controller (Button panel next to the lift) would be the client calling the server to calculate which lift needs to come down or go up to it. There could be multiple lifts in a building and a single controller on each floor. 
<br />
<br />
<b>Optional</b> - Unit tests to randomize the input.
<br />
<b>Mandatory</b> - Swagger UI

## Getting started
Create yourself a github account if you don't have one already. 
<br />
Create a new repository called Lifts.
<br />
Fork from this repository and start using your new repo.

## Part 1
Using .NET Core create an API that takes in the controller's floor position and server side logic that does the calculations and returns the selected lift in the following model:
<br />
{
    <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"lift": {
        <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    "number": int,
        <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    "floor": int,
        <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    "dateTime": dateTime
        <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
    <br />
}

## Part 2
Some tweaks need to be made to ensure the following:
<br />
1.) Lifts that are currently busy aren't selected (Thread.Sleep on the moving ones is fine and they move at 5 seconds per floor).
<br />
2.)  We need to be a bit greener, so lifts above the level of the controller need to be prioritised.
<br />
Output stays the same where relevant
<br />
<br />
Once you've completed the questions please respond back to the recruiter with a link to your repository.


