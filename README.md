# motion-star-editor
Short jupyter notebook used to loop through and edit lines within all .star files in a WARP-made motion folder.
This script is a small part of my usual processing pipeline. I will collect .tif images, preprocess particles on WARP, and clean the stack in cryosparc. I will always try baysian polishing on any dataset I've collected, which requires conversions of the data to be read and used by Relion. This script is used in the conversion process when I have multiple data collections I want to individually do Bayesian polishing on but want to 3D refine together. Most often, I have to edit MicrographMovieName in each movie/.star file to point to the original .tif image in the original collection directory as I've found a soft link to the tif images from the relion directory does not get properly read by relion.

See attached presentation WARP_Csparc_Relion31 for more detail on this process and pipeline

This notebook was made with help from John Lithio, data scientist
