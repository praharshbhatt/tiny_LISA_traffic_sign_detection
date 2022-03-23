## Context
This dataset (Tiny LISA) comes from the LISA database, which originally consists of 6,610 images and 47 classes. This database arises from the paper "Vision-Based Traffic Sign Detection and Analysis for Intelligent Driver Assistance Systems: Perspectives and Survey".

## Content
Tiny LISA was developed to facilitate experimentation in our work "Evaluation Method of Deep Learning-Based Embedded Systems for Traffic Sign Detection" aiming to test our proposed method.

The db_lisa_tiny.zip file contains an annotations.csv file and the 900 .png images. In total there are 900 annotations, each annotation is a row that contains 6 columns: Name of the file with enumeration, the coordinates of its bounding box (x1, y1, x2, y2), and the class label to which the file belongs traffic sign. This structure is stored in the annotations.csv file. An example of the structure is presented below:

filename;x1;y1;x2;y2;class