# Krita shell audio helper scripts (It has no name, call it whatever)
A script to run an audio file such as .wav or .mp3 in the audio player of your choice after a 10 second countdown.

These two scripts were born from trying to find a hacky solution to the issue of playing audio files in krita.
They're both very primative, just using echo and sleep for 10 seconds, so I licensed it under CC0 because there was no justifcation using GPL for this.

I made both a windows .BAT and unix/linux/macos shell script. The non windows one is shell agnostic and doesn't use GNU extensions, so you don't have to have bash installed. Just download, modify the last line in the script that's commented out, and run it. The last line is supposed to be you playing the MP3/WAV/Whatever in the audio player of your choice. You then press the play button on the krita timeline when the file starts playing.

You may do whatever you wish with it, there is nothing impressive about this script at all. You will have to start at the beginning each time you play it, but that's okay to me because you're meant to use krita to split an animation be it a short or full length movie into a series of projects no more than 10 minutes. Only one audio file will be played, so you'll have to tape together into one if you want to use more than one audio file. Of course, nothing stops you from modifying the script further if you know what you're doing, consider this script an inspration for further hacking. Hack away!
