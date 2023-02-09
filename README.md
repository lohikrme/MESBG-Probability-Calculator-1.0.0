Hello! This is my MESBG Probability Calculator version 1.0.0.

Last updated: 10/2/2023

All rights reserved. For personal use only.

I believe this calculator will help lots of MESBG players to build better army lists, 
because it is simply impossible to calculate these calculations with
traditional methods (tens or even hundreds of loops of probability). 

I tried to make an easy to use GUI with sliders and buttons. I also used effort to make the GUI responsive.
For example in css I use a lot vw and vh to determine size instead of pixels.
The GUI is based on HTML and CSS, and the calculator and inputs are based on javascript.
I also wrote a python file where I explain more deeply about the mathematics. 

Users can give next inputs for the calculator:
Opponent A: dice-amount:int, F-value:int, elven-sword:bool
Opponent B: dice-amount:int, F-value:int, elven-sword:bool
The "Calculate" button activates JS-functions and completes the calculation based on these 6 inputs.

The inputs are received by inputs.js file. Inputs.js file send the data forward to calculator.js.
Calculator.js runs the data through complex functions and then changes the p-tags of the original HTML file.

So, have fun calculating stuff!

-lohikrme
