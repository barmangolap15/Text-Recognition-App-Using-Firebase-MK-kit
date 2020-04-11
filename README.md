# Text-Recognition-App-Using-Firebase-MK-kit

Where text will be recognize from an image using Firebase Text Recognition kit

## Dependency

First we need to add **Firebase** dependencies in `build.gradle` app and project files

In `builde.gradle` app

<img src="text_recg_images/text6.JPG">

here, we user old versions of ml-version and core of `firebase` because, for latest versions (above 15+) we need to use our credit card

and in `manifests` we need to put camera feature

<img src="text_recg_images/text7.JPG">

and add `meta-data` inside `MainActivity.java` class in `application`

<img src="text_recg_images/text8.JPG">

## Getting Started

For taking the image we need one `ImageView` and to show the text from that image we need one `TextView`

<img src="text_recg_images/text9.JPG" width="400" height="400">  <img src="text_recg_images/text2.jpg" width="200" height="400"> <img src="text_recg_images/text4.jpg" width="200" height="400">

for capturing image and detecting the text from image we need two triggers, for that we used two `Button`s

<img src="text_recg_images/text10.JPG" width="400" height="400">  <img src="text_recg_images/text3.jpg" width="200" height="100"> <img src="text_recg_images/text5.jpg" width="200" height="100">

# Screenshots

## Main Screen
<img src="text_recg_images/text1.jpg" width="200" height="400">  

## after clicked CAPTURE IMAGE button
<img src="text_recg_images/Screenshot_20200411_141600.jpg" width="200" height="400">  

## after clicked DETECT TEXT button
<img src="text_recg_images/Screenshot_20200411_141605.jpg" width="200" height="400">  



