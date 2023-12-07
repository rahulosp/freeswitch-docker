# freeswitch-docker
Repository to run freeswitch as a docker container
If you need the image directly you can pull rahulosp/freeswitch:1.10 from dockerhub

#Steps to create the image from scratch
1. git clone https://github.com/rahulosp/freeswitch-docker.git
2. git clone https://github.com/signalwire/freeswitch.git
3. cp -a ./freeswitch/conf/minimal ./freeswitch-docker/freeswitch/conf
4. cd ./freeswitch-docker/
5. docker-compose up -d --build

