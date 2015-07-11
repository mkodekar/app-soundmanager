# Sound Manager 2.0 #

## What's New in Sound Manager 2.0 ##

Sound Manager version 2 incorporates some great new improvements in setting times for the volume to change. Instead of being limited to only one or two times a day, now you can set as many "schedules" as you like for each volume setting. Not only that, but you can also specify for which days of the week the schedules are active. Change volume at certain times for the work week, for example, and other times for your events on the weekend.

Version 2 also makes the notification volume stream available. This wasn't open to developers on the initial Android OS version, but with Android 1.5, also known as Cupcake, Google makes this open to developers. You can have different schedules for email and IM notifications, for example, than you have for the ringer volume.

(Sound Manager Version 2 should be released soon through the Android Market. Look for it in the next week or two.)

## How to Use ##

Slide your finger along any of the volume bars to change the volume.

Use the Menu to switch screens to set vibration settings or toggle the ringmode.

To treat the Notification volume as different than the Ringer volume, go to your home screen. Press Menu and choose Settings. Choose Sound & display from the menu. Then choose Ringer volume. Deselect the check box labeled "Use incoming call volume for notifications". Now the Ringer volume and Notification volume can be treated as completely separate volume settings in the Sound Manager.

To set a schedule:

  1. Press the Set Schedule button next to any of the volume settings.
  1. You will be presented with a list of current schedules. Perform a long-click on any schedules to toggle them to Active or Inactive, or to delete them.
  1. Press the Menu button to add a new schedule.
  1. Choose the time of day you want the volume to change.
  1. Use the slider bar to set the volume level you want it to change to.
  1. Vibrate is now in the same schedule with the volume. If a vibrate checkbox is visible, make sure it is checked or unchecked, depending on how you want it.
  1. Choose the days of the week you want the schedule to be active.
  1. Press the Back button. The schedule will be set.

# F.A.Q. #

**Q.** When I set the schedule, it changed by volume right away!

**A.** Please state that in the form of a question.

**Q.** Why did it change my current settings?

**A.** When you set a schedule for a time of day earlier than the current time the schedule will be activated immediately and set volume settings.

**Q.** What if I reboot my phone? Will the timers I set still work?

**A.** They will reinstall upon startup. If you missed one of your timers, it should go off right when you start up.

**Q.** How come when I change my Ringer volume it also had changes my Notification volume?

**A.** By default, Android treats the Ringer and Notification sounds as one audio stream. When you change ringer, it automatically changes the notification volume. To change this, go to your home screen, press Menu and choose Settings. Choose Sound & display. Then choose Ringer volume. Deselect the check box labeled "Use incoming call volume for notifications". Now Sound Manager is able to treat the two volumes as completely separate. This can be extremely helpful if, like me, you want to turn down email and IM sounds (like at night, when you want to sleep) but want to keep the ringer volume up in case someone needs to call you.

**Q.** I changed the ringer volume and then the notification and system volume also changed. What happened?

**A.** This will only happen if you had the Ringmode set. For example, if the Ringmode is set to Silent the ringer, system, and notification volumes will be at 0. If you raise the ringer volume we know that you actually want to hear the phone ring, which won't happen if the Ringmode is still set at Silent. So we change the Ringmode to Normal, which means depending on your settings that it may ring and/or it may vibrate. Doing this returns your System Volume and Notification Volume to their previous values.

**Q.** I had the window open when the volume changed, but the volume controls in the app didn't reflect the change. Why not?

**A.** To reset the volume sliders, just exit out of the app and return.

**Q.** I set my ringmode to 'Vibrate Only', but I returned later to see that it is set to 'Silent', why is that?

**A.** The Vibrate Settings and the Ringmode Toggle can interfere with each other sometimes. If you set the ringmode to 'Vibrate Only', but then went and switched the Ringer Vibration Setting to 'Vibration Off', then the ringmode you chose is no longer valid and should actually be 'Silent'.

**Q.** Why have my schedules not triggered since I updated?

**A.** After an update the Operating System may disable the schedules that were in place. A reboot of the phone will quickly reenable them.

**Q.** I muted my phone, but later the volume raised? What's going on?

**A.** The Mute button is a great feature, but it doesn't supersede the timers you set for your volume controls. If you mute your phone, but a timer you set raises the volume, then the volume will be raised.

**Q.** Help! I created a shortcut to my mute activity, but the shortcut does nothing!

**A.** The shortcut doesn't display anything, but it does toggle your mute status. If you press it once, it mutes your phone. If you press it a second time, the volume levels are returned to what they were when you muted the phone (even if you've changed the volume in the meantime).

**Q.** How can I turn off the camera shutter sound?

**A.** The camera shutter sound seems to be controlled by the System Volume. Turn down that volume and the camera shutter should be silent.