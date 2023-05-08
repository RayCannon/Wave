# Wave
Generate a Waveform Audio File Format (.WAV) files from APL and then play it. 

This Repostory has now been superseeded by TOCCATA.

In the file "ToccataDm.dws" is a Dyalog APL (Version 18.2 64bit unicode) workspace with all the functions required to build a ".WAV" file which can play the opening bars from J.S.Bach's Toccata and Fugue in Dm.

The top level function is "WriteToccata".  Before running, you should edit WriteToccata to specify the full filename you want the file to have. Currently it points to "C:\Program Files\APL\notes\Toccata.wav".

If not being run under MS Windows, the ⎕NA call to "PlaySoundW" (part of the "Winmn.DLL") will need to be replaced.
The ".WAV" file produced can be played by MS Media player and many other audio apps.

Under Windows, the function "Toccata" will play the file produced via PlaySound. The function Stop will stop PlaySound in its tracks.

The data for the music is supplied by the function TuneTocatta.

My ability to read music is somewhat lacking so the rendition is poor with a few "bum notes", which I will correct as soon as I can work out the correct notes and timings.
