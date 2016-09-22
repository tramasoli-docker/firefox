# firefox
Ubuntu 16.04 firefox - from http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/

# to run
docker run -ti --rm \

       -e DISPLAY=$DISPLAY \
       
       -v /tmp/.X11-unix:/tmp/.X11-unix \
       
       firefox --no-remote
