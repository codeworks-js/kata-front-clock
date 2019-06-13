# Clock

Is it lunch time yet ? Do a clock to know it !

## Instructions

Transform the hands with js every second.

Use the css `rotate` to rotate the hands to the right time. Don't forget to apply a transition to smooth the ticks.

## Knowledge

* Change the origin of the rotation : `transform-origin`
* Run a function every `x` ms : `setTimeout(function, x)`
* Get time : `new Date()`

## Tips

Nothing huge, just try not to create multiple `Date`, 1 is enough.

To prevent the weird animation when the hand is straight up, you should either deactivate css animation and re-enable it later or keep the the number of turns the hand has done. The best solution should be little bit of both.
