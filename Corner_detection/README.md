## What is a feature?
* In computer vision, usually we need to find matching points between different frames of an environment. Why? If we know how two images relate to each other, we can use both images to extract information of them.
* When we say matching points we are referring, in a general sense, to characteristics in the scene that we can recognize easily. We call these characteristics features.
* So, what characteristics should a feature have?
   * It must be uniquely recognizable.
## Types of Image Features:   
* Edges
* Corners (also known as interest points)
* Blobs (also known as regions of interest )
## Why is a corner so special?
* Because, since it is the intersection of two edges, it represents a point in which the directions of these two edges change. Hence, the gradient of the image (in both directions) have a high variation, which can be used to detect it.
