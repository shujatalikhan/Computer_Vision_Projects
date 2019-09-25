## An image gradient is a directional change in the intensity or color in an image. The gradient of the image is one of the fundamental building blocks in image processing.
### OpenCV provides three types of gradient filters or High-pass filters, Sobel, Scharr and Laplacian. We will see only sobel and Laplacian Derivative.

### 1. Sobel and Scharr Derivatives
### Sobel operators is a joint Gausssian smoothing plus differentiation operation, so it is more resistant to noise. You can specify the direction of derivatives to be taken, vertical or horizontal (by the arguments, yorder and xorder respectively). You can also specify the size of kernel by the argument ksize. If ksize = -1, a 3x3 Scharr filter is used which gives better results than 3x3 Sobel filter. Please see the docs for kernels used.

### 2. Laplacian Derivatives
### It calculates the Laplacian of the image given by the relation, \Delta src = \frac{\partial ^2{src}}{\partial x^2} + \frac{\partial ^2{src}}{\partial y^2} where each derivative is found using Sobel derivatives. If ksize = 1, then following kernel is used for filtering:

## Canny edge detection is a technique to extract useful structural information from different vision objects and dramatically reduce the amount of data to be processed. It has been widely applied in various computer vision systems. Canny has found that the requirements for the application of edge detection on diverse vision systems are relatively similar. Thus, an edge detection solution to address these requirements can be implemented in a wide range of situations. The general criteria for edge detection include:

### 1. Detection of edge with low error rate, which means that the detection should accurately catch as many edges shown in the image as possible
### 2. The edge point detected from the operator should accurately localize on the center of the edge.
### 3. A given edge in the image should only be marked once, and where possible, image noise should not create false edges.
