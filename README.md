# Real time, webcam-based face detection script
## This script returns your webcam feed, detects all human's faces and draws a rectangle around them

### Intro
The purpose of this script is to return your webcam feed and detect all human's faces on the feed and highlight them by a rectangle. The script uses the Haar Cascade Face Detection Model. The method of getting the webcam feed is specialized for Google Colab.

### Known issues
At this moment there are no known issues of this script. This is your opportunity to find one!

### Opportunities for further development
* [ ] All rectangles could get individual coloring for better visualization.
* [ ] The drawing of the rectangle after face detection lags by 1 FPS compared to the webcam feed, this can be disturbing for the user. It may be better if the webcam feed and the drawing would be synced, by making the webcam feed lag by 1 FPS.

### Credits
* @TheAIGuy https://www.youtube.com/@TheAIGuy
* Google Colab https://colab.research.google.com/
* Haar Cascade's Face Detection Model https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html
