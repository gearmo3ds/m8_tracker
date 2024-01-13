## General
| Action | Key |
|---|---|
|Navigate screens (bottom right SCPIT map)|SHIFT + ARROW|
|Insert Value|EDIT|
|Change Value|EDIT + ARROW|
|Reset Value|EDIT + OPTION in Instrument + setting views|
|Enter next free item slot| EDIT, EDIT
|Navigate to previous or next channel/instrument/table etc.|[OPTION]+[LEFT or RIGHT] |
|Navigate +/- 16 steps (in certain views)|[OPTION]+[UP or DOWN]|

## Selection & Copy / Paste
| Action | Key |
|---|---|
|Copy and paste single cursor selections | EDIT|
|Cut single cursor selections | EDIT + OPTION|
|Enter selection mask| SHIFT + OPTION|
|Select Row/Column/All/None| Press SHIFT + OPTION repeatedly|
|Copy selection | OPTION with active selection|
|Paste selection| SHIFT + EDIT|
|Move or rotate selection | EDIT + UP/DOWN ARROW|
|Clone selected items (make unique) | SHIFT + EDIT in selection mode|
|**Deep clone selected** chains in song view| SHIFT + EDIT, EDIT in selection mode|
|**Render selection to sample** in song view| EDIT, EDIT in selection mode|

## Play / Mute / Solo in song view
| Action | Key |
|---|---|
|Plays/stops all tracks.|[PLAY] |
|Cue the selected song row for playback. |[LEFT]+[PLAY]|
|Solo all tracks to the left or right side of the cursor’s position.|[OPTION]+[LEFT or RIGHT]|
|Mute current track (release option first to hold the mute).| [OPTION]+[SHIFT]|
|Solo current track (release option first to hold the solo).| [OPTION]+[PLAY]|
|Clear all mute and solos.| [OPTION]+[SHIFT]+[PLAY]|
|Toggle live (clip launch) mode|SHIFT + LEFT|
|Launch selected clip(s) in live mode|PLAY|
|Launch selected clip(s) at next bar in live mode|PLAY, PLAY|

Adjanced clips (chains) are looped.

When the row after the currently playing chain is empty ("--"), the play-head jumps to the beginning of the previous block.

Indepentent sections can be created by leaving an empty row between them.

## Phrase view editing
| Action | Key |
|---|---|
|Play current chain solo| PLAY|
|Continue song at chain position (non-solo) | SHIFT + PLAY|
|Preview selected row when playback is stopped|EDIT|
|In selection mode: Randomize the note value up or down, else navigates to the previous or nextphrase in the chain.|[OPTION]+[UP or DOWN]|
|In selection mode: Left to cycle note fill modes,right to randomize note and instrument triggers, else navigates to the previous or next track’s phrase. * When exiting selection mode after a fill action, perform a paste to undo.|[OPTION]+[LEFT or RIGHT] |
|Pastes the copy buffer that was copied in selection mode. In selection mode: with a series of rows and a single column highlighted: interpolate the selected range.|[SHIFT]+[EDIT]|
|On the instrument column or on a command value column where the command is the table or groove command (TBL or GRV): copy the contents of the selected data into a new number. (I.e.“clone”).|[SHIFT]+[OPTION, then EDIT]|
|Navigate to instrument in selected row |[SHIFT]+[LEFT or RIGHT]|
|Enter Note-off when note column is selected |EDIT + OPTION, OPTION|

Find and go to next free instrument:

1. Select instrument column
2. EDIT, EDIT 
3. SHIFT + RIGHT


## Instrument view
| Action | Key |
|---|---|
|Preview instrument.|[EDIT]+[PLAY]|
|Edit selected value with the position of a finger on any value with a visual slider.|[EDIT+TOUCHSCREEN]
|Assign the touchscreen axis to the selected parameter on any value with a visual slider. See the section on the MIDI Map-pings view. | [OPTION+TOUCHSCREEN|

## Mixer View
| Action | Key |
|---|---|
|Set selected parameter to its default value.|[EDIT]+[OPTION]|
|Creates a song snapshot for temporarily storing entire song to recall at a later point.|[SHIFT]+[OPTION]|
|Recall song snapshot. See [SHIFT]+[OPTION]|[SHIFT]+[EDIT]|
|Assign the touchscreen axis to the selected parameter. See MIDI Mappings view.|[OPTION+TOUCHSCREEN]|
|Assign a MIDI CC to the selected parameter. See MIDI Mappings view.|[OPTION+MIDI CC]|

## Pseudo Timestretching (locking loop-sample to tempo)

### Instrument view
- Set PLAY to **FWDLOOP**
- Set LENGTH to 0

### Modulation View
- Set MOD3 to LFO
- Set DEST to LOOP_ST(art)
- Set OSC to RAMP_UP
- Set TRIG to RETRIG
- Set FREQ to the amount of bars contained in sample (10 for one bar, 20 for two etc.)

