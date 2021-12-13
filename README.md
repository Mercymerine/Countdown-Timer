# Event Countdown Timer

![This image shows Event Countdown Timer project](preview/javascript-countdown-timer-768x576.png)

# What You Should See

Visit the hosted github page to see this [](JavaScript Countdown Timer) in action.

# Project Objective
The project creates a JavaScript countdown timer. This timer takes a given day and returns the days, hours, minutes, and seconds.

# JavaScript Used
* JavaScript Date() Object
* Window.setInterval() method
* JavaScript CSS Selectors
* JavaScript Math.floor()

# Project description
The original project only created an output for the countdown time

But, I figured I'd make the project marginally better by at least displaying the day that was used for the countdown.

So, in the top of the page you'll see the fixed date that the timer is actually using.

You could probably make the project much better if you code up a way to actually have your user input the time and then recalculate the countdown timer each time.

I chose not to do this because I wanted to quickly get to the next project.

# New Things Learned or Refreshed
This project was pretty basic.

However, like each time, it made me realize that being a JavaScript programmer is more than just knowing the language.

You have to know how to use logic to use the language.

For example, it's easy to output a date using JavaScript onto your browser's screen with the `Date()` object, but if you didn't know how to extract the hour from your date using JavaScript you'd have to end up using an equation.

This project had to use a math equation to extract the days, `let days = Math.floor(distance / (1000 * 60 *60 * 24));` for example, because the days had to be calculated from difference in days in milliseconds.

JavaScript programming is logic + programming knowledge.
