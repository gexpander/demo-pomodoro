This demo uses GEX to drive NeoPixels. It is a Python implementation
of the [Pomodoro timer](https://en.wikipedia.org/wiki/Pomodoro_Technique).

The strip shows:
- a shortening red strip during the work phase
- dim orange/red when the user should start working
- dim green when the break can be started
- and a shortening green strip during the break phase

The end-of-phase wait states are left by pushing a button, entering the following
break or work period.
