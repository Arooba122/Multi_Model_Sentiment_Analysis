# Video-Sentiment-Analysis
A web application that lets you analyze a video and classify each frame of the video into 7 different  emotions : Angry, Sad, Fear, Happy, neutral, Disgust  and Surprise. The sentiments shown by video characters will be identified. The whole video will be processed frame by frame and in each frame faces will be recognized first and then the facial expression will be classified into one of the possible sentiments/emotions.  Video that our system will display to the user will have rectangle drawn to person’s face ,at the bottom of the rectangle text will also be displayed. The text will be the emotion predicted by the system.
Following are the steps you need to perform in order to use the application:
1.	First install flask, cmake, boost-py, dlib, Opencv,Autokeras,tensorflow,face-recognize.
2.	The command to install these are below:
pip install cmake
pip install boost-py
pip install dlib
pip install opencv-python
pip install autokeras
pip install face-recognize
pip install tensorflow
3.	After the installation of all the mentioned libraries, open command prompt/Terminal and navigate to the directory where your actual application exists: 
C:\Users\faiza>cd d:/fyp/video-sentiment-analysis
4.	Now type “python app.py” to start flask server.
5.	Copy and paste the provided url (in my case it was : http://127.0.0.1:5000) on to your browser then hit enter.
6.	When the website opens click on the cloud icon and then browse through your directory to select the vide that you want to analyze.
7.	Once selected click on upload button, the website will display loading image.
8.	It may take time depending upon the duration and resolution of the video, after video is analyzed it will be displayed to you.
 


 

