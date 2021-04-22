# Clap Recogintion extension demo
This is a Chrom extension the will reconize a clap with your hand and siwtch the theme between dark and light theme at [netlify](https://app.netlify.com/).

This extension uses a model trained with [tensorflow.js](https://www.tensorflow.org) to reconize the clap with your hands and separate the background noises.

# Getting started

* Clone the repo.
* Run npm install to install the dependencies.
* Run npm run  build to generate the dist folder.
* Visit chrome://extensions in your browser and make sure developer mode is toggled on.
* Click on "Load unpacked" and select the dist folder generated.
* Visit https://app.netlify.com and clap your hands to toggle dark mode.
* Wooppie 😊


At the first time, you will be promted to get access to your microphone. To get it work you must grant it like this:
![](.img/grand.png)