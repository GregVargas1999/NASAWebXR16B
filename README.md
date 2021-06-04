# NASA Psyche Mission Timeline
CS/CSE Capstone Project for NASA Web XR Group 16B - NASA Psyche Mission Timeline
Team Members: Fareed Osman, Greg Vargas, Rushil Popat, Joshua Holloway
Arizona State University

## Summary

The NASA Psyche Mission Timeline is an interactive website where users can view
and learn about the major phases of the Psyche mission. Different phases are
represented in a 3D environment and animated.

## Programming Languages and APIs

All code for our website is written using JavaScript, with HMTL and CSS used
to format the website.

We used the JavaScript API 'three.js' for 3D object rendering, which is compatible
with most mobile devices and browsers. For more info: https://threejs.org/

For animating the 3D objects, we used the 'tween.js' API. The API is compatible
with 'three.js' and allows for animating movement using 3D vectors. More info
can be found here: https://github.com/tweenjs/tween.js/blob/master/docs/user_guide.md

## Testing

While developing the website, most of our coding and testing was done through
Visual Studio Code. A plugin called 'Live Server' allows for launching the
website using the local device as a server.

## Usage

Once the website is launched, the user will be directed to a homepage, where
they can select between 2 different implementations of the website. Once a
version is selected, it will load the main menu screen.

'Begin Journey' takes the user to the first phase of the mission, while the 
'Next Stage' and 'Previous Stage' buttons are used to transition between phases.
'Credits' allows the user to view the credits and disclaimers.
