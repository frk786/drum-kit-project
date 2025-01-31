# Introduction:
For this project, we are going to create a simple website that displays the drum kits used in the vocalist band. The main purpose of creating this website is that when we create the drum kits it also plays the corresponding sound when you key press it.

As discussed in the previous dice-challenge project there are plenty of JavaScript features and elements used in here, which we are going to further breakdown.

# JS features used:
To select all the drums created in the HTML, we used;
       
       - document.querySelectorAll(".drum").length;

This allows you to execute custom code when a particular event (like a click, mouseover, keypress, etc.) happens on that element.

       - element.addEventListener(event, function, useCapture);

The purpose of a for loop in JavaScript is to repeatedly execute a block of code a specific number of times, based on a defined condition. It is used to iterate a loop and execute set of instruction until all drums are pressed.

       - for (var i=0 ; i<numberOfDrumButtons; i++)

# SWITCH statement:
The switch statement in JavaScript is used to evaluate an expression and execute different blocks of code based on the value of that expression. It provides a more efficient and readable way to handle multiple conditions compared to using a series of if...else statements.

For our project, it is used here to represent each drun-kit sound separately. 

 - Syntax

       - switch (expression) {
        case value1:
        // Block of code to be executed if the expression === value1
        break;
       case value2:
       // Block of code to be executed if the expression === value2
       break;
       case value3:
       // Block of code to be executed if the expression === value3
       break;
       default:
       // Block of code to be executed if none of the above cases match
       }


# Other KeyWords Used:
- this        ....          Its purpose is to give you a way to access the object that is currently executing the code, allowing you to interact with properties and methods of that object.
- play();     ....          This command in JavaScript is commonly used with audio and video elements to start or resume playback of media files (like an audio or video file) on a webpage.
- var         ....          The var keyword in JavaScript is used to declare a variable.

# Project Link:
[Drum-Kit Link](https://1drv.ms/u/c/291798b4f12915c1/ESCZT47zUoVCh0NgRVQ5ySgBP9IUyd8KcVvlI-UQDSt3dQ?e=cYkdsd)
