FROM archlinux/base

VOLUME ["/pkg"]

RUN pacman -Syu --noconfirm
RUN pacman -S --noconfirm base-devel git wget rsync tar zip sudo

ENTRYPOINT ["makepkg"]
