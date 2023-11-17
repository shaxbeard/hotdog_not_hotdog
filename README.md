# Install

`npm install`

---

# Things to add

- Create a config folder with a `.env` file and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - CLOUD_NAME = `your cloudinary cloud name`
  - CLOUD_API_KEY = `your cloudinary api key`
  - CLOUD_API_SECRET = `your cloudinary api secret`
  - MS_COMPUTER_VISION_SUBSCRIPTION_KEY = `your Microsoft Subscription Key`
  - MS_COMPUTER_VISION_ENDPOINT = `your Microsoft Computer Vision Endpoint`
  - MS_FACE_ENDPOINT = `your Microsoft Face Endpoint`
  - MS_FACE_SUB_KEY = `your Microsoft Face Key`

---

# Run

`npm start`

# Project Description

This app is a re-creation of the Seefood app from the show, Silicon Valley. Like the app in the show, this app can only tell you if something in a photo is either a hot dog or NOT a hot dog. Unlike the app in the show, this app has access to a Machine Learning model that is actually identifying all of the objects in the photo. To check whether or nor there is a hot dog in the photo, I am simply checking if "hot dog" is one of the items on the list of contents.
