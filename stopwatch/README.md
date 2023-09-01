Project Folder Structure:

Let’s build the project folder structure before we begin writing the code. We create a project folder called ‘Stopwatch’. Inside this folder, we have three files. These files are index.html, style.css, and script.js.



----------------------HTML---------------------

We begin with the HTML Code. First, create a file called – ‘index.html’.



-----------------------CSS----------------------

Next, we style our heading using CSS.



---------------------Javascript-----------------

Finally, we add functionality using Javascript. 

We begin by creating intial variables and creating references. In a stopwatch, the user can start, pause or reset the timer.

When a user clicks on the start button we clear any previous intervals and start calling the ‘displayTimer’ function at an interval of 10ms. The ‘displayTimer’ function is responsible for doing the calculations for milliseconds, seconds, minutes, and hours and then displaying the timer on UI.

When the user clicks on the pause timer we simply clear the interval. For the reset timer, we clear the interval and set the milliseconds, seconds, minutes, and hours to 0 and finally, we display the timer in our UI.