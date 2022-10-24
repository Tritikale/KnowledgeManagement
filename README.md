# Knowledge management lab, Brain Tumor Detection

The GUI can be used to detect and view the tumor region.

The tensorflow model can be used to detect if the MRI image contains tumor or not.
The tumor region can be viewed using Image processing methods applied through opencv. Image segmentation using marker-based watershed segmentation algorithm is used to view the tumor region. A watershed is a transformation defined on a grayscale image. We label the region which we are sure of being the foreground or object with one color(or intensity), and label the region which we are sure of being background or non-object with another color and finally the region which we are not sure of anything, we label it with 0. That is our marker. Then apply watershed algorithm. Then our marker will be updated with the labels we gave, and the boundaries of objects will have a value of -1.
