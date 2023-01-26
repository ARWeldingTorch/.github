# Senior Design Project


##Order of Frames Steps
- Get Frame
- Noise Reduction Filter
- Color Filter - 
- Character Detection - Put up prompt asking if the letters detected are correct
- Shape Detection
- Line Detection
- Confidence?
- Output

## Tyler's Milestones
- Learn python basics
- Install opencv and numpy
- Do simple camera color detection using opencv and numpy
- Calibrate camera
- Make camera recognize simple shapes
- Learn basics of open3D
- Make open3D do simple color detection and recognize simple shapes
- Filter noise
- Make open3D detect angles and depth
- Display widths,lengths, depths and angles on screen
- Recognize shapes and colors drawn on metal and use that to tell the robotic arm what to do

## Tyler's Project Statement


## Wyatt Short-term Milestones
- Setup OpenCV and Numpy
- Display camera
- Calibrate camera
- Extract pixel data 
- Filter out background
    - Observe color behavior
- Filter out noise
- Isolate clusters
    - Explore SciLearn
- Track/record center points
- 

## Wyatt Long-term Milestones
- Successfuly identify/isolate color
- Identify individual shapes/objects
- Log critical point pixel coordinates
- Prove reliability using depth camera through testing
- Model planes of joint and calculate parameters (angle, center, etc.)
- Combine 2D pixel location with depth information
- Verify reliability of 3D tracking through testing
- Allow better calculation through multiple photos
- Communicate location information to robotic arm
- Process/communicate details of weld to arm processor (color, writing, etc.)
-

## Wyatt Project Statement
The goal of this design is to provide reliable code that utilizes color, shape, 
and depth information from a mounted camera to route a robotic welding arm in an 
optimized way without manual input, minimizing the amount of required training for 
operators and allowing welders to more effectively control details of the weld.

## Elevator Speech 
Our project is aiming to mount a camera onto a production-level robotic welding arm 
that can process markings written on the joint and identify the best route to take, 
minimizing expensive iconsistencies between welds as well as the resources/man-power 
needed on the production line.
