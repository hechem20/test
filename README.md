Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.
Logic of project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed
The working of the project
As you can see the above screenshot where the landmarks aredetected using the detector.
Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.
Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.
![image](https://github.com/hechem20/test/assets/134158670/edfc2e52-ddcb-4664-8e3b-7707a7aca1dd)
![image](https://github.com/hechem20/test/assets/134158670/50c5e27d-4109-4e5a-9a5d-696540975a43)
![image](https://github.com/hechem20/test/assets/134158670/e62637a1-5ccc-4673-81df-2000e5b561c3)

