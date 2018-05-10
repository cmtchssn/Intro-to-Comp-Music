# Strip Silence
It is quite common that, as the result of continuous recording, some Audio Events may have gaps of silence or relatively low levels between performances. It may be helpful in these cases to remove the gaps and only keep the desired sections of the recorded Event. Studio One's Strip Silence function, controlled from the Strip Silence panel, is designed to handle this task.

Open the Strip Silence panel by clicking on the Strip Silence button in the toolbar, or select Strip Silence from the View/Additional Views menu. Select the Audio Events from which you wish to strip silence, make the desired settings, and then click on [Apply]. Click on the [Default] button to return all settings in the panel to their defaults.

The result of the Strip Silence process is similar to using a gate processor to only allow the desired signal to be heard, except that the Event is edited.

When the small light indicator next to the [Apply] button is lit, this means that changing the Detection or Event options and then clicking Apply automatically undos the previous operation, making it easier to find the right settings by viewing the result of the Strip Silence process, then tweaking the settings if needed without having to undo manually. Any change in selection (or other editing operation) ends this automatic state, and the indicator is no longer lit.

The following describes each setting:

**Detection** This determines how Studio One identifies silence in the areas you wish to process.

  * **Material** The first three options set the Open and Close Threshold for the gate algorithm automatically.
    * **Lots of Silence** Choose this for material that contains lots of silence and single hits—for instance, a clean, typical single-drum recording (hat, kick).
    * **Little Silence** Choose this for material that has some action going on but still has some silence—for instance, minimal techno/single drum loops, ride, or snare tracks.
    * **Noise Floor** Choose this for material where there is almost no real silence—for instance, noisy drum recordings, overheads, drum mixes, and drum loops.
    * **Manual** Allows the Open and Close Threshold to be manually edited.
  * **Open Threshold** Set between -80 and 0.00 dB.
  * **Threshold Link** Engage to link the Close Threshold to the Open Threshold.
  * **Close Threshold** Set between -80 and 0.00 dB.

**Events** This section determines the nature of the Events created after removing silence.

  * **Minimum Length** Determines the minimum length in seconds for any resulting Event.
  * **Pre-Roll** Determines the amount of time in seconds that should remain at the beginning of resulting Events from the time at which the previously detected silence ends.
  * **Post-Roll** Determines the amount of time in seconds that should remain at the end of resulting Events from the time at which newly detected silence begins.
  * **Fade-In** Determines the length in seconds of the linear fade-in applied to resulting Events.
  * **Fade-Out** Determines the length in seconds of the linear fade-out applied to resulting Events.
  * **Link** Enable this option to automatically set the Fade-In parameter to match the Pre-Roll setting, and the Fade-Out parameter to match the Post-Roll setting.

---

*Images reproduced from the official Studio One Version 3.3.0 Reference Manual*  
*Copyright © 2016 PreSonus Audio Electronics, Inc*
