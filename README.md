# **Air Canvas** using **Computer Vision**

- **Air Canvas** is a **virtual painting** application that helps the user to draw on screen virtually just by waving their **finger** fitted with **coloured caps** in the air without touching the screen.
- This project uses the concept of **Computer Vision** and is implemented using ```Python```, ```OpenCv``` & ```Numpy```.

# System Requirements:

- ```Python```
- ```OpenCv```
- ```Numpy```
- ```WebCam```

# Concepts used:

- **Color Tracking:** Tracks the colored object at the finger tip.
- **Contour Detection:** Detects the position of the colored object and making a circle over it.
- **Frame Processing:** Tracking the finger tip and drawing points at each coordinate positions for virtual painting effect.
- **Image Masking:** Image mask is created after detecting color.
- **Color space conversion:** Converts the BGR into HSV values.

# Algorithm:
- Read the frames and convert the captured frames to HSV color space.
- Prepare the canvas frame and put the desired colors for painting.
- Prepare the mask and perform morphological operations on it.
- Detect the contours.
- Store the centre coordinates of the contour in the array for successive frames.
- Finally draw the points stored in the array on the screen.

# Screenshots:

# Applications of this project:
- Draw your imagination on screen easily.
- Can be used for teaching purpose and one can easily rub the window by just choosing clear all option.

Hope you all liked this project :heart:
