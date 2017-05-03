# angularjs-website
using angularjs, html, css


##In the computer, you should have node install and set the node modules npm follwing these commands:

$ node install 
$ npm install npm --global


##You need to set up a server in order to run the app 

Here is a quick tutorial on how to set up a Python HTTP server.

**Install Python**

You'll normally install Python as part of your CentOS installation. Verify that Python is running by entering "python" from the command line. 

If Python isn't already installed, you can install it with a yum command similar to the following:

$ yum -y install python27 python27-devel

**Start Python**

Assume for this example that you want /angularjs-website to be your HTTP server directory. Go to that directory and start the Python HTTP server with the following commands:

$ cd /angularjs-website
$ python -m SimpleHTTPServer
You should see the following message indicating that the HTTP server is serving port 8000 by default:

Serving HTTP on 0.0.0.0 port 8000 ...
