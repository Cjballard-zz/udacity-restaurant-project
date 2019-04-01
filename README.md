# Restaurant Reviews Project

## Project Overview
This project is part of Udacity's Front-End Nanodegree Program. Starting with a starter Restaurant Reviews project, the goal was to improve accessibility, conform to responsive design and institute a service worker to cache assets for offline.

## Improvements made
After downloading the [Starter Project](https://github.com/udacity/mws-restaurant-stage-1), I made the following improvements to the code:
- Created a responsive stylesheet that uses media queries to make the site responsive for mobile use.
- Included "alt" tags on images so they can be read by a screen reader.
- Improved the accessibility of the map and filter forms so screen readers are more clear.
- Increased color contrast and font sizes to be more readable and accesssible for all users.
- Created a service worker that will cache offline assets and lead to a better experience.

### How to set up
Download this repo and navigate into the project folder. In this folder, start up a simple HTTP server to serve up the site files on your local computer with [Python](https://www.python.org/).

From Udacity:
> In a terminal, check the version of Python you have: python -V. If you have Python 2.x, spin up the server with python -m SimpleHTTPServer 8000 (or some other port, if port 8000 is already in use.) For Python 3.x, you can use python3 -m http.server 8000. If you don't have Python installed, navigate to Python's website to download and install the software.
Note - For Windows systems, Python 3.x is installed as python by default. To start a Python 3.x server, you can simply enter python -m http.server 8000.

> With your server running, visit the site: http://localhost:8000, and look around for a bit to see what the current experience looks like.

### Dependencies
This project is created with HTML, CSS, basic Javascript and includes a Leaflet map built with [Mapbox](https://www.mapbox.com/). No other dependencies to install.