# Mojito
Mojito is a simple, monophonic, subtractive synthesizer with effects that is capable of generating a wide range of sounds. It models a classic analog synthesizer and features a low-aliasing oscillator and a 24 dB filter emulation. Mojito can generate killer bass sounds, lead sounds, and special effects.

![Mojito](Images/Mojito_584x198.png)

### Interface
Mojito is organized into Oscillator (OSC), Amplifier (AMP), Filter (FLT), and FX sections, with easy-to-use, yet powerful controls.

### Oscillator
Mojito’s Oscillator section is on the upper left of the plug-in window. Here you can set up the harmonic content of the sound source. The basic controls are the three large knobs on top: Pitch, Wave, and Width.

  * **Pitch** Adjusts the frequency from one octave below to one octave above the played note. Note that this affects the cutoff frequency only via key tracking. Pitch is modified by the pitch-bend wheel (± 2 semitones).
  * **Wave** Selects between a sawtooth wave and a pulse wave. These two waveforms have a rich and regular harmonic content, making them classic sources for subtractive synthesis. Sawtooth waves contain the fundamental and all harmonics whereas pulse waves have only the fundamental and odd harmonics. Mixed settings effectively adjust the level of the even harmonics.
  * **Width** Adjusts the pulse width of the pulse wave from almost zero to square. This adjusts the balance between the fundamental and the higher and lower harmonics.  

Below the three main OSC controls is a smaller row of knobs that adjust how much the oscillator settings are modulated. The speed of the modulation is adjusted using the LFO Speed controls, located to the right of these knobs. The LFO can be synced to tempo or it can oscillate with a freely adjustable period. Use the modulators to create chorus-like or string-like sounds, vibrato, and other familiar modulated sounds.

There is also a Sub Oscillator knob, which can be adjusted from 0 to 100% to add more low frequency content to the sound.

The Portamento section lets you control pitch slewing between notes. Using the mode selector, you can choose between three modes:

  * **Off** A note that is played while another note is playing silences the previous note and trigger the new one.
  * **Legato** An overlapped note does not trigger a new envelope but the pitch slowly changes to the pitch of the new note.
  * **Retrigger** An overlapped note retriggers the current envelope, starting at its volume at the moment it is retriggered. This also slowly changes the note’s pitch. Note velocity is not applied or updated for overlapped notes.  

The Time knob adjusts the glide speed (that is, the duration of the pitch change) when using portamento. The range is from 5 ms to 1 s.

### Amplifier
Below the Oscillator section is the Amplifier section. This consists of a Gain control, which responds to MIDI Volume messages, and a Velocity-to-Volume control, which modulates the volume of a note in response to key velocity.

The most important part of this section is the ADSR envelope. (“ADSR” stands for “Attack, Decay, Sustain, Release.”) With these four sliders, you can adjust the amplitude characteristics over time. These characteristics play a huge role in defining the overall sound. The ADSR envelope can control the volume of a played note and can also control the filter cutoff.

  * **A** Adjust the attack time, which is the time required for the sound’s amplitude to go from zero (silence) to full amplitude. The range is from 2 to 500 ms.
  * **D** Adjusts the decay time, which is the time required to drop from full amplitude to the sustain level. The range is from 2 ms to 1 s.
  * **S** Adjusts the sustain level, which is the level that is held from the end of the decay until the key is released. The range is from -96 dB (silence) to 0 dB (full amplitude).
  * **R** Adjusts the release time, which is the time required to fall back to silence after the key is released. The range is from 2 ms to 2 s.

### Filter
The section on top of the right side of Mojito only affects the resonant 24 dB low-pass filter.

  * **Reso** Controls the resonance of the filter, which is an amplification, or emphasis, of the signal at the cutoff frequency.
    * Note: If the amount of resonance of a filter is raised high enough, the filter begins oscillating at the cutoff frequency, thus generating its own waveform. Be careful: this can be loud!
  * **Drive** Controls the amount of filter drive from 0 to 100%.
  * **Cutoff Knob** Controls the corner, or cutoff, frequency, which is the point above which frequencies are attenuated. The range is from 20 Hz to 16 kHz.

The other controls affect the modulation of the cutoff frequency.

  * **Key** Controls how much the played note scales the cutoff frequency.
  * **Velo** Controls how much the velocity of the played note shifts the cutoff frequency up or down.
  * **Envelope** Controls how much the ADSR envelope shifts the cutoff frequency up or down.
  * **LFO** Controls the amount of shifting that the filter LFO applies to the cutoff frequency. The LFO can either be synced to tempo or it can oscillate with an adjustable period.

### FX
On the bottom right is a small effects section where you can apply a modulation effect to enliven or broaden the sound. Mod Depth controls the amount of this effect. Using Mod Color, you can adjust the timbre from a flanger-like to a chorus-like effect. The modulation utilizes an LFO that has the same speed as the filter LFO.

Finally, there is an Overdrive, the amount of which is controlled by the Drive control.
