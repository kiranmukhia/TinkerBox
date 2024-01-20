## Project Overview

This repository contains a simple web page that generates fireworks effects when the user moves the mouse. The web page includes HTML, CSS, and JavaScript files to create an interactive and visually appealing New Year's celebration experience.

<br>

## Under The Hood

### NewYearFireWorks.html

This HTML file defines the structure of the web page, including the necessary links to the CSS and JavaScript files. It also contains a container for fireworks and a greeting message.

`<!DOCTYPE html>`: Declares the document type and version of HTML. <br>
`<html lang="en">`: Specifies the language of the document.<br>
`<head>`: Contains meta information and links to external resources.<br>
`<meta charset="UTF-8" />`: Sets the character encoding to UTF-8.<br>
`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`: Configures the viewport for responsive design.<br>
`<title>New Year's Fireworks</title>`: Sets the title of the web page.<br>
`<link rel="stylesheet" type="text/css" href="NewYearFireWorks.css" />`: Links to the external CSS file.<br>
`<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet" />`: Links to the Google Fonts API to import the "Pacifico" font.<br>
`<body>`: Contains the content of the web page.<br>
`<div id="fireworks-container">`: Container for the fireworks and greeting message.<br>
`<h1>Happy New Year!</h1>`: Greeting message.<br>
`<script src="NewYearFireWorks.js"></script>`: Links to the external JavaScript file.<br>

<br>

### NewYearFireWorks.css

This CSS file defines the styles for the web page, setting up a full-screen layout, styling the greeting message, and specifying the appearance of the fireworks particles.

`body, html`: Styles for the body and html elements.<br>
`#fireworks-container`: Styles for the container div.<br>
`h1`: Styles for the greeting message.<br>
`@keyframes fadeIn`: Keyframes for a fade-in animation.<br>
`.particle`: Styles for the fireworks particles.<br>

<br>

### NewYearFireWorks.js

This JavaScript file contains the logic to create fireworks particles when the user moves the mouse. It generates random particles with different colors and animations, creating a dynamic and festive display.

`let canCreateFirework = true;`: Variable to control the creation of fireworks.<br>
`document.getElementById("fireworks-container").addEventListener("mousemove", function (e) { ... });`: Event listener for mouse movement inside the container.
Checks if it's allowed to create fireworks (canCreateFirework).
Creates 20 particles with random colors and animations when the mouse moves.<br>
`function getRandomColor() { ... }`: Generates a random color for the fireworks particles.<br>
`function moveAndFade(particle, vx, vy) { ... }`: Moves and fades the particle over time, creating the animation effect.<br>

<br>

## How to Use <br>

Simply open the NewYearFireWorks.html file in a web browser to experience the New Year's fireworks celebration. Move your mouse to see the interactive fireworks display and enjoy the greeting message.

<br>

Feel free to customize the styles and tweak the JavaScript logic to suit your preferences for a personalized New Year's celebration experience.
