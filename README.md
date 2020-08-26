# Group Number : 4

## Project Title : Sleep Stoppers
  -   "Time is money". We often hear this in relevance with the fast paced 21st century life. This has meant
      that we use more cab/taxi services than ever before. The cab drivers end up doing longer work/drive hours to earn
      that much extra money. This ofen puts them through a lot of stress and results in a bad sleep schedule. Accidents
      happen due to lapse of concentration which are a result of drowsiness or sleep depravity. We aim to install a sensor
      which detects the "drowsiness" level of the driver and raise an alarm if it crosses threshold.

## Abstract
  - As of late, driver drowsiness has been one of the significant reasons for street mishaps and can prompt extreme physical wounds, deaths and noteworthy financial misfortunes. Measurements demonstrate the need of a dependable driver drowsiness discovery framework which could alarm the driver before a disaster occurs. A nitty gritty survey on the measures will give understanding on the current frameworks, issues related with them and the improvements that should be done to make a powerful framework. By structuring a cross breed drowsiness identification framework utilizing Convolutional Neural Networks that combines non-meddlesome physiological measures with different measures, one would precisely anticipate the driver drowsiness level. Various street mishaps may then be kept away from if an alarm is sent to a driver who seems to be drowsy.
      
## Architecture Diagram
![alt text](https://github.com/SJSUSpring2020-CMPE272/Sleep-Stoppers/blob/master/Sleep_Stoppers_Architecture.png "arch diag")

![alt text](https://github.com/akshay-sjsu-173/cmpe272-project/blob/master/Report%20Stuff/How-facial-recog-works.JPG "prof flow")
## Technology Stack
   - Video Camera : This must be capable of capturing the driver's face.
   - Image Map : Python deep learning library to create an image map from the video/image stream
   - Open CV : This is required to stream video camera data to code.
   - Machine Learning : Keras , Tensorflow
   - Mini speaker : We will require this to trigger an alarm if "drowsiness" threshold is breached.

## Project Setup
  - Clone https://github.com/SJSUSpring2020-CMPE272/Sleep-Stoppers.git
  - Make sure you have the required python version by referring to https://github.com/SJSUSpring2020-CMPE272/Sleep-Stoppers/blob/master/Pipfile
  - If you don't have "pipenv" installed, run the following command: <br>
    "pip3 install pipenv"
  - The following commands will setup a virtual environment to run this project: <br>
    1.  pipenv shell
    2.  pipenv install --dev
  - Run the following command to start the application: <br>
    "python drowsiness_detection.py"
