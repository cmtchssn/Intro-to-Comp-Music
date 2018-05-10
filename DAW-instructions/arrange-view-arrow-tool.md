# Arrange View Mouse Tools
The mouse tools allow direct interaction with Events, using the mouse. It is helpful to remember that actions done using the mouse tools can be undone at any time, so feel free to explore them. You can click the right mouse button in any open space in the Arrange or Edit views to open a list of mouse tools and editing commands. Choose the desired tool or command by clicking it with the left mouse button. You can also click the middle mouse button (or scroll wheel) to display an expanded list of tools to choose from, including all Paint tool shapes.

![Arrow Tool](Images/studio-one-arrange-view-arrow-tool.jpeg)

## Arrow Tool
This tool is selected by default. Click on the Arrow tool button or press [1] on the keyboard to select the Arrow tool. The Arrow tool can be used for the following purposes:

#### Move an Event

To move an Event using the Arrow tool, click anywhere on the Event and drag left, right, up, or down. Dragging the Event left or right moves the Event backward and forward in time, relative to the current Timebase and Timeline zoom. When dragging an Event left or right beyond the viewable arrangement, hold [Space Bar] on the keyboard to speed up the scrolling.

Dragging the Event up or down moves the Event to another existing Track of the same type. If the Event is dragged to a position where no Track currently exists, Studio One creates a new Track of the same type.

When dragging an Event from one Track to another (up or down), the position of the Event is constrained within an automatic snapping range to make it easy to keep the Event at the same time position. To defeat this snapping, hold Shift while dragging the Event up or down.

#### Size an Event

Events can be thought of as windows into audio files and musical performances, where what you see is what you hear. Sizing is a fundamental technique wherein Events are made shorter or longer, so that only a portion of the audio or musical data they contain is seen and heard. To size any Event using the Arrow tool, float the mouse to the left or right edge of the Event to reveal the Sizing tool. When this tool appears, click-and-drag left or right to size the Event. Events can be sized and resized nondestructively any number of times.

Two adjacent Events can be sized simultaneously so that no gap is created between them. To do this, float the Arrow tool to the bottom of where the two Events meet in the Timeline, where you can see the sizing icon with both left and right arrows illuminated, and then click-and-drag left or right.

Holding [Alt]/[Option] on the keyboard and then sizing an Event from the right edge results in the Event being freely timestretched. Refer to the Timestretching section of this chapter for more information.

#### Adjust Audio Event Volume Envelopes

All Audio Events feature a basic volume envelope that allows the volume of the audio to be shaped in several ways. Using the volume envelope, you can create a fade-in and fade-out, as well as set a constant volume level between the fades. The volume envelope applies gain changes to the audio clip in the Event and is therefore at the front end of the audio signal path.

To create a fade-in or fade-out, click-and-drag left or right on the Fade Flag in the upper left or right corner of an Audio Event. By default, a linear fade is created over the length you have moved the Fade Flag. Fade times, as well as Event gain, can also be edited in the Inspector for any selected Event.

To change the curve of the fade, click on the Fade Curve box in the middle of the fade curve and drag up or down. The fade curve determines how quickly or slowly the fade occurs and changes over time. If you press and hold [Shift] while editing the fade length or the curve, you can edit both at once. Dragging up or down edits the curve, and dragging left or right changes the length.

It is also possible to drag a complete crossfade left or right, or up or down, in order to change the location and characteristics of the fade. Float the mouse to the center of the crossfade until the Hand icon appears, then click and drag to adjust. Dragging left or right adjusts the location of the fade, extending or shortening the crossfaded Events. Dragging up or down alters the shape of the crossfade.

To adjust the overall volume level of an Audio Event, click on the volume box in the center of the volume envelope and drag up or down. As you adjust the volume envelope, the audio waveform is redrawn to approximate the effect of the adjustment.

#### Select Multiple Events

Multiple Events can be selected in order to edit them all at once, with a single action. To select multiple Events with the Arrow tool, do one of the following:

Click outside of the range of an Event, and then drag over any other Events; a gray box is drawn while you drag over the target-selection area. Release the mouse button once the box is drawn over all of the Events you wish to edit, and these Events are selected for editing.
Click on any Event, then while holding [Shift] on the keyboard, click on any other Events to select them. This allows you to select multiple Events that are not in close proximity to each other. All selected Events can then be edited at once.
Click on any Event, then or , to select all Events on between the start of the Song the current Event.
Click on any Event, then
Double-click on the timeline of a Track in the Arrange or Edit view while holding [Shift], to select all Events present on that Track.
Normally, when you select multiple Events and adjust volume or fade in/out shape on one of them, all selected Events change to match the new setting. If you want to adjust an individual Event without losing your selection, hold [Alt] while making your changes.

#### Alternate Arrow Tool Uses

For speed and efficiency when editing, a selection of modifier keys can be applied while the Arrow tool is selected, giving temporary access to the following alternate tools and editing modes:

  * Range Tool Hold [Ctrl]/[Cmd].
  * Slip Editing Hold [Ctrl]/[Cmd]+[Alt] while floating the Arrow tool over an Event.
  * Define Tempo Hold [Ctrl]+[Alt]/[Command]+[Option] while floating the Arrow tool over the edge of an Event.

---

*Text reproduced from the official Studio One Version 3.3.0 Reference Manual*  
*Copyright © 2016 PreSonus Audio Electronics, Inc*
