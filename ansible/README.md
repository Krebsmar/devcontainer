```
docker pull ghcr.io/krebsmar/devcontainer/ansible:{{image_tag}}
```
or build on your own
```
docker build . -t ansible
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host ansible sh
```