# Image Pre-Processing for Feature Detection using SIFT

Feature Extraction or Detection is a key concept in image processing, as these help the computer to find relation between images i.e find patterns in images. Typically any image contains lots of information, the image as a whole is the grouping of multiple smaller pieces of information, just like a puzzle in which the separate pieces are arranged to form a bigger picture. Identifying these small piece of information and learning what it is and finding related piece of information in other images is feature extraction and discription. In images objects can be identified by its edges, corners, or flat surface. SIFT or Scale Invariant Feature Transform is a feature detection algorithm, that helps in finding features in differnt scaled images and orientated images. This algorithm find keypoints in different scales for each octave (Image Pyramids) and scales and orients the keypoints so that these keypoints can help identigy the same object in multiple images. Pre processing the image before SIFT by applying filters, to better improve the feature extraction is the goal of this project. As a pre processed image reduces the much problem caused by the original image. pre processing results in better results.

So, How can it be pre processed?

Since SIFT algorithm works on local gradients, edges identification and noise removal is necessary, so that unwanted features are not detected. A Gaussian high pass filter or gaussian blur with edge detection can be done to pre process the image. Also the image should have a good contrast. Poorly contrast images results in poor feature detection. Histogram equalization can be done to improve the contrast, to better improve the image before feed to the SIFT algorithm. 

Hence, in this project, the working of Image pyramids and SIFT is done, and the image is pre processed using the above mentioned filters to improve the results of feature detection
