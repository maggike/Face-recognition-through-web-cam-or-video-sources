# face-recognition-from-webcam-and-video-sources
Face Recognition from WebCam and Video Sources using Javascript, NodeJS and face-api.js which is a wrapper around TensorFlowJS.

<b>Some of the Major technologies used:</b>
1. <a href="https://nodejs.org/" target="_blank">NodeJS</a>
2. <a href="https://expressjs.com/" target="_blank">ExpressJS</a>
3. <a href="https://javascript.info/" target="_blank">JavaScript</a>



Prerequisites to run the app in local environment
1. Installed NodeJS


<b>Step 1:</b>
Run the command ``` npm run dev ``` on terminal, making sure you are in the face_recognition_video directory. The code will run on http://localhost:3000. 
On my local computer, the final output is like this:


![my web cam image](https://github.com/maggike/Face-recognition-through-web-cam/assets/140755916/f82b375e-db6c-4ab4-8e36-ede2efc1ccc7)



The code is set to image recognition through web-cam. Change it following the instructions below to recognize images through video. A sample video of the Avengers and their images have been uploaded just to represent how the code would work. But it can be used for recognizing any person's face through web-cam or video once their images (3-5) have been added to the public/labeled_images directory.

<b>Congratulations!</b> You are good to GO now.

<b>For WebCam:</b>
Just comment out line number 16 and 56 inside public/js/script.js and uncomment from line 10 to 15 and 57.

<b>For Video Source:</b>
Just uncomment line number 16 and 56 inside public/js/script.js and comment out line 10 to 15 and 57.

<b>Note:</b>
For best performance, if you have a dedicated graphic card on your system enable that to be used by your browser. By defualt browser uses the internal graphic of the system which might not work best for this app.






