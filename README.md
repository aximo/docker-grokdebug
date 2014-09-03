# Grok Debugger

This Docker container aims to run the [Grok debugger](https://grokdebug.herokuapp.com/), which is running on Heroku, on your own laptop / server.


## How to use this image

* **Start the Grok Debugger container :**


    docker run -d --name grokd -p 80:80 fdrouet/grokdebug:v1

_This image includes `EXPOSE 80` (the http port)_

* **Use the Grok Debugger :**

Go to [http://localhost:80]() to access the web interface

* **Stop the Grok Debugger container :**


    docker stop -t 2 grokd
