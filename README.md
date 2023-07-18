
# Releases of parameter sets without LEEF specification, refer to the first LEEF experiment.

# v2.3.5-LEEF-2: flowcam.yml: added "Small_cells" to species tracked

# v2.3.3-LEEF-2: Change of flowcytometer dilutions

# v2.3.2-LEEF-2: Flowcam classifier uses now small letters as trait names

# v2.3.1-LEEF-2: Add size standards and FSC A to size conversion parameter

# v2.3.0-LEEF-2: Update of LEEF 2 classifiers and change in flowcam species

# v2.2.2-LEEF-2: changes to flowcytometer and flowcam
- removed `parameter/0.raw.data/flowcam/flowcam_dilution.csv` as added manually anyway and differs between days
- updated `parameter/0.raw.data/flowcytometer/metadata_flowcytometer.csv`
- added `treatment/stressor_levels.csv`

# v2.2.0-LEEF-2: Dilution rates in flowcytometer changed

# v2.1.1-LEEF-2
- changed README.md

# v2.1.0-LEEF-2
- change inbemovi.mag.25 parameter and tracked species
- removal of LEEF-1 treatment files


# v2.0.5-LEEF-2
- changed dilution factors for flowcytometer and flowcam

# v2.0.4-LEEF-2
- added missing `flowcam.yml`

# v2.0.3-LEEF-2
- added missing `.rds` to classifiers in bemovi_mag_25

# v2.0.2-LEEF-2
- added missing return to flowcam.yml
- fixed typo in experimental design (bottles instead of bottle)

# v2.0.1-LEEF-2: Final changes
- Formating change in conductivity.xlsx
- added directories with dummy files in flowcytometer

# v2.0.0-LEEF-2: initial release for LEEF-2




# v1.6.1: Added flowcam classifier for bottle b_05
Bottle b_05 has been contaminated at 20220504. b_05 should be classified after
that date using this classifier
`svm_flowcam_classifiers_B02_contaminated_after_20220504_20220710_MergedData.rds
` for the flowcam.

# v1.6.0: Classifier including all videos and images from the beginning of the experiment

# v1.5.1: Fix wrong tracked_species in yaml files

# v1.5.0: new classifiers for flowcam and videos. 
These classifiers use all stock culture data recorded up to date (April 2022).
tests have qualitatively shown that the within treatment variance is bigger than
the variance across treatments, meaning that there is only 1 classifier
respectively for the flowcam, the videos 25x and the videos 16x, i.e. no
different classifiers for different treatments (light vs decreasing light).


# v1.4.0 Flowcam updated for light at 18% increasing and constant
These classifiers use data from early February 2022 (and only this data, as
discussed), when the light was either constant or at 18% (decreasing). Hence (if
I'm not mistaken) these classifiers are to be used for the period of time where
the light was between 24% and 12% (values included) (resp. constant in the
control).


# v1.3.0 DO NOT USE _ NOT CORRECT 

# v1.2.1: Corrected bemovi 16x classifier

# v1.2.0: Classifiers and corresponding yml files updated

# v1.1.2: add 'instrument' field to 'flowcam_dilution.csv' file

# v1.1.1: rename classifier_cropped to non_cropped

# v1.1.0: added additional bemovi 25 classifier_cropped analysis where same
# classifiers as in 
  cropped are used, but the video is NOT cropped.

# v1.0.1: added 'filtration' and 'flowcell' columns to the file
  'flowcam/flowcam_dilution.csv'
  These are carried through to the table 'flowcam__algae_traits' in the RRD
  database

# v1.0: Parameter for first temperature steps in LEEF experiment 18 degrees
https://github.com/LEEF-UZH/LEEF.parameter/releases/tag/1.0

# v0.9: Parameter for 30 samples

The github repository can be found at
[https://github.com/LEEF-UZH/LEEF.parameter](https://github.com/LEEF-UZH/LEEF.
parameter)

