# Dockerfiles

## Building a package

*Example using ubuntu-focal*

Build the docker image for the target distribution :
```sh
docker image build -t makepkg/ubuntu-focal `pwd`/ubuntu-focal/
```

Then go to the package directory and run :
```sh
docker run --rm -it -v `pwd`:/pkg  makepkg/ubuntu-focal
```
