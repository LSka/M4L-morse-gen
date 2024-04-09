# M4L-morse-gen
Max For Live MIDI Tool for Live 12 that generates MIDI clips based on Morse code

# Installation
Put anywhere in your Ableton search path (i. e. the User Folder or any other folder you added to "Places" in Live's browser).
You should now be able to see it in the "Generate" pane when selecting a MIDI clip.

# Usage
Type anything in the text field and notes will be generated in the clip. The clip length is automatically adjusted to the phrase length.

You can set the "Time unit", i. e. the length of the "dot" in Morse code (by conventions, "dot" is 1 unit long, "dash" is 3 units, "space" is 7 units; additionaly, separation between each dot or dash is 1 unit, and separation between letters is 3 units long).

By default every letter is associated with a specific MIDI note, so you can generate more interesting melodies or percussion patterns. You can change the assignments by clicking on the "Set Notes" button.

Notes can be changed individually or in bulk by setting the first note (corresponding to the letter "A", default is C1) and clicking on the "Set All" button.
If the "Scale Awareness" toggle is on, assigned notes will follow the general scale's intervals (Note: at the moment the first generated note using Scale Awareness will not always be the root note of the scale, but the note after the "first note" set in the device. I'll try to fix that in the next release).
