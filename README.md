# Motion-Music

Instructions: Run the Music.java main method to bring up a window with two inputs, one for the file name of a .wav or .au music file you wish to play and control with leap motion, and the other for the BPM of the music. Leap Motion gestures with one hand can be used to change the tempo and volume of the music as it plays. Make clockwise circles to increase the tempo and counterclockwise circles to decrease the tempo. Make a swipe from left to right to increase the volume and swipe from right to left to decrease the volume. Making a tap gesture will end the music.

The MusicListener.java class uses the LeapJava.jar library from the Leap Motion SDK and allows for the recognition of leap motion gestures to change the audio.

The AudioPlayer.java class allows for the manipulation and playback of music by taking values from a MusicListener object that recognizez gestures. It draws from the StdAudio library from Princeton CS found here:
http://introcs.cs.princeton.edu/java/stdlib/

The Music.java class uses JFrame to make a GUI asking for two inputs, the file name of a .wave or .au file and the BPM of the music, and uses an AudioPlayer object to play music.
