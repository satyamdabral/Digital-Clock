# DIGITAL-CLOCK

This project demonstrates a basic digital clock using web technologies. It shows the hours, minutes, seconds, and session (AM/PM) on a web page.
The clock updates automatically to reflect the current time.

function displayTime() which will be responsible for updating the clock's display.

var dateTime = new Date() which represents the current date and time.

var hrs = dateTime.getHours();, var min = dateTime.getMinutes();, var sec = dateTime.getSeconds();
These lines extract the current hour, minute, and second from the dateTime object.

if (hrs >= 12)  The code checks if the time is 12 PM or later; if yes, it's PM (afternoon/evening), otherwise, it's AM (morning).

