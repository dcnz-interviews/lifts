# Lifts
Here at Datacom we work with all kinds of customer problems on a daily basis. 
<br />
These can range from search algorithms on shopping apps to complex scalable systems with multiple databases and integration points. 
<br />
For this challenge we don't want you to spend an entire week coding away. Please select the desired pattern, plan carefully and you'll find it to be easy.
<br />
Hopefully this sparks some of that passion we share for solving problems and future proofing for the next colleague that comes along. 
<br />
To complete this please fork from this git repository and treat each question as a feature branch, you can merge them back into main once you've completed each of them. 
<br />
Remember to add in some unit tests to randomize the input.

## Getting started
Create yourself a github account if you don't have one already. 
<br />
Create a new repository called Lifts.
<br />
Fork from this repository and start using your new repo.

## Question 1
There are multiple lifts in a building with a controller on each level of the building
The controller invokes an API and the server calculates the closest lift and notifies that lift to move to the selected floor.  
The following output needs to be displayed:

2022-04-11 21:21:00 - Button Pressed on Floor 3
<br />
2022-04-11 21:21:00 - Lift #2 selected on Floor 2
<br />
2022-04-11 21:21:00 – Lift #2 notified
<br />
2022-04-11 21:21:00 – Lift #2 arrived on Floor 3

## Question 2
Some tweaks need to be made to ensure the following:
<br />
1.) Lifts that are currently busy aren't notified and selected (Thread.Sleep is fine).
<br />
2.)  We need to be a bit more green so lifts above the level of the controller need to be prioritised.
<br />
Output stays the same where relevant

## Support
TODO
