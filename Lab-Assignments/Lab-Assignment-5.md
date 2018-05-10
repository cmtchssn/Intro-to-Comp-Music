# Lab Assignment 5
## Basic MIDI Recording

---

#### Prerequisites
Content from all previous lab assignments

[The Grid](DAW-instructions/the-grid.md) in the Studio One Reference Manual

Recommended - review the following sections in the Studio One Reference Manual:
  * [Loops Tab](DAW-instructions/loops-tab.md)
  * [Browsing for Instruments](DAW-instructions/browsing-for-instruments.md) (in Instruments and Audio Effects)
  * All Built-In Virtual Instruments - especially [Mojito](DAW-instructions/mojito.md) and Mai Tai
  * [Metronome Control](DAW-instructions/metronome-control.md)

Optional - [Set Up MIDI Keyboards](DAW-instructions/setup-midi-keyboards.md) in the Studio One Reference Manual
*Our MIDI controllers in the lab have already been properly set up. However, they occasionally need to be reconfigured.
This section of the manual is crucial to ensure that you know how to configure MIDI devices in Studio One, both at home and in the lab.*

---

#### Objectives:
  * Basic MIDI recording and quantizing
  * Working with Virtual Instrument presets

---

1. Open your DAW, create a new song/project with the title "YourFirstNameYourLastName-Lab5". If prompted, use the following settings:
  * Sample Rate - 44.1kHz
  * Resolution - 16 bit
  * Tempo - will be changed later
2. Open the [Loops](DAW-instructions/loops-tab.md) tab of the Browser panel on the right side of the window. Find a drum loop that you like and change your song tempo to match the tempo of the loop - the selected loop's tempo is listed at the bottom of the loop tab. Drag your loop onto a new track in the Arrange window.
3. Open the [Instruments](DAW-instructions/browsing-for-instruments.md) tab of the Browser panel. Drag an instance of the [Mojito](DAW-instructions/mojito.md) instrument onto a new track in the Arrange window. Ensure that your MIDI keyboard is working - press a few keys and you should hear a sound. If you do not, see me to make sure that your MIDI keyboard is set up correctly. Choose a bass preset sound from the preset dropdown menu in the software instrument’s window.
4. Play along with your drum loop a few times to come up with a bass line. Once you have something you want to record, turn your attention to the [Metronome](DAW-instructions/metronome-control.md). Set a Metronome Precount for 2 bars - this means that when you hit record, you will hear 2 bars of clicks (8 beats) before the recording actually starts.
5. Record!
  * Arm the record enable button by the track name of your Mojito track. This will not be visible if you have automation showing.
  * Skip the playhead to the beginning of your song.
  * Click the record button in the transport bar. You should start hearing the metronome counting down - remember, it will give you 2 full measures (8 clicks) before it actually starts recording.
  * Play along with the drum loop like before - you’re now recording MIDI.
6. You probably didn’t play the part perfectly. Double-click on the newly recorded MIDI region to open the piano roll editor at the bottom of the screen. Snap the notes onto [The Grid](DAW-instructions/the-grid.md) using an operation called “Quantization”. Make sure that "Auto Quantization" is turned on via the AQ button. Select all of the MIDI notes in the piano roll with [Ctrl+A] on Windows or [Command+A] on Mac and select a value from the quantize dropdown menu. You might have to try a couple of different values - start with 1/8 and listen to see if that worked. If it did, your bass part should be perfectly in time  with the drum loop. If it didn’t, try 1/4 or 1/16.
6. When you are finished, submit your project using the procedure in the [Basic Submission Instructions](DAW-instructions/basic-submission-instructions.md#submitting-a-project) document.
7. As always, save a backup copy on your personal storage media.
