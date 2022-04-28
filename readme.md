
# React-D3-Bubblechart
The famous d3 v4 Bubble Chart done in a [React + d3 Hybrid Approach](http://cmichel.io/how-to-use-d3js-in-react/). 


## Running
D3 needs to be run from a web server due to how it imports data files.

See more here: https://github.com/mbostock/d3/wiki#using

So, to run this visualization locally, from the Terminal, navigate to the directory you checked it out to

cd ~/code/path/to/bubble_chart_v4
Then start a webserver locally. If you are on a Linux or Mac, you should be able to use python's built in webserver:

python -m SimpleHTTPServer 3000
Alternatively, I have switched to using node's http-server for local hosting.

Ensure you have the node package installed:

npm install -g http-server
And then run it in the root directory of the repository.

http-server

