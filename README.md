frontend-nanodegree-mobile-portfolio
===============================

What is this?
------------
This is project p4 assignment.
There are 2 parts to this project

Assignment 1
------------
index.html has been optimized with Google PageSpeed Insights. 
The score obtained with PageSpeed Insights is 95 / 100 for Mobile and 97 / 100 for Desktop. This can be verified with this Github URL http://gitapriyam.github.io/

This can also can be verified by checking out this project https://github.com/gitapriyam/frontend-nanodegree-mobile-portfolio.git from Git using the following steps

-----------------------------------------------
    1) Check out the repository https://github.com/gitapriyam/frontend-nanodegree-mobile-portfolio.git

    To inspect the site on your phone, you can run a local server

    $> cd /path/to/your-project-folder
    $> python -m SimpleHTTPServer 8080

    Open a browser and visit localhost:8080

    Download and install ngrok to make your local server accessible remotely.

    $> cd /path/to/your-project-folder
    $> ngrok 8080

    Copy the public URL ngrok gives you and try running it through PageSpeed.
--------------------------------------------------------------------------

Assignment 2
------------
Part 1
------
The Scrolling Pizza page pizza.html under views folder has been optimized to run at 60fps by modifying the views/js/main.js file
Appropriate comments have been added to the main.js file on the changes made.
I have also included a snapshot of the timeline when I last ran it with my local machine. It is available with git repository with the file TimelineRawData-20150405T165954.json. The fps can verified with this file too.
Here is the console output
Average time to generate last 10 frames: 0.23670000227866694ms main.js:509 Average time to generate last 10 frames: 0.19219999958295375ms main.js:509 Average time to generate last 10 frames: 0.20849999928032048ms main.js:509 Average time to generate last 10 frames: 0.22489999973913655ms main.js:509

Part 2
------
Resize Pizza Optimization to less than 5 seconds
This has been accomplished using JQuery. 
main.js function changePizzaSizes has been changed to incorporate JQuery
to improve efficiency.
The console output got for resizing the pizzas is
Time to resize pizzas: 2.0399999993969686ms
