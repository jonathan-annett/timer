# Presentation Timer

Single Monitor Mode
---

option 1 - view [online version](https://jonathan-annett.github.io/timer/timer.html) - runs in browser ( if unavailable, try the [alternate site](https://timer.1mb.site) )

   * drag browser window to appropriate monitor and press S to enter Single Monitor Mode
  
option 2 - Download and install windows [setup](Setup.exe) - runs as standalone app (deployed as a full screen nw.js app)  

   * starts full screen on your default montitor
   * press S to enter Single Monitor Mode


The main idea behind this mode is to quickly get a countdown running, without having to have multiple monitors running.
Since it's intended to directly drive a countdown display, minimal information (ie clutter) is show, and it's intended you drive it using the keyboard or mouse.


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

the Space bar will always reset the timer to it's current default value.
you can change the default value by typing in a new duration in whole minutes, and pressing Enter
you can also ignore the default value entirely, and type in a duration in whole minutes, and then pressing Space

there are a number of live adjustments that can be made using the arrow keys, which are explained on the timer screen itself

remember that if you hold down the control key, all adjustments made with the arrow keys are for 1 minute, instead of the default 1 second nudge that can be applied to a running timer. The main purpose of these adjustments is to fine tune the end time, if you have a "hard out". you can also however correct for starting a timer a few seconds late, or (if needed, you can pre-empt a future countdown that you wish to start at a specific time, by nudging the start time into the future, which will give a preview-countdown to the actual countdown.

Mouse Operation (Preset button mode)
---
if you prefer to use your mouse, drag the mouse to the top of the screen, and select a preset duration to immediately start the timer using that duration

Updating the preset buttons

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



