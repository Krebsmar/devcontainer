```
docker pull ghcr.io/krebsmar/devcontainer/golang:{{image_tag}}
```
or build on your own
```
docker build . -t golang
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host golang sh
```