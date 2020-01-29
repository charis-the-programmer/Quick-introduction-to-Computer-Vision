# Quick introduction to Computer Vision
### What is Computer Vision?
Computer Vision is a field in Computer Science that focuses on giving computers the ability to see the visual world like the human eye does. The computers achieve this through acquiring, processing and analyzing the digital images and videos with the aim to extract meaningful information from the visual world. 
### A brief history of Computer Vision
The journey of Computer Vision started in the 1960s with the idea of giving computers the ability to mimic human vision and then ask them what they see. In 1966 the first milestone in the journey of artificially intelligent Computer Vision was reached when a camera was attached to a computer and then the computer was asked to describe what it saw.

In 1970 the foundations of the computer algorithms that exist today were formed which could extract edges from images, labeling of lines, motion estimation and optical flow. 
In the 1990s the researchers of Computer Vision focused mainly on mathematical analysis and quantitative aspects and they developed algorithms that were based on statistical learning which were later used for face recognition. 

In the decade that followed researchers of Computer Vision stated tapping into feature based techniques which are being used in conjunction with machine learning techniques and optimization techniques which are more complex. 

Currently the continuous improvements in deep learning techniques are facilitating the progress of Computer Vision and the accuracy of the algorithms that are now being used on Computer Vision datasets has proved to be much better.  
### Fields of Computer Vision
#### Object Detection
In this field the machines are supposed to  detect objects using the pattern of geometry for example detecting faces, detecting bodies or animals. There are many algorithms that are used to detect objects by computers for example the binary matrix is used to see where an object starts and where it ends on the binary image. This is achieved by finding connected components which are then used to determine the boundaries of the object. The computers will then generate a pixelated boundary of any color to show the location of that object. Below is an image that shows a road sign that has been detected by a computer.

![](https://codeswag.co.uk/wp-content/uploads/2020/01/1detection-1.jpg)

#### Object Recognition
This field follows the same steps taken in object detection but the only difference is that the object will be already detected and now the computer has got to compare the results with what is already stored in the database. For example when a semi-autonomous vehicle is trained to detect a road sign that signals road users to stop, the next time is detects a road sign it will then check if the sign matches the stop sign already stored in its database. If the sign matches with stop sign stored in the database then it will recognize it. The image below shows people and kites that have been recognized with a match percentage.

![images](https://codeswag.co.uk/wp-content/uploads/2020/01/1recognition.jpg)

#### Object Tracking
This field is based on video analysis which could be looking for frames on a webcam and then use image processing algorithms that extract information of the image and the objects on it. In this field the state of the objects will be stored such as their location on the frames. The computer will then track the objects on the frames as they move around in the frames of the video that is coming from the webcam. This field is only possible in video processing, in image processing this is not possible because the objects will be stationery. Below is an image showing a satellite that is tracking sea waves.

![Image](https://codeswag.co.uk/wp-content/uploads/2020/01/1tracking.jpg)

#### Object Classification
In this field the computer will put objects found on an image into a broad category based on its characteristics or visual content. For instance when using an object classification algorithm a computer may be able to tell if an image contains a human figure or not. This field differs from object detection in the sense that in object detection the computer doesn't specifically look for a human figure. The image below shows vehicles that have been put into certain classes by a computer.

![image](https://codeswag.co.uk/wp-content/uploads/2020/01/2classification-1.jpg)

#### Object Segmentation
In this field the computer divides an image into a number of regions using the characteristics of pixels to identify object boundaries in order to analyze it more efficiently. An example of object segmentation is seen on green screens where the foreground (object) is placed on another background. Below is an image which shows a tiger that has been placed on another background.

![Image](https://codeswag.co.uk/wp-content/uploads/2020/01/1segmentation-1.png)

### Applications of Computer Vision
#### Automotive
Computer Vision can be used on any vehicle could be land based, air based or water based to help navigate paths that are safe to move in. This can be achieved with a group of cameras that are mounted on the vehicles and these act as eyes for the vehicles. For instance when using the cameras and collision detection algorithms the vehicles will be able to determine the distance, motion and direction of every object in their surroundings which will ultimately help them decide the right speed and course of action required to avoid a collision. A good example of a vehicle model that is using these techniques is the [Tesla Model Y](https://www.tesla.com/modely) which is fully autonomous (it can drive itself without human supervision). It can do lane changing, self parking, roads signs and marking detection,auto pilot and more using computer vision. 
#### Health Care
Computer Vision can be used by medical professionals to better diagnose patients using medical imaging analysis, predictive analysis and health monitoring. Computer Vision algorithms can detect the slightest condition that could be otherwise not detected by human doctors who have sensory limitations. Medical imaging can create and analyze images or even assist doctors in interpreting them. It can also covert 2D image scans to 3D which gives the doctors a more detailed understanding of the patient's health. A good example of such a software is one called [InnerEye](https://www.microsoft.com/en-us/research/project/medical-image-analysis/) which was developed by Microsoft and is able to identify tumors and other anomalies in X-Ray images.
#### Security
Computer Vision can be used as a security eye that detects, recognize and verify to improve security. Using algorithms tailored for security computers are able recognize wanted suspects in crowds, detect possible theft on properties and verify identity using biometric features. For instance in China the [police identified a suspect to a case from a large crowd which was going to a concert](https://thenextweb.com/artificial-intelligence/2018/04/12/chinese-authorities-nab-fugitive-in-a-crowd-of-50k-thanks-to-facial-recognition-ai/).
#### Manufacturing Industry
Computer Vision can be used to inspect parts that are used in production to avoid mix ups and then inspect the finished products to check if they are of the required quality. Computer Vision can also control the production processes and flag if there are any inconsistencies. The scanning of products can also be achieved with optical barcode recognition which automate and speed up the scanning process of products on the production line.
#### Retail
Computer Vision can speed up retail operations for instance shelf management (barcode scanners), payments and data collection. Security can also be enhanced through the use of connected cameras that monitoring retail stores so as to detect suspicious behavior and deter theft. Computer Vision based mobile applications can be used to give the customers more information about a particular product, all the customer has to do show the product to the phone camera and the application will give all information relevant to that product. In clothing retail mobile applications can also be used to take body measurements of the customers so that the customers doesn't have to go to the retail stores to try out the clothes but just receive them at their convenient places.
#### Finance
  - Banking - When making payments Computer Vision can be used to identify customers using their iris for identification instead of credit cards or signatures which can be easily forged. All the customer has to do is to put their mobile phones' camera on the eye and the software will verify their identity then the payment is approved.
  - Insurance - When a risk has occurred the evaluation of the damaged property can be evaluated by a computer instead of sending an inspector which is time consuming. All the client has to do is take a picture of the damaged image then the system calculates the amount of damage and compensation required.
  - Commerce - satellites can be used to track the traffic of containers as they are transported to thier destinations so as determine the amount of imports and exports and use that for planning and decision making.
#### Social Media 
When applying filters on social media the computer recognizes parts of the face like eyes, nose, lips and jawline which are then used to modify face features in real time for instance when snapchat add puppy ears to a human face.
### The differences between Computer Vision and Image Processin
In Image processing an image is provided as input that is processed to give out an output in form of an image. The processing could be in form of smoothing, sharpening, stretching and contrasting. The processing depends on what needs to be achieved. On the other hand in Computer Vision an image or video is considered as an input to the system and the main focus is to understand the information on the image rather than changing its characteristics. The main difference is on the goal that is if the image needs to be transformed for later use then image processing is used and if the goal is to mimic human vision then computer vision is used.
### Best languages for developing Computer Vision 
Normally the most recommended languages for AI are Python, C++ and Java but for computer vision Python and C++ are the leaders. However Python is relatively slower compared to C++. Python is a scripting language built for systems simplicity, portability and creativity. But when using libraries like OpenCV there is C++ code underneath the Python code so basically Python becomes as fast as C++ and one advantage to this method is to combine the strength of the two languages. 
### Libraries available for Computer Vision 
The most popular libraries for Computer Vision include OpenCV ,Matlab and SOD but the leaders are OpenCV and Matlab. The performance of these libraries are almost the same but most developers prefer OpenCV because its for free yet it still achieve the same job which is done by Matlab. OpenCv is open source which gives it a wide range of support online. Some its source code is provided by by giants like Google, Microsoft and Intel. 
