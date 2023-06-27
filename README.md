# RVC2UTAU
Files for converting an RVC model to UTAU

Here's how to do it:

1. Open your RVC inference interface of choice.

2. Select the model you want to make an utau of.

3. Use the "utau_dataset.wav" as your inference audio.

4. Download the result.

5. Open audacity, and load the audio.

6. Go to Import>Labels and import the "Labels 4.txt" file.

7. Go to Export>Multiple, and select these settings:

	-Format: WAV
	-Split  files based on: Labels
	-Name files: Using Label/Track Name

    Make sure these files are exported to a new folder so everything is together.

8. Go to the "UTAU files" folder and find the "character.txt" file. Edit it, changing "New Utau Voicebank" to the
   name of your model.

9. Go to the folder where the audios were exported to, and insert all files from the "UTAU files" folder.

10. If you want to change the icon for the voicebank, get any image, change the size to 100x100, and open it with
   MSPaint and save over the "icon.bmp" file you copied into your utau's folder.


That should be everything! The voicebanks run best with moresampler, which you can download below:

https://mega.nz/file/D7B2UCiK#hVSiX7AZzeWf7Tr8TmWEojN9mKYPsSZnKc6xgqlbrtw

___________________________________________________________________________________
Guide is by hobqueer

Oto included is by Biggety Boy
