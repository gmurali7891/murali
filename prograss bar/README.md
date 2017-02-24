# reactivePB

This a Frontend Assignment - Progress Bars

Requirements:
 * Behaviours
 * Multiple bars
 * One set of controls that can control each bar on the fly
 * Can't go under 0
 * Can go over 100, but limit the bar itself and change its colour
 * Display usage amount, centered
 * Write tests for your code (hint: TDD strongly preferred)
 * Implement a responsive solution: testing it on mobile, tablet, etc. Getting it working nicely.
 * Animate the bar change, make sure it works well when you tap buttons quickly.
 * Publish your code online somewhere: github or something like plnkr.co, jsfiddle.net
 * Bonus points for implementing "production quality" code, using practices such as:
 * Setting it up as a project
 * Setting up some automated tools
 * Version control (git)
 * Linting, code quality, etc
 * JavaScript/CSS minification, packaging, etc
 * Using a CSS preprocessor like SASS/SCSS
 * Styling it to a production quality level

# Project
I decided to create a git project to be able to work on it remotely and keep all changes stored for versioning issues.

I decided to use grunt.js to build the project automatically.
  * use concat task to concat all my js file and import in the project;
  * use wiredep to built the project with all the bower_components linking the js files and css files;

I decided to use bower to be able to keep all third part frameworks and plugin always updated and tracked.

I decided to use this following frameworks:

  - Jquery [ bases for a lot front-end frameworks ]
  - Bootstrap [ one of my favorite framework to avoid responsive issue and create easly 'flat' and 'modern' website ]
  - Bootstrap-select [ one important plugin to integrate 'selectpicker' in bootstrap style ]
  - reactive [ use this important DOM-Manipulator framework was the main goal of this task ]
  
# Features

Next steps to improve the project will be 

  * use SCSS/SASS preprocess and add 'compass' task to gruntfile.js
  * use require.js to manange all the bower packages and import the right one in the right moment.
   
  
For the moment I didn't use sass preprocessor because I've met few issues with compass-watch and I decided to use as first release CSS
files.
  
