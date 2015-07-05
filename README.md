Getting started

Some useful tips to help you get started:

Check out the repository
To inspect the site on your phone, you can run a local server

$> cd /path/to/your-project-folder
$> python -m SimpleHTTPServer 8080
Open a browser and visit localhost:8080

Download and install ngrok to make your local server accessible remotely.

$> cd /path/to/your-project-folder
$> ngrok 8080
Copy the public URL ngrok gives you and try running it through PageSpeed Insights! More on integrating ngrok, Grunt and PageSpeed.

Optimizations for Frames per Second in pizza.html

Fix
---
---
main.js
Modified function updatePositions() by creating a new location variable outside of loop.
Modified function changePizzaSizes(size) by instatianting dx & newwidth variable outside of loop.

pizza.html
reduced critical path length by making main.js async.

Resources
udacity.com
w3schools.com
