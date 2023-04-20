# Wave
Generate simple Waveform Audio File Format  (.WAV) files from APL and play them 

In the file "ToccataDm.dws" is a Dyalog APL (Version 18.2) workspace with all the functions required to build a ".WAV" file which can play the opening bars from J.S.Bach's Toccata and Fugue in Dm.

The top level function is WriteToccata. with the music being supplied by the function TuneD. The file can be played bt MS Media player 

My ability to read music is somewhat lacking so the rendition is somewhat poor with a few "bum notes", which I will correct as soon as I can work out the correct notes and timings.

The function Toccata will play the file produced by WriteToccata via a ⎕NA call to PlaySound. The function Stop will stop PlaySound in its tracks.
