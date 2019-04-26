Run the Main function
Select the twinkle_Midi_File
Play the Midi file
Select the twinkle_Audio_File
Play the aduio file
Click AutoTune
Autotuned file will be played and also stored in twinkle_AutoTuned_File




Write midi folder includes the function to write the midi file.
The command in the text file is how you give it in matlab and it calls the function to write the midi files 
We need to specify:
track number
channel number
note number (midi encoding of pitch)
velocity
start time (seconds)
end time (seconds)
message number of note_on
message number of note_off
To write to a midi file
Text file has the example of how to generate random midi file.