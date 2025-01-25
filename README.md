# Efficient Crowd Management System
We are building a web application that provides people with real-time analytics on wait times at SuperMarkets.
QLess scales to a diverse userbase by customizing its insights for individuals regardless of their social and economic backgrounds. 
This provides users with up-to-date info on the queue length of local people available in the market during a period of time. 

# People Counter Model

The People Counter program allows you to count the number of people in a video passing through a Region of Interest, which is created by the user. To use the program, you'll need Python 3 and OpenCV 3.4. 

It is built for measuring the crowd present in a supermarket, and it detects people using HOG + Linear SVM classifier (Histogram of Oriented Gradients for Objection Detection), along with Non-maximum Suppression(NMS); and it then outputs distinct pictures of the detected people using SIFT (Scale-invariant feature transform). 
The program counts number of people coming in towards the camera as coming 'In' and people going away from the camera as 'Out'. 


