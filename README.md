# website-clock

LinkedIn- https://www.linkedin.com/in/website-himanshu-singh
GitHub- https://github.com/webHimanshusingh 


1 HTML:
The HTML file (index.html) sets up the basic structure of the webpage.
It includes a div element with the ID clock inside a container div for displaying the clock.
It links to the CSS file for styling and the JavaScript file for the clock functionality.
2 CSS:
The CSS file (styles.css) styles the body to center the clock on the page and gives it a dark background.
The clock-container class styles the container holding the clock, adding padding, a border, and a background color.
The hashtag#clock ID styles the clock text, setting the font size and color.
3 JavaScript:
The JavaScript file (script.js) defines the updateClock function, which updates the clock every second.
updateClock retrieves the current time, formats the hours, minutes, and seconds to always have two digits (using padStart), and sets the text content of the clock element.
setInterval (updateClock, 1000) calls updateClock every second to keep the clock updated.
updateClock() is called once initially to display the time immediately upon loading the page.
By copying these code snippets into their respective files, you can create a fully functional digital clock. Open index.html in a web browser to see the clock in action.
