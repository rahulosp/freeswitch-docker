# freeswitch-docker
Repository to run freeswitch as a docker container
If you need the image directly you can pull rahulosp/freeswitch:1.10 from dockerhub

#Steps to create the image from scratch
git clone https://github.com/rahulosp/freeswitch-docker.git
git clone https://github.com/signalwire/freeswitch.git
cp -a ./freeswitch/conf/minimal ./freeswitch-docker/freeswitch/conf
cd ./freeswitch-docker/
docker-compose up -d --build
