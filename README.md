In this HTML page, we first create a heading and a button to display the current date and time. The button has an onclick attribute that calls the displayDateTime() function when it is clicked.

Inside the displayDateTime() function, we create a new Date object to get the current date and time. We then use document.getElementById() to select the <p> element with an id of "datetime". Finally, we set the innerHTML of this element to display the current date and time using template literals.

When the user clicks the "Get Date and Time" button, the displayDateTime() function is called and the current date and time is displayed below the button.
