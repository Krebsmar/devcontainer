```
docker pull ghcr.io/krebsmar/devcontainer/terraform:{{image_tag}}
```
or build on your own
```
docker build . -t terraform
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host terraform sh
```
.