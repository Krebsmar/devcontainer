```
docker build . -t kube-tools
```
```
docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host kube-tools sh
```