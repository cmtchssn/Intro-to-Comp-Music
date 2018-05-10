# The Grid
The Arrangement grid is comprised of the ticks in the timeline and the vertical lines extending from those ticks through the background of the Arrangement. This grid uses the Timebase setting as the basis for its display. The Timebase settings are Seconds, Samples, Bars, and Frames, and they determine the behavior of Event and tool snapping. The Timebase can be changed at any time, without directly affecting the arrangement.

Perhaps the most common Timebase setting is Bars, which display time in a musical format of bars and beats. With this Timebase setting, the grid is determined by the settings in the Quantize panel.

### Quantize Panel

![Quantize Panel](Images/QuantizePanel_633x25.png)

The Quantize panel can be opened from the toolbar by clicking on the Quantize Panel button, or by selecting Quantize from the View/Additional Views menu. The Quantize panel can be detached and freely placed on the screen. In this panel, you can edit all settings related to the Quantize grid that are displayed in the Arrangement. From left to right in the panel, you can see areas for Grid or Groove mode; note-value selection; note grouping and Swing amount; Start, End, Velocity, and Range percentages; and preset management.

### Rhythmic Values

With Grid mode selected, you can choose a note value between whole notes and 64th notes, and the following musical note groupings: Straight (with a Swing percentage setting), Triplet (3 notes in the space of 2), Quintole (a quintuplet with 5 notes in the space of 4), or Septole (a septuplet with 7 notes in the space of 8). These settings also determine the look and behavior of the grid in the Arrange view. For information on the Groove mode of the Quantize panel, refer to the Groove Extraction and Quantize section.

### Swing

Swing is a rhythmic style you can apply, in which off-beats are moved forward in time relative to on-beat notes, creating a relaxed, bouncy feel. This offset is calculated based on the currently selected Quantize value. For example, at 100% Swing, with 16th-note quantize selected, a pattern of 16th notes play at a 2:1 ratio; On-beat notes play on beat, and offbeats play as though they were the final 16th-note triplet in a group of three. You can set the amount of swing between 0% (straight timing) and 100% (fully swung).

### Quantize Note Starts

The Start percentage defaults to 100%, which means that the start of a selected note, Event, or transient snaps to the grid if quantized. This is effectively a quantize-strength parameter, where anything less than 100% moves the note, Event, or transient a relative amount closer to the grid, instead of all the way to the grid.

### Quantize Note Ends

The End percentage only affects notes in Instrument Parts. The function is similar to the Start percentage, except that it affects the note end, effectively making quantized notes shorter or longer. The Velocity percentage also only affects notes, and adjusts note velocity according to an extracted groove if the Quantize mode is set to Groove.

### Velocity Sensitivity

The Velocity percentage lets you tie Quantize strength to note velocity, to the degree that you specify.

### Quantize Range

The Range percentage sets the relative range from grid lines within which notes, Events, or transients are quantized. Notes, Events, or transients beyond this relative range are not quantized. As there is no display indicating the Range, quantizing several times while adjusting this setting may lead to the best results.

The presets area of the Quantize panel allows you to quickly switch between up to five Quantize panel settings, so that working with multiple complex quantization setups is very easy. You can also store and recall Quantize panel settings, just as you would store an effect or instrument preset.

---

*Text and images reproduced from the official Studio One Version 3.3.0 Reference Manual*  
*Copyright © 2016 PreSonus Audio Electronics, Inc*
