# Lane Detection
### In road-transport terminology,a lane detection system can be used as lane departure warning system is a mechanism designed to warn the driver when the vehicle begins to move out of its lane (unless a turn signal is on in that direction) on freeways and arterial roads. These systems are designed to minimize accidents by addressing the main causes of collisions: driver error, distractions and drowsiness. In 2009 the U.S. National Highway Traffic Safety Administration (NHTSA) began studying whether to mandate lane departure warning systems and frontal collision warning systems on automobiles.[1][2]

## There are three types of systems:

### 1.Systems which warn the driver if the vehicle is leaving its lane with visual, audible, and/or vibration warnings (lane departure warning, LDW)
### 2.Systems which warn the driver and, with no response, automatically take steps to ensure the vehicle stays in its lane (lane keeping assist, LKA/LKS)
### 3.Systems which assist in oversteering, keeping the car centered in the lane, and asking the driver to take over in challenging situations (lane centering assist, LCA).

## Working principle
### A lane detection system used behind the lane departure warning system uses the principle of Hough transform and Canny edge detector to detect lane lines from realtime camera images fed from the front-end camera of the automobile. A basic flowchart of how a lane detection algorithm works to help lane departure warning is shown in the figures.

### Steps For Detecting lanes in the Video :
### 1. Video (Video is formed with the images.Discretizing the Video into the image.)
### 2. Making it to Gray Scale Image
### 3. Gaussian blurr
### 4. Canny Edge Detection.
### 5. Region of Interest
### 6. Bitwise and Operation
### 7. Hough Transform 
### 8. Optimization of the Line

## Couldn't upload Video As it was exceeding the  25MB size.
