# HW2-Simple-Python-Server
HW2 Creating a simple python server

##SEIS752 – Advanced Web Application Development   [Spring 2015]
#####Professor Lloyd Cledwyn
#####HW #2  
##Simple HTTP Server
Due: Feb 18th, 6pm

###Summary
In class we built a simple socket interface. We set up a socket server, and had a client connect and communicate with the server.  In this exercise we will extend the socket server and create a very basic HTTP server.
###Purpose:
To understand basic communication details at the point of the HTTP server
Build a proper HTTP response
###Assignment:
1. Fork this project into your own repo
2. Download Python from http://python.org/download/  (Be sure and download 2.7, not version 3)
3. Submit by creating a pull request to the original.

The HW2 project file has a working "site" that you should extend for this homework.  Open the server file and look over the code.  The   HTML files (*.html) are a very very basic "site" to get a sense of what's happening.  You should be able to run the server file and navigate to http://localhost:2000/index.html and click the links.   

UPDATE:  In the Python version, use port 9000.  Also Running python in windows has one additional quirk.  By default it reads a file's text, in order to have it open, and sucesfully pass the image file on in your web server you will need to explicitly tell it to open the file as a binary file.  Add the 'rb' parameter to the open file command.

```f = open(curdir + sep + self.path, 'rb')```


####VIDEO NOTES:  
(yes the default display is small, but if you click on "full size" then it will display in full resolution)

1. [Intro to thoughts about the assignment, and getting the python version running.](http://www.screencast.com/users/cledwyn/folders/Jing/media/ad7a479b-b5f5-497f-b98e-73de1ed5935d) (5min)
2. [Part 2 of getting Python to work.](http://screencast.com/t/aqyRuqH2Z) (2:13)



###Deliverables
  1. Run the server as it is and notice what is written to the command window as you click on the links.  What is going on here?  (Short paragraph or two.)
  2. Build a simple 3-5 page website.
    1. Interlink the pages so you can navigate between all of them.
    2. Include some (at least 2) images, at least one GIF and one JPG.
Change the server code to enable you to
         1. render GIFs in your web pages
         2. render JPGs in your web pages
         3. allow the default request (http://localhost:9000/) return index.html
         4. With images working on your pages, note what is happening in the command window as you click from page to page.
        
Submit the file as a pull request to the original project.