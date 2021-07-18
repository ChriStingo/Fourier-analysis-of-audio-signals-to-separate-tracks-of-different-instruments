# Fourier-analysis-of-audio-signals-to-separate-tracks-of-different-instruments
Analysis of an audio signal consisting of two or more instruments. Work on the Fourier transform to obtain the original audio tracks of the instruments that make up the signal given in input.

### **Introduction**:

This can be achieved by manually making selections by observing the Fourier transform and making various attempts.

Personally I don't think this method is interesting, so I looked for a way to perform this procedure automatically.

Therefore, given a signal with certain characteristics, such as that of being composed of instruments whose transforms have distinct frequencies, I tried to obtain, through appropriate cuts, a filter on the frequencies that would divide those belonging to one instrument from those belonging to another. Obviously all this without knowing the instruments that make up the signal given in input.

This method does not guarantee absolute precision and does not always manage to divide the instruments perfectly, this is due to how the Fourier transform of the composite signal looks.

Nevertheless, I have prepared two optimal examples where this occurs with acceptable accuracy.

### **Example of execution**:

![download](https://user-images.githubusercontent.com/62427405/126068255-c16ac284-a220-4711-9d75-df28c3cba57b.png)

Inside the notebook you can also listen to the result

**Note**: To load the audio files do not load the folder, but the audios individually
