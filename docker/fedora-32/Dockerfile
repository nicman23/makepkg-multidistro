FROM fedora:32

VOLUME ["/pkg"]

RUN yum -y upgrade
RUN yum -y groupinstall 'Development Tools'
RUN yum -y install tar expect gpg rpm-build rpm-sign openssl createrepo rsync make automake gcc wget zip git 

ENTRYPOINT ["makepkg"]
