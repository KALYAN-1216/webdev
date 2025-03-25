About the code :
HTML Structure: The webpage consists of a two-column grid layout using <div class="container">. The left side displays an image, while the right side contains interactive components like a clock and calendar.

CSS Grid & Styling: The layout is managed with CSS Grid, setting grid-template-columns: 1fr 1fr;. The elements have rounded corners, background colors, and padding for a modern look. Tabs and buttons have hover effects for better UI interaction.

Tab Functionality (JavaScript): The showStep(stepNumber) function toggles between the Clock and Calendar views by setting display: none/block for relevant sections.

Clock Implementation: Uses setInterval(updateClock, 1000); to update the time dynamically every second. The function fetches hours, minutes, and seconds, formatting them for display.

12-Hour Format: The clock converts 24-hour time to 12-hour format, ensuring a familiar AM/PM format.

Calendar Generation: The script dynamically generates the calendar grid using generateCalendar(), setting the current month and year.

Navigation for Months: prevMonth and nextMonth buttons update the month dynamically, allowing users to browse past and future months.

Highlighting Today’s Date: The current date is highlighted using .today class styling, making it visually distinct.

Empty Grid Spaces: The calendar adjusts the first day’s position correctly by adding empty <div> elements for proper alignment.

Event Listeners: The script attaches click listeners to tabs and buttons to toggle views and navigate months dynamically.
