# JS-Day-19-A
Theme Clock


This code is an HTML, CSS, and JavaScript implementation of a clock that includes a toggle button to switch between light and dark mode.

The HTML code creates the basic structure of the web page and includes the following elements:

A button element with the class "toggle" for switching between light and dark mode

A div element with the class "clock-container" that contains the clock display and the time and date elements

A div element with the class "clock" that contains the clock needles and center point

Three div elements with the classes "hour", "minute", and "second" for the clock needles

A div element with the class "center-point" for the center point of the clock

Two div elements with the classes "time" and "date" for displaying the time and date respectively


The CSS code styles the HTML elements and includes the following:

A Google font called Heebo

A root variable for the primary and secondary colors used in the light and dark mode

Styles for the light and dark mode backgrounds and text colors
Styles for the toggle button

Styles for the clock and needles, including their position and color

Styles for the center point and its after-element

Styles for the time and date elements, including their font size and color


The JavaScript code adds interactivity to the web page and includes the following:

Selecting HTML elements using their class and storing them in variables

Creating an event listener for the toggle button that switches between the light and dark mode and updates the button text accordingly

Defining a function called setTime() that gets the current date and time, and updates the clock needles to match the current time. This function is called every second using the setInterval() method.