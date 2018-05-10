# Arrange View Mouse Tools
The mouse tools allow direct interaction with Events, using the mouse. It is helpful to remember that actions done using the mouse tools can be undone at any time, so feel free to explore them. You can click the right mouse button in any open space in the Arrange or Edit views to open a list of mouse tools and editing commands. Choose the desired tool or command by clicking it with the left mouse button. You can also click the middle mouse button (or scroll wheel) to display an expanded list of tools to choose from, including all Paint tool shapes.

![Split Tool](Images/studio-one-arrange-view-split-tool.jpeg)

## Split Tool
Using the Split tool, single Events can be split into multiple Events. Click on the Split Tool button, or press [number 3] on the keyboard to select the Split tool.

With the Split tool selected, a vertical and horizontal line is drawn near the current mouse-cursor position. The vertical line indicates the exact time position of the Split tool, while the horizontal line underscores the Track on which the Event to be split resides. The Split tool is directly affected by the current Snap settings.

Click on any Event with the Split tool to split the Event at that position. By splitting a single Event, you create two Events that can be edited independently. If multiple Events are selected across multiple Tracks, the Split tool affects all of the selected Events in the same way.

It is also possible to split selected Events at the timeline cursor, without using the Split tool, by pressing [Alt]+[X] on the keyboard.

To temporarily switch to the Arrow tool while the Split tool is selected, hold [Alt].

#### Splitting Instrument Parts

Normally, if you split an Instrument Part at a point that falls within one or more notes, those notes are truncated at the split point, and no longer play in the newly created Part to the right of the split point. This can be an issue, especially when splitting up Parts in which some notes are held for long periods, such as pad and string passages.

For example, if you have a four-bar Part in which a chord is played and held throughout, splitting the Part in the middle leaves the Part to the left of the split point mostly untouched. However, the held notes are now missing from the newly created Part to the right of the split point.

To split an Instrument Part and split (rather than truncate) any notes that cross the split point, hold [Alt]/[Opt] while you make the split.

---

*Text reproduced from the official Studio One Version 3.3.0 Reference Manual*  
*Copyright © 2016 PreSonus Audio Electronics, Inc*
