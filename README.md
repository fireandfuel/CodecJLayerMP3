CodecJLayerMP3
==============

A mp3 codec library for Paulcode's 3D Sound System.
It based on parts of JLayer (mpeg decoder library), MP3SPI and Tritonus library.

How to use it:

If you use a IDE: Add the codec plugin to your build path.
Add the line

  import de.cuina.fireandfuel.CodecJLayerMP3;

to your the imports and

  SoundSystemConfig.setCodec("mp3", CodecJLayerMP3.class);

to the codecs setup at your class where Paul's Sound System is used.

Please use the Paulscode's forum for advices, critique, etc. 
http://www.paulscode.com/forum/index.php?topic=496.0

License: LGPLv3
