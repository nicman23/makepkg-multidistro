FROM debian:buster

VOLUME ["/pkg"]

RUN apt-get --assume-yes update
RUN apt-get --assume-yes upgrade
RUN apt-get --assume-yes install build-essential reprepro rsync wget zip git 

ENTRYPOINT ["makepkg"]
