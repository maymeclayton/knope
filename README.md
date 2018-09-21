# Instructions

converting sass to css:

Repository:
1) Create an input.scss file to store your sass information

2) Create an output.css file that will hold the converted sass

3) Link to the .css file in our html file

Command line: (under the correct repository)
1) Create json files
run npm init

2) Install sass to the project
run npm --save -dev install sass

3) Install browser-sync to the project
run npm --save -dev install browser-sync

4) Set watch command for both sass and b)browser-sync

./node_modules/.bin/sass input.scss output.css --watch

5) Set watch command for browser-sync

./node_modules/.bin/browser-sync start --server --files "output.css"



This will allow you to see updates to the .scss file automatically update the site.
