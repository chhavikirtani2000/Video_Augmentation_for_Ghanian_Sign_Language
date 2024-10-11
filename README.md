# Video_Augmentation_for_Ghanian_Sign_Language
The available videos for ghanian sign language are very less. To counter this, I created a script that creates 10 different diverse videos from a single video. This data augmentation improves the classification results significantly for situations with less data. This script can be used for any Computer Vision project in general.

Different augmentation techniques implemented here are:

['AnglePerspectiveChange', 'RandomRotate30', 'Multiply', 'HorizontalFlip', 'InvertColor', 'PiecewiseAffineTransform', 'RandomTranslate', 'RandomRotate60', 'VerticalFlip', 'GaussianBlur']

Note that AnglePerspectiveChange basically changes the viewing angle of the video (as if the camera was filming it from a different direction). The code for this augmentation technique was implemented from scratch, and the other augmentation techniques were implemented thanks to importable functions and utilities from https://github.com/okankop/vidaug

We saw a tremendous increase in ghanian sign language classification after augmenting our data.

