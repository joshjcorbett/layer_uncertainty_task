# layer_uncertainty_task
PsychoPy code (and other relevant files) for running the orientation judgement task used in a study investigating the representation of uncertainty across cortical layers.

## General structure
The main experiment file is ‘fmri_ori_task.psyexp’ in the ‘scripts’ directory. This file was generated using the PsychoPy Builder (v2022.2.4).

The experiment file calls a protocol file from the ‘protocols’ directory. Each protocol file contains pregenerated orientations for up to 20 blocks of 18 trials. 

Orientations were chosen pseudo-randomly, such that the orientations from each block of 18 trials are uniformly distributed, and roughly cover the full range of [0,180).

Results are saved in the ‘results’ directory, which will be created the first time the experiment is run.

## Other notes
This experiment file was designed to be used in an fMRI study. The experiment (and each block) commences when the letter ’t’ is pressed (the scanner trigger).

The bar is rotated using ‘a’ (counterclockwise motion) and ‘b’ (clockwise motion) keys, which corresponded to left and right buttons on a button box used in the original fMRI study.

To exit the experiment at any time press the ‘escape’ key.

See the readme.md file in the scripts directory for details on how to deal with a common PsychoPy bug when running on Mac.
