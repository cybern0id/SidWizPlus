# SidWizPlus
Fork of a version of SidWiz with modifications for my own purposes.

## Features added

* Commandline mode
* Replaced renderer with GDI+ (.net Graphics API), allowing simpler code and more advanced rendering:
** Antialiasing
** Bitmap layering
* Added rendering features from other variants
** Grid
** Channel labels
* Integration of [MultiDumper](https://bitbucket.org/losnoco/multidumper) to generate tracks from a VGM
** Including automatic removal of unused tracks
* Automatic master audio track generation, with ReplayGain
* Waveform scaling (including auto-scaling)
* Unlimited tracks and columns
* YouTube uploading
** Including generation of titles and descriptions from tags in VGM files
