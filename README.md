
# Project Title

Web appliction based on facial recogination to reduce
cyber crime related womens.

## Documentation

It's basically a photoapp where we can upload photos and if you have objection with any photo about you uploaded by others user, you can instantly remove the photo by reporting through report button It simply recognize your face to verify it's you in that photo after verification, that photo remove automatically within a seconds.

# Services used in project 
 ## Azure blob storage
   :to store picture uploaded by user 
 ## flask framework
   :to make web app
 ## open cv & face recognition library
   :to scan and match faces
 ## html and css:
   :to customize web page

## Installation
(1) Create the Azure blob storage account on 
   Azure portal (https://portal.azure.com/)

(2) Open code on "vs code" and make & activate virtual environment 
   to run python flask app.

   To create virtual environment "env" run this in cmd terminal of vs code
   ### py -m venv env
   To activete virtual environment "env" run this in cmd terminal of vs code
  ### .\env\Scripts\activate.bat


(3)install libraries in virtual environment one by one in cmd terminal of vs code

### pip install flask
### pip install azure-storage-blob
### pip install opencv-python
### pip install dlib https://github.com/jloh02/dlib/releases/download/v19.22/dlib-19.22.99-cp310-cp310-win_amd64.whl
### pip install face_recognition


(4) To run the flask app by runing this in cmd terminal
### flask run
(4) Run the flask app & upload any image (size should be less(<100kb) for best results) by clicking "choose files" and "submit" buttons form your local files and to check the functionality of report button click on
  "instant report" .

  
## Demo Url link
https://youtu.be/OnWZZXoJ_NA


## 🚀 About Me
I'm a self taught full stack web developer coding is my hobby.


## FAQ

#### Question 1
Why are you not used Azure Face API or Coginative services in your project?

#### Answer:
Initially I tried to implement face api and cognitive services in my project, but due to some documentation issue (uses of face verification using stream of image of face api) and due to some functionality I want to use like verify-face using web cam and match with the give image become very difficult task for me to use Azure face api or cognitive services, that's why I'm forced to use opencv 
and face recognition libraries.

#### Question 2
Why are you not deploying your web app on Azure using Azure web app services?
#### Answer:

I tried my best to deploy my flask web app, but every time I tried to deploy they give me the error in importing."Cmake libraries", "dlib libraries" that is important to install face recognition library
on "Azure cloud", even I tried hard to deploy my web app on other cloud platforms also like "Heroku", but they give me the same error when it comes to installation of face recognition libraries.
