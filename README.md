# TimelineWEB
A simple web component to display a timeline sequence (equidistant spaced points).
Used to integrate a timeline component into a Data Studio dashboard.
![GitHub Logo](/example.jpg)
Format: ![Timeline example](url)

## Technology
* HTML/CSS
* Papaparse for google sheet parsing
* JQuery 2.1.4

## Input: GET parameters
key: google sheet key id 
sheet: sheet's id (gid)
range: range with data (without headers)

## Data
3 columns:
- Date (text)
- Description
- Progress (0:done or 1:todo)

** EXAMPLE REQUEST **
https://cesarmiguel85.github.io/TimelineWEB/index.html?key=1RmLSPsRnB-s93FkFDrZnr5rGestwebNn0bQ1XbYYITc&sheet=1420769761&range=E2:G100
