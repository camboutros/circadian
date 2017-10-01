# circadian
Repository containing files for sonifying biological circadian and ultradian rhythms

Contents:
	* DataSonificationUsingPretty_MIDIandJupyterNotebook.pdf 	
		-Research Paper
	* Sonified Temperature Data Using PrettyMIDI
		-IPython Notebook
	* .wav Recordings
		- DataSonificationAll.wav
		- DataSonificationCoreandDiffCore.wav
- DataSonificationDistalandDiffDistal.wav
- DataSonificationAxialandDiffAxial.wav
- DataSonificationPercussionAndRatesonly.wav
	

Notes on Uploaded recordings: 

All recordings are sonifications of temperature data via MIDI. Some of the sonifications are direct representations of the data, others represent the first derivative taken on the data, and any percussion represents special events in the data, as described both in the accompanying research paper and IPython notebook. All direct representations of the data are normalized to in relation to each other; likewise, the difference function representations are normalized separately but also in relation to each other. All data that is represented with pitch is also pitch-bent to account for variance in the data that requires accuracy beyond the western music 12-tone “bucketing” per octave. 
	While listening to the recordings, it can be difficult to know at first what is being heard. However, within a minute or two of listening, it should be clear that there are some “instruments” that change pitch slowly, while others change pitch constant and seem to be more melodic as a result. In the recording containing all the tracks, the slowest tracks will be the core temperature data (which makes sense - core body temperature does not vary much, as contrasted with distal or axial body temperature) and the difference functions tracks (which would only change pitch slightly to reflect patterns of change in the original data). The distal and axial body temperature tracks change so much that they seem cacophonous at first, especially since the data contains three days worth of information condensed into a handful of minutes. Still, these begin to make sense with time; there are moments where all the original tracks and difference tracks drop in pitch simultaneously, reflecting an overall rapid drop in body temperature. There are also moments where there is unison of pitch, at least between the three original data sets, representing periods of high activity. Furthermore, there are beautiful stretches of the tracks where there appears to be repetition in harmony and melody - a product of the math involved and the meaningful relationships behind the data. With more analysis and more data, perhaps more information can be drawn from these stretches where cacophony seems to organize into something almost musical. 
	- DataSonificationAll is a .wav recording including all three original temperature datasets (core, distal, axial) as well as their correlating difference functions and a percussion track. 
	-DataSonificationCoreandDiffCore, DataSonificationDistalandDiffDistal, and DataSonificationAxialandDiffAxial separates out each of the original datasets and plays them with their difference functions and the percussion track in order to highlight the usefulness in having both the original representation and the difference representation. What is hopefully heard is the former track allows one to clearly and simply hear the data, while the latter gives a skeleton of what is important to hear in the data, and allows one to begin to draw conclusions and patterns out of it.
	-DataSonificationPercussionAndRatesOnly leaves out the original datasets entirely and gives us the sonification of just the difference function tracks and the percussion event tracks. Doing this eliminates the noisiness caused by the original sets and highlights patterns that emerge as one listens to . For example, at about 1:45, there is significantly more noise from all the tracks as opposed to earlier in the track. An overarching periodicity emerges: stretches of low activity across the board alternating with brief stretches of hyperactivity from all tracks. At 2:40, a bell plays over a cacophonous swell of sound; by 3:28, barely one track is playing. 


Notes on notebook: 

	The notebook can be viewed by installing Jupyter notebook and viewing the notebook in a browser. The current software uses Python version 2.7. 



