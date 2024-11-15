# color-bars-game



This HTML code creates a simple bar animation with "Start," "Stop," and "Reset" buttons for interactive control. The animation randomly changes the height of each bar every 500 milliseconds once "Start" is clicked, creating a dynamic visual effect.

Here's a breakdown of the code:

HTML Structure:

A <div class="container"> holds five .bar elements, each with different colors and initial heights.
A <div class="buttons"> contains the control buttons: "Start," "Stop," and "Reset."
CSS Styling:

.container sets the bars within a black background.
Each .bar is styled with a different background color and has a smooth height transition.
JavaScript Animation:

The startAnimation function initiates an interval that adjusts the height of each bar randomly between 50px and 250px.
The stopAnimation function halts the animation interval.
The resetAnimation function resets each bar to its initial height.
This setup allows you to visualize bars dynamically adjusting their height in response to button clicks.
