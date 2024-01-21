# iqfeed-docker

Given that the [IQFeed API](https://www.iqfeed.net/) is only available on 
Windows, an installation of [Wine](https://www.winehq.org/) is necessary for the 
API to work with a Linux Docker image.

Use this Docker file to build a Debian image that contains the IQFeed.exe 
installed using Wine. The pre-built image can then be uploaded to the Docker Hub
to accelerate the deployment of the IQFeed data streaming API.

Alternatively, you can pull the pre-built image from the 
[Fractal Gambit](https://hub.docker.com/u/fractalgambit) Docker Hub.
