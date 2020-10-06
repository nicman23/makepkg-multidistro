FROM centos:7

VOLUME ["/pkg"]

RUN yum -y install epel-release
RUN yum -y upgrade
RUN yum -y groupinstall 'Development Tools'
RUN yum -y install tar expect rpm-build rpm-sign openssl createrepo rsync make automake gcc wget zip git

ENTRYPOINT ["makepkg"]
