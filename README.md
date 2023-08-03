# Human Count Detection
- An application that allows detecting humans or people in any image, video, or even through a Camera.
- It also visualizes no. of humans detected and the avg. accuracy of detection w.r.t. time, using graphs and plots.

### Python Libraries Used : 
- tkinter
- messagebox
- PIL
- cv2
- argparse
- matplotlib.pyplot
- numpy
- time
- os
- tensorflow
- fpdf

### Flow of steps:
- The user just needs to download the file and run the main.py on their local system.
- On starting the application, he will be able to see the START and EXIT options, using which he can start or exit from it.
- When he starts the application using the START button, a new window will open, which allows him with options like, DETECT FROM IMAGE, DETECT FROM VIDEO, or DETECT FROM CAMERA.
- When he selects any of the first two options, he needs to determine the respective files using the SELECT button.
- He can preview the selected file using the PREVIEW button, and detect and count the humans using DETECT button.
- And when he selects, the last option of detecting through the camera, he needs to open the Camera, using the OPEN CAMERA button, As soon as the camera opens, the detection process will start.
- After the detection process gets completed or he manually completes it, two graphs get plotted, 
	- 1.) Enumeration Plot(Human Count Vs. time) and 
	- 2.) Average Accuracy Plot(Average Accuracy Vs. time).
- Along with these two plots, an option to generate a crowd report also appears, On clicking on it, a crowd report in the form of a PDF is generated and saved automatically at the project file location.
- In the crowd report generated, there will be information like, What is Max Human Count, Max Accuracy, Max Avg. Accuracy, and also a two-line status about the crowd.

### Compilation Steps :
- Install all the required libraries.
- After that download the code file, and run main.py on the local system.

