# Presentation Timer

Single Monitor Mode
---

option 1 - view [online version](https://jonathan-annett.github.io/timer/timer.html) - runs in browser ( if unavailable, try the [alternate site](https://timer.1mb.site) )

   * drag browser window to appropriate monitor and press S to enter Single Monitor Mode
  
option 2 - Download and install windows [setup](https://jonathan-annett.github.io/timer/Setup.exe) - runs as standalone app (deployed as a full screen nw.js app)  

   * starts full screen on your default montitor
   * press S to enter Single Monitor Mode

The main idea behind this mode is to quickly get a countdown running, without having to have multiple monitors running.
Since it's intended to directly drive a countdown display, minimal information (ie clutter) is show, and it's intended you drive it using the keyboard or mouse. 

while in this mode, press the "P" key will switch between single monitor mode and control screen mode, and moving the mouse to the top of the display will reveal the preset and helper buttons.


Dual Monitor Mode
---

option 1 - view [online version](https://jonathan-annett.github.io/timer/timer.html) - runs in browser

   * drag browser window to appropriate monitor 
   * open the remote display window by clicking the link in the lower left hand corner
   * drag the remote window to the approprate monitor, and resize as needed  (or just press F to make it full screen )
   * click on the original browser window, and press F to make that fullscreen (if needed) 
  
option 2 - run the windows app (see above) 

   * starts full screen on your default montitor
   * open the remote display window by clicking the link in the lower left hand corner
   * drag the remote window to the approprate monitor, and resize as needed  (or just press F to make it full screen )
   * click back on the fullscreen app, as it needs to have focus in order to control the timer.


Keyboard operation
---

The space bar will always start the timer using currently displayed duration value.

You can change the default value by typing in a new duration in whole minutes, and pressing Enter.

You can also ignore the default value entirely, and type in a duration in whole minutes, and then press Space to immediately start a new timer.

There are a number of live adjustments that can be made using the arrow keys, which are explained on the timer screen itself.

Remember that if you hold down the control key, all adjustments made with the arrow keys are for 1 minute, instead of the default 1 second nudge that can be applied to a running timer. The main purpose of these adjustments is to fine tune the end time, if you have a "hard out". 

you can also however correct for starting a timer a few seconds late, or you can pre-empt a future countdown that you wish to start at a specific time, by nudging the start time into the future, which will give a preview-countdown to the actual countdown.

Progress Bar Graph
---
pressing B will toggle a progress bar display under the countdown timer

Time of day display
---

Pressing T will toggle the time of day display


Pause Mode
---

pressing " (otherwise know as double quote - usually requires shift) will toggle pause mode 

while paused, the main display freezes and the end time will be advanced - since pausing the timer means it will finish later.

note that pressing the space bar while paused will restart the timer, consistent with the idea that pressing the space bar always starts the timer.

if you have paused the display, the acumulated time spent whilst paused is displayed below the total time display - and you can clear this number by pressing the single quote key ('), this has the effect of completely undoing the pause, and forcing the timer to complete at it's expected end time.



Mouse Operation (Preset button mode)
---
if you prefer to use your mouse, move the mouse to the top of the screen, and select a preset duration to immediately start the timer using that duration

Updating the preset buttons
---

to update a preset button, you can type in a new duration, press enter (making it the current default), then press one of the preset buttons while holding down the shift key.

Messages
---
Pressing the "M" key will toggle message mode

in message Mode, a 1 minute warning message is displayed above the countdown suggesting that it's time to wrap up. once the countdown reaches zero, a "time's up" message will be displayed.

Custom Messages
---

custom messages can be used to display a message above the current countdown timer

To edit a custom message, Press the "C" key, and type in your message, folowed by the Enter key

Pressing "C" again will remove the custom message.

Custom Styling
---

If you're a web developer, and understand how to edit CSS files, you can customize the display locally (changes are saved to the local pc)

to bring up the editor, press Ctrl-S.

Pressing Ctrl-S again will close the editor

Note: if you mess things up, the default styling can be restored by using Shift-Ctrl-S

Full list of keyboard commands
===

**keys for any screen**
* ```F``` Toggle full screen mode for the currently focussed window
* ```Escape``` Exit full screen mode in the current window
* ```T``` Toggle the display of the current time on all screens
* ```B``` Toggle the display of the progress bar on all screens

**keys for the control window, or single monitor mode window**
* ```S``` Enter Single Monitor Mode. This is a full screen mode that looks like a remote display screen, but allows full control via the keyboard, using the same keyboard commands as the controller screen. you can also use the mouse for most functions, by moving the mouse up and revealing the buttons.
* ```P``` Toggles between the controller screen and the presenter view mode. presenter view is almost identical to single monitor mode. the only difference is that in presenter view mode, the mouse operation is disabled. note that pressing P when you are in single monitor mode will exit single monitor mode, and return you to controller mode. this basically means you can toggle between single monitor mode and controller mode, by pressing P and S.

* ```Space``` Restart the timer, using the duration displayed in the lower right hand corner of the screen. this will either be the default duration (it will be white), or one you have just entered using the number keys (in which case it will be green)

* ```0``` thru ```9``` use the number keys to enter a duration in minutes. whilst you can use the colon  ```:``` key to enter something like ```1``` ```:``` ```3``` ```0```, the timer will understand ```9``` ```0``` to mean the same thing. (it will display it in the long hand format, regardless of what you type)

* ```Enter``` will take the a duration you have just entered, and save it as the current default. (as opposed to ```Space```) which will immedately start a timer using that value
* ```.``` If you feel the need to enter less than 1 minute or a fractional minute duration, enter it as a decimal value, for example ```4``` ```.``` ```5``` will translate to 4 minutes and 30 seconds. whilst this may seem counter intuitive, this decision was made deliberately, as in most cases the timer will be used for multiples of minutes, and to avoid confusion, the colon ```:``` is always used to delineate hours and minutes. not to worry as you can still enter durations like ```1``` ```:``` ```3``` ```0``` ```.``` ```5``` which would be identical to entering ```9``` ```0``` ```.``` ```5``` (1 hour 30 minutes 30 seconds)
* ```"``` Pause/Resume the timer. the end time will automatically be updated in real time, indicating when the countdown will actually end, if you were to resume it immediately. you can do this to make the clock stop, and then restart when you have reached a desired future hard out time,
* ```'``` if you've previously paused the timer, or are currently pausing the timer, this will undo all pauses, reverting to the original duration you selected, and restore the countdown to the correct value.
