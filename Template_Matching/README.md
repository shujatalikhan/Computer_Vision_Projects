## Template matching:
### Template matching is a technique for finding areas of an image that match (are similar) to a template image (patch).
## How it Works:
### We need two primary components:
### Source image (I): The image in which we expect to find a match to the template image.
### Template image (T): The patch image which will be compared to the template image.
### To identify the matching area, we have to compare the template image against the source image by sliding it:
### By sliding, we mean moving the patch one pixel at a time (left to right, up to down). At each location, a metric is calculated so it represents how “good” or “bad” the match at that location is (or how similar the patch is to that particular area of the source image).
