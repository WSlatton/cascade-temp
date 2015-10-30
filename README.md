# cascade-temp

Temporary repository for cascade training files

## Usage

1. Place JPGs from android camera into either positive/ (photos of object to detect) or negative/ (photos of background)
2. run topng to convert all images to pngs
3. run resize to resize all images to a height of 256px
4. run list to generate file lists
5. run vec to generate samples
6. run merge to merge samples into one .vec
7. run train to create haar/cascade.xml
