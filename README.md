# Shazam Canvas
Image classification app built for Android powered by the Tensorflow.JS lite ML model that has the ability to predict images in 1000+ categories. Built using Kotlin programming and Jetpack libraries

<p align="center">
  <img src="/demo/shazam_canvas_icon.png" alt="shazam_canvas_icon" width="100" height="100"/>
</p>

### Tech Stack
**Languages**: Kotlin </br>
**Libraries**: Tensorflow.JS, Jetpack </br>
**Technologies**: Android </br>

## App Usage
### Step 1: Launch app 
Shazam Canvas's UI design is based on the Shazam mobile app with modifications to better meet an image use case. 

![Shazam Canvas Launch](/demo/1_launch.gif)

### Step 2: Tap the `Select an Image` button to pick an image from gallery 
Shazam Canvas can access the mobile phone's photo gallery and store the selected image to a bitmap to display on the home screen and await identification.

![Shazam Canvas Launch](/demo/2_select.gif)

### Step 3: Tap the `Identify the Image` button to identify image  
Using the Tensorflow.JS lite ML model, Shazam Canvas is able to read the image stored in the bitmap and label it under 1 of 1000 categories supported by the ML model.  

![Shazam Canvas Launch](/demo/3_search.gif)
