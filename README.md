
# Color Detection Script and HSV Trackbar Tool

This project consists of two Python scripts using OpenCV for color detection and manipulation of HSV (Hue, Saturation, Value) values. The color detection script captures video from a webcam, identifies the color of a central pixel in each frame, and displays the color name on the screen. The HSV trackbar tool allows users to interactively adjust HSV values using trackbars and visualize the resulting color.

## Color Detection Script:

### Usage:
1. Ensure you have OpenCV installed (`pip install opencv-python`).
2. Run the script.
3. Point your webcam at an object with distinct colors.
4. The script will identify the color of the central pixel in each frame and display the corresponding color name.

## HSV Trackbar Tool:

### Usage:
1. Ensure you have OpenCV installed (`pip install opencv-python`).
2. Run the script.
3. Adjust the HSV trackbars to manipulate the HSV values.
4. The window will display the resulting color based on the HSV values.

## Color Naming:
- The color detection script categorizes colors based on the hue value of the central pixel in each frame.
- Colors are categorized as follows:
  - RED: Hue values less than 5
  - ORANGE: Hue values less than 22
  - YELLOW: Hue values less than 33
  - GREEN: Hue values less than 78
  - BLUE: Hue values less than 131
  - VIOLET: Hue values less than 178
  - Undefined for all other values

## Note:
- Ensure your webcam is correctly connected and functional.
- Adjust lighting conditions if necessary for accurate color detection.
- Press `ESC` key to exit both scripts.

