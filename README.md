# stop_watch
# The provided code is for a simple stopwatch application implemented using HTML, CSS, and JavaScript
# In HTML
This HTML file sets up the basic structure of the webpage.
It includes a reference to an external CSS file (style.css) for styling.
Inside the <body>, there's a <div> with the class "stopwatch" that contains:
A <div> with the class "time" and the id "display" for displaying the stopwatch time. It starts with "00:00:00".
Two buttons: "Start/Stop" with the id "startStop" and "Reset" with the id "reset".
At the end of the <body>, there's a reference to an external JavaScript file (script.js) for adding functionality to the stopwatch.

# In CSS
This CSS file defines the styling for the stopwatch and its elements.
It sets the font family, alignment, and sizes for text and buttons.

# In JavaScript
The  start Button,stop button and reset Button elements are accessed using document.getElementById().
Three functions are defined:
start: It starts a timer when "Start" is pressed and stops. it when "Stop" is pressed.
stop: when "Stop" is pressed, it stops the timer,
reset: Resets the stopwatch to "00:00:00" and stops the timer.
Event listeners are added to the "Start/Stop" and "Reset" buttons to trigger the corresponding functions.
Finally, the reset() function is called to set the initial state of the stopwatch.
