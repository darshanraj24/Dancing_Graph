# Dancing_Graph
Bar Graph Animation

The given code is an HTML document that creates a bar graph animation.
The startAnimation function is triggered when the Start button is clicked. It loops through all the bars and calls the animateBar function for each bar that doesn't have an active interval yet. The speed of the animation increases for each bar, with the first bar being the slowest and the last bar being the fastest.
The stopAnimation function is triggered when the Stop button is clicked. It loops through the intervals array and clears any active intervals using clearInterval. It also sets the corresponding interval entry to null
The resetAnimation function is triggered when the Reset button is clicked. It calls the stopAnimation function to clear any active intervals and then resets the height of all bars to 100%
Event listeners are attached to the Start, Stop, and Reset buttons to call the respective functions when clicked...
startAnimation function is called once outside of any event listener, so the animation starts automatically when the page loads.
