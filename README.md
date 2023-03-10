# COCO-Keypoints-Demographics (COCO-KD) annotations

The file [annotations.csv](annotations.csv) provides our annotations for a subset of images from the COCO 2017 validation set (keypoint challenge).

657 valid images (containing a face, of sufficient size in pixels) were identified; please refer to our main paper for additional methodological details.  
These annotations should only be used for fairness evaluation.

For each image, identified by image ID, we provide values for age, gender, and skin tone, as annotated by three of the paper's authors. 

- Age is provided as a value -1, 0, 1, 2 or 3. -1 indicates the lack of a valid face within the image. Other numbers are associated with perceived age as follows: 0: [0, 18], 1: (19, 30], 2: (31, 50], 3: (51 +). 
- Gender is provided as a perceived binary value. -1 indicates the lack of a valid face within the image. Values may be Female or Male otherwise. 
- Skin tone takes the form of either a binary value or -1, indicating the lack of a valid face within the image. A value of True indicates that the primary subject is lighter-skinned. A value of False indicates that the primary subject is darker-skinned.


