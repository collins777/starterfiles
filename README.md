# starterfiles
Starter Files
These are simply starter files for new projects, the only purpose they serve is to speed
the developement process. Instead of using Gulp as a build tool I've used NPM scripts.

Upon downloading, follow steps:

1. Open Terminal 

2. Prompt command "npm i" or "npm install"

3. Prompt command "npm run start" *** this will start the live-server and compile sass while watching for changes*** 
* note: if the live server opens a 'listing directory', simply click the 'build' folder in the browser window to begin'*

4. Once project is complete, navigate to the terminal and enter 'npm run build:css'
* this will run all npm scripts optimizing project for maximum web perfomance *

********************* NPM SCRIPT DOCS *********************


"watch:sass": uses node-sass to watch for changes in  "scss/main.scss" files

"devserver": opens live-server

"start": starts the live server, watches and compiles sass files

"compile:sass": uses node-sass to compile "scss/main.scss file" into "build/css/style.comp.css" file 

"concat:css": uses concat to create new file in build folder called "build/css/style.concat.css" witch is both "build/css/style.comp.css" and "build/css/style.min.css" in one

"prefix:css": calls postcss in order to use autoprefixer which will prefix "build/css/style.concat.css" to the last 10 versions in the file "build/css/style.prefix.css"

"compress:css": uses node-sass to compress "build/css/style.prefix.css" into the minified  "build/css/style.min.css" file

"build:css": runs all npm scripts ** do not delete style.min.css **

********************* HAPPY CODING *********************
