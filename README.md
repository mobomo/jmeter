# JMeter container

## Instructions added by Mobomo
must be on a linux system. Running the following command will launch the GUI in X11. Any tests you have should be put into the /tests folder. That is shared the the host

```
docker-compose up
```

Tada!

#### Jenkins to run JMeter headless (k8s):

> https://github.com/qazynx/jmeter/tree/master/yaml

#### JMeter GUI via docker run :

> docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix mimi50/jmeter

#### Shell into JMeter container:

> docker run -it --rm --name jmeter mimi50/jmeter /bin/bash


