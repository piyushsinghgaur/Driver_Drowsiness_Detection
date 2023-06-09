# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.</br></br>

<h3 >The working of the project</h3>

<ul><li>As you can see the<b> above screenshot</b> where the landmarks are detected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>

<center>
<img src="https://github.com/piyushsinghgaur/Driver_Drowsiness_Detection/assets/96806312/8227bc39-39dc-4408-b4e5-b5697f7e704c" align="left" height="350">
</center></br>

![Active](https://github.com/piyushsinghgaur/Driver_Drowsiness_Detection/assets/96806312/a6ab185f-039c-4320-a434-a0dc66346b50)

![Drowsy](https://github.com/piyushsinghgaur/Driver_Drowsiness_Detection/assets/96806312/788a6310-8461-4a17-a184-cb60994c95d0)

![Sleeeping](https://github.com/piyushsinghgaur/Driver_Drowsiness_Detection/assets/96806312/988fd06c-7060-4615-90f5-87806de9348f)




