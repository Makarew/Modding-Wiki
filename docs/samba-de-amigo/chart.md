# Amigo de Mapeo

Amigo de Mapeo makes the charting process easier by providing a simple GUI for editing.

## Getting To Know The UI

The main UI of Amigo de Mapeo is divided into three sections: Song Info, Playback, and Editing

### Song Info

The Song Info section of the UI is found along in the lower right corner. This section will get everything else ready for charting.

Here's what everything in Song Info does:

* BPM - The beats per minute of the song. Make sure this is accurate to ensure notes line up.
* Resolution - The amount of subdivisions per measure. A high value is recommended.
* New - Start a new project.
* Load - Load a saved project.
* Save - Save the current project.
* Difficulties - Select the difficulty to edit. Toggle the checkbox to enable/disable the difficulty.
* Title - The title of the song.

### Playback

The Playback section of the UI wraps around the screen from the left side, along the top, and to the right side, above the Song Info Section. This section lets you view where you are in the song, along with fast and precise control to move where you are in the song.

Here's what everything in Playback does:

* Spectrum - On the left side, the spectrum shows you how strong frequencies are. Low frequencies are at the top, and high frequencies are at the bottom.
* Waveform - On the top, shows a complete waveform of the song. The red line shows where you are in the song. Click and drag the red line to quickly scrub through the song.
* Duration - On the right, below the waveform. Shows the total duration of the song, along with the current time of where you are in the song.
* Play/Pause - Below duration, allows you to play and pause playback.
* Measure - Below Play/Pause. Functions the same as duration, but displays in measure and resolution. The measure is on the left of the ```.```, and the resolution is on the right.
* Measure Adjust - Below measure, allows you to scrub through the song by measures.
* Resolution Adjust - Below measure adjust. Similar to measure adjust, but using resolution.

### Editing

The Editing section of the UI in the center allows you to actually create your chart. The Editing section has two modes: Placement and Modifying.

#### Placement

When one of the notes in the bottom left of the section is highlighted after clicking it, you'll enter Placement mode. You can now click in one of the six note circles to place the selected note type at that position at the current measure and resolution. To exit Placement mode, click any empty space.

#### Modifying

If none of the notes in the bottom left of the section is highlighted, you're in Modifying mode. In this mode, you can right click a note to delete it, or you can click on any notes in the chart to bring up a new menu. Each note type will have a different menu that comes up, but all of the will feature a ```Measure``` and ```Resolution``` section. Using the buttons, or typing a value will change that note to be played at that time.

##### NORM Note/Blue + HAPP Note/Happening

The NORM and HAPP notes feature no additional values.

##### MASH Note/Red

The MASH note includes one additional value called length. Changing this value changes how long the note needs to be held.

##### SLID Note/Slide

The SLID note has additional values for Wait, Speed, and Pattern.

* Wait - How long from the note spawning until the note starts moving.
* Speed - How fast the slide moves.
* Pattern - How the pattern moves. Select this from the list of images.