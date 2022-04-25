# v1.5.0: new classifiers for flowcam and videos. These classifiers use all stock culture data recorded up to date (April 2022). tests have qualitatively shown that the within treatment variance is bigger than the variance across treatments, meaning that there is only 1 classifier respectively for the flowcam, the videos 25x and the videos 16x, i.e. no different classifiers for different treatments (light vs decreasing light).


# v1.4.0 Flowcam updated for light at 18% increasing and constant
These classifiers use data from early February 2022 (and only this data, as discussed), when the light was either constant or at 18% (decreasing). Hence (if I'm not mistaken) these classifiers are to be used for the period of time where the light was between 24% and 12% (values included) (resp. constant in the control).


# v1.3.0 DO NOT USE _ NOT CORRECT 

# v1.2.1: Corrected bemovi 16x classifier

# v1.2.0: Classifiers and corresponding yml files updated

# v1.1.2: add 'instrument' field to 'flowcam_dilution.csv' file

# v1.1.1: rename classifier_cropped to non_cropped

# v1.1.0: added additional bemovi 25 classifier_cropped analysis where same classifiers as in 
  cropped are used, but the video is NOT cropped.

# v1.0.1: added 'filtration' and 'flowcell' columns to the file 'flowcam/flowcam_dilution.csv'
  These are carried through to the table 'flowcam__algae_traits' in the RRD database

# v1.0: Parameter for first temperature steps in LEEF experiment 18 degrees
https://github.com/LEEF-UZH/LEEF.parameter/releases/tag/1.0

# v0.9: Parameter for 30 samples

The github repository can be found at 
[https://github.com/LEEF-UZH/LEEF.parameter](https://github.com/LEEF-UZH/LEEF.parameter)

